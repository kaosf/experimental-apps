# Experimental Apps

http://experiment.kaosfield.net

or

http://ka-exp-apps.herokuapp.com

## Deployment to Heroku

Configure DNS server. Set the CNAME of `experiment.kaosfield.net` to `ka-exp-apps.herokuapp.com`.

```sh
# run at only the first time
heroku create ka-exp-apps
heroku domains:add experiment.kaosfield.net
```

```sh
git push heroku master
```
