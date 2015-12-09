# Blank App

```
rails new router-demo
cd router-demo
bundle
bin/rake db:create

bin/rake routes
# rails tells us we have not created any routes

bin/rails server
# when we open app in browser, it also tells us to add some routes
```


# Simple Route
````
git checkout 0.0-simple-route-INITIAL
bin/rails generate controller pages index
bin/rake routes
````