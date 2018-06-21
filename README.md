# Simple Rails API JWT + Knock

## Instalation Step
1. Clone this repository
2. Run `bundle install`
3. Setup your `database.yml`
4. Run `rails db:create` to create database on postgresql
5. Run `rails db:migrate` to migrate all table

## Setup the basic Knock structure.
1. Run `rails generate knock:install`
2. Run `rails generate knock:token_controller user`