# composite-action-practice

This action prints "WOW" or user input as ASCII art to the log and validates inputs of a user against a schema defined in Spots87/validate-schema-js/index.js

## Inputs

## `my-text`

**Required** Text to convert to ASCII art. Default `"WOW"`.

This action validates a inputs against a schema defined in index.js

## `user-name`

**Required** The name of the User to validate. Default `"Tim"`.

## `user-age`

**Required** The age of the User to validate. Default `"35"`.

## `user-email`

**Required** The email of the User to validate. Default `"admin@example.com"`.


## Outputs

## `is-valid`

Message declaring if inputs are valid from schema.

  ## Example usage

uses: Spots87/ascii-action@v1
with:
  my-text: 'NEATO'
  user-name: 'Joe'
  user-age: '25'
  user-email: 'joeCool@gmail.com'