# Engineering Project 1 (Makersbnb)
I completed building an Airbnb clone as part of my first team engineering project during the 5th week of the Makers bootcamp. This web application allows users to list spaces they have available, and hire spaces for the night.

## User stories

Using TDD we implemented the following user stories:

As a guest,  
So I can use Makersbnb,  
I'd like to be able to register an account.

As a guest,  
For a personalised experience,  
I'd like to be able to see a list of available spaces.

As a host,  
So that I can use Makersbnb,  
I'd like to be able to register an account.

As a host,  
So that I can have guests,  
I'd like to be able to list available spaces with a short description of the space, and a price per night.

As a guest,  
So I can experience a new accomodation,  
I'd like to be able to request to book an available space.

As a host,  
So I can manage my properties,  
I'd like to approve bookings.

As a guest and host,  
So I can reduce my time on the internet,  
I'd like to logout of Makerbnb.


## Setup

```bash
# Install gems
bundle install

# Run the tests
rspec

# Run the server (better to do this in a separate terminal).
rackup
```

## Databases
- Bookings
- Users
- Spaces
- Hosts

## Technologies used
This application integrated a database using the 'pg' gem and Repository classes. We implemented the web application using Sinatra, RSpec, HTML and ERB views to make dynamic.
