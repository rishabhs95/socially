## Socially
Socially is an open source social networking platform written in Ruby on Rails.

### What it uses?
* [Ruby on Rails](https://github.com/rails/rails)
* [Bootstrap](https://github.com/twbs/bootstrap-sass)
* [Devise](https://github.com/plataformatec/devise)
* [Public Activity](https://github.com/chaps-io/public_activity)

```
Using DRY(do not repeat yourself) concept, this project uses gems to minimize code
 and increase code quality.
```

### How do I get set up?
To set it up on your local machine here is what you need to do. Install Ruby & Rails. Clone this repo using the following command:

```
git clone https://github.com/rishabhs95/socially
cd socially
```

Then resolve dependencies using bundler:

```
bundle install
```

Run Migrations:

```
rake db:migrate
```

Run rails using

```
rails server
```

### User stories
 - As a visitor, I can register an account and sign in
 - As a signed in user, I can sign out
 - As a signed in user, I can upload an image
 - As both a signed in user and visitor, I can view uploaded images
 - As a signed in user, I can delete an image that I uploaded
 - As a signed in user, I can comment on an image
 - As a signed in user, I can follow other users
 - As a signed in user, I can share text updates
 - As a signed in user, I can update my profile
