# Experimental Apps

[https://ka-exp-apps.herokuapp.com/](https://ka-exp-apps.herokuapp.com/)

![alt https://ka-exp-apps.herokuapp.com/](qrcode.png)

## Deployment to Heroku

```sh
# run at only the first time
heroku apps:create ka-exp-apps
```

Set `HEROKU_API_TOKEN` [here](https://github.com/kaosf/experimental-apps/settings/secrets/actions).

```sh
# Deployment by GitHub Actions
git push origin main

# or
# Manual deployment
git push heroku main
```
