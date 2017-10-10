# Knex.js practice

## Instructions

Fork and clone this repository, then run `npm install` when in the project directory.

This repo is for setting up a basic connection to knex without express in the way. Here are the steps to re-create it.

1. Install knex globally with the command `npm install -g knex`
1. Initialize knex with the command `knex init`
1. Using knex help (`knex -h` and the website) as a guide, do the following
    1. configure the __knexfile__ to point towards a local database
    1. Create a migration to create a table with an id column, and at least one other column
    1. Create a seed file to put at least 3 rows of data into the table
    1. Create a JavaScript file that connects to the database using Knex.js and runs a query, logging out the result
