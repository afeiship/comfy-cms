# comfy-cms
> Comfy cms.

## install:
Add gem definition to your Gemfile:

```rb
gem "comfy_blog", "~> 2.0.0"
```
Then from the Rails project's root run:
```bash
bundle install
rails generate comfy:blog
rake db:migrate
```

Take a look inside your config/routes.rb file and you should see following lines there:

```rb
comfy_route :blog_admin, path: "admin"
comfy_route :blog, path: "blog"
```
You should also find view templates in /app/views/blog folder. Feel free to adjust them as you see fit.


## resouces:
- https://github.com/comfy/comfortable-mexican-sofa