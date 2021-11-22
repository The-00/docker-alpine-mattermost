# docker-alpine-mattermost

docker version of mattermost based on alpine-s6 with auto create of admin user

# Auto configuration parameters :

```
- ADMIN_USER   username of the admin user (ex: admin)
- ADMIN_PASS   password of the admin user (ex: i%5lf)
- ADMIN_MAIL   email    of the admin user (ex: a@a.a)

- MM_*******   every configuration variable used by mattermost (https://docs.mattermost.com/configure/configuration-settings.html#environment-variables)
```

# Docker compose with mariadb in the repository

# [In comming] Docker compose with LDAP configuration

I will use Mattermost-LDAP : https://github.com/Crivaledaz/Mattermost-LDAP

### you can find the image in docker hub : ttrova/mattermost
