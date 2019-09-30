# Rails rules in IT team

## Naming (1 point)
1. Model Naming: singular
1. Controller Naming: plural
1. Migration: add index to the key which has suffix "_id"
1. Migration Naming: must be can readable, for_example: add_role_to_users 
1. Naming: all the function and variable are need underscore. for_example: check_user_role
1. function naming with '?': prefix is_xxx? and only return true or false
1. function naming with '!': this function must be change(insert update delete) data to database.
1. Javascript: only .js
1. Css: only .scss

## attention
1. Don't repeat yourself (DRY)

## i18N
1. [language.yml example](./language.yml) take something as reference
