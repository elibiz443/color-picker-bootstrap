# color-picker-bootstrap

Steps:

## Create Project
```
rails new color-picker-bootstrap -j esbuild -c bootstrap -T -d postgresql && cd color-picker-bootstrap && subl .
```

## Create Scaffold:
```
rails g scaffold post title body:text font_color background_color
```

## Create & migrate DB:
```
rails db:create db:migrate
```

## Add index to routes:
```
root "posts#index"
```
 ## Run Server
```
bin/dev
```

## Run the following:
```
rails g stimulus colors

yarn add @melloware/coloris
```

Add in Gemfile ```gem 'foreman', github: 'ddollar/foreman'```
then ```bundle```

Update stimulus controller and form.
