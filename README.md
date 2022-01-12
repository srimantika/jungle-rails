# Jungle

A mini e-commerce application built with Rails 4.2 for purposes of teaching Rails by example.

## Landing Page
!["Screenshot of Home Page"](https://github.com/srimantika/jungle-rails/blob/659ba9fb323f3593055acab7b9c4d21d433caabd/docs/Sales%20display.png)
## Sold Out Tag
!["Screenshot of Sold Out"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Sold%20Out.png)
## Categorywise product display
!["Screenshot of Categorywise Product Display"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Product%20Categorywise%20display.png)
## My Cart
!["Screenshot of My Cart"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/My%20Cart.png)
## Categories
!["Screenshot of Categories"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Categories.png)
## Admin Functions
!["Screenshot of Admin Functions"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Admin%20functions.png)
### Admin Dashboard
!["Screenshot of Admin Dashboard"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Admin%20Dashboard.png)
### Admin - All Products
!["Screenshot of Admin All Products"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Admin_All%20Products.png)
### Admin - All Sales
!["Screenshot of Admin All Sales"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Admin_All%20Sales.png)
### Admin - Create New Category
!["Screenshot of Admin Create New Category"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Admin_create%20new%20category.png)
### Admin - Create New Sales
!["Screenshot of Admin Create New Sales"](https://github.com/srimantika/jungle-rails/blob/3da3010d2fd979289ed3242b4d0c8beefded1f18/docs/Admin_create%20new%20sale.png)


## Additional Steps for Apple M1 Machines

1. Make sure that you are runnning Ruby 2.6.6 (`ruby -v`)
1. Install ImageMagick `brew install imagemagick imagemagick@6 --build-from-source`
2. Remove Gemfile.lock
3. Replace Gemfile with version provided [here](https://gist.githubusercontent.com/FrancisBourgouin/831795ae12c4704687a0c2496d91a727/raw/ce8e2104f725f43e56650d404169c7b11c33a5c5/Gemfile)

## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe
