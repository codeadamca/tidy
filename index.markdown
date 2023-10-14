# tidy

<style>@import url("//readme.codeadam.ca/readme.css");</style>

A list of programming guidelines to follow for all BrickMMO related development.

## Database Conventions

All database naming conventions follow [Laravel Eloquent](https://laravel.com/docs/10.x/eloquent) conventions along with [eplus](https://eplus.codeadam.ca/). It is recommended to use the Laravel migration process for creation and upkeep of BrickMMO databases.

## GitHub Repos

All GitHub repos should be created within the [BrickMMO GitHub Organization](https://github.com/BrickMMO) and use the following process to develop:

1. Fork the desired repo
2. Make changes to the forked repo
3. Submit a pull request to the original repo

## Coding Guidelines

1. Parentheses are placed om their own lines:

    ```php
    if ($value == true) 
    {
      // Code to execute
    }
    ```

2. Brackets following an if statement, loop, etc... have a space between the constructor and condition:

    ```javascript
    for (let i = 0; i < 3; i ++)
    {
      // Code to execute
    }
    ```
    
> This repo is available to view at  
> [https://tidy.codeadam.ca](https://tidy.codeadam.ca).

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
