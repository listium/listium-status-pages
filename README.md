# listium-server-error
A repo to manage and host the default page for when Heroku crashes fully.

http://listium.github.io/listium-status-pages/server-error.html
http://listium.github.io/listium-status-pages/maintenance.html

```
heroku config:set \
  ERROR_PAGE_URL=https://listium.github.io/listium-status-pages/server-error.html \
  MAINTENANCE_PAGE_URL=https://listium.github.io/listium-status-pages/maintenance.html
```

### Heroku maintenance mode
```
heroku maintenance:on
heroku maintenance:off
```
