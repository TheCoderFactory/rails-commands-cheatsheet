rails-commands-cheatsheet
=========================

# Rails commands
```
# Create a new app
rails new myapp
```

```
# Generate a complete scaffold (migration, model, controller, views)
rails g scaffold Object attribute:datatype

# Eg. Create a scaffold for a book with a title, author and summary
rails g scaffold Book title:string author:string summary:text
```

```
# Generate a controller and view/s
rails g controller controller_name action


# Eg. Create a home index page/home controller with index action
rails g controller home index
```

```
# Generate a data model with corresponding migration (a data model/database table)
rails g model Object attribute:datatype
```

```
# Add an attribute to a data model/database table
rails g migration AddAttributeToObject attribute:datatype
```



# Rake commands
```
# create database tables from migration file
rake db:migrate
```

```
# seed the database with data in db/seeds.rb file
rake db:seed
```

```
# rollback the last migration
rake db:rollback
```

```
# check your app’s routes
rake routes
```



# Git commands
```
# Initialise a git repository for your app
git init
```

```
# Add all files to your repository
git add --all
```

```
# Commit all changes to your repository
git commit -am 'message'
```

```
# Check the state of your git repository
git status
```

```
# Check your repository remote links
git remote -v
```

```
# Push the master branch of your repository to a remote named origin
git push origin master
```

```
# Create a new branch and checkout the new branch in one command
git checkout -b newbranch
```



# Heroku commands
```
# Create a new app/repository on Heroku
heroku create appname
```

```
# Migration
heroku run rake db:migrate
```

```
# Check Heroku logs
heroku logs
```
