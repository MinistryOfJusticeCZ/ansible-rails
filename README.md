Usage
====

This role setup rails application with database on same server.
PostgreSQL, Unicorn, Nginx.

Je potřeba nakonfigurovat alespoň tyto proměnné:
```yaml
rails_app_name: <name> # name of the application
rails__sidekiq: True #defaults to false - if to install sidekiq support - redis and restart scripts
```

More information about configuration: [defaults/main](roles/rails_app_psql/defaults/main.yml)