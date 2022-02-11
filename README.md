# Dester-Libdrive-Server


## use Magic to deploy on heroku

## auth0 configuration

### Create an application on auth0 [Single Page Application]

Application Login URI = blank

Allowed Callback URLs = frontend url [recommended to host it on vercel for now] example: https://app.vercel.app [without trailing slash]

Allowed Logout URLs = frontend url [recommended to host it on vercel for now] example: https://app.vercel.app [without trailing slash]

Allowed Web Origins = frontend url [recommended to host it on vercel for now] example: https://app.vercel.app [without trailing slash]

Allowed Origins (CORS) = blank

### Create an Api 

`Settings`

Identifier = just for reference any random domain but recommended to use your own even https://google.com will work

> RBAC Settings

--- Enable RBAC
--- Add Permissions in the Access Token
--- Allow Skipping User Consent [Upto you]

`Permissions tab`

#### Add a Permission

read:current_user


