# bbq

A Ruby on Rails application, that allows you to create an event, pick a date, set a location, upload photos, share comments and invite your friends.

## Demo
[mymegabbq.herokuapp.com](https://mymegabbq.herokuapp.com/)

## Versions used

* ruby '2.6.3'
* rails '6.0.2.1'

## Installation

To use the code:

1. Download the repository using the [instruction](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
2. In the command line go to the directory with the files downloaded.
3. Install required gems. To do that:
  * Check if the bundler is installed with the command `gem list bundler`.
    * If it is not installed - installed it with the command `gem install bundler`.
    * If bundler is already installed, that is perfect. Go to the next step.
  * In the directory with the app, to install all necessary gems run:
```
bundle install --without production
```
4. Install all the dependencies listed within package.json in the local node_modules folder:
```
yarn install
```
5. To run migrations:
```
bundle exec rails db:migrate
```
