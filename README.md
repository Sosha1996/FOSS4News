![FOSS4News_screenshot](doc/img/screenshot.png)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fsadraiiali%2FFOSS4News.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fsadraiiali%2FFOSS4News?ref=badge_shield)

# FOSS4News

Just a simple clone of The Hacker News based on [Laravel Framework](https://laravel.com/docs/7.x/) and [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/),which is in alpha stage. The project has been released in Persian/Farsi language. We are planning additional languages in the future.

> این صفحه را به فارسی در [اینجا](doc/README_FA.md) مشاهده کنید

## Run

before run this project you need to install [php](https://www.php.net/manual/en/install.php), [composer](https://getcomposer.org/), a dbms (like [mysql](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/)) and [npm](https://www.npmjs.com/get-npm).

1. First copy example environment and change it with your parameters.

   `cp .env.example .env`

2. Install PHP dependencies.

    `composer install`

3. Create App Key.

    `php artisan key:generate`

4. Create database tables.

    `php artisan migrate`

5. Link storage files to public.

    `php artisan storage:link`

6. Install JS dependencies.

    `npm install`

7. Run npm.

    `npm run dev` 

8. Run Project using php artisan.

    `php artisan serv`

## License

The main code is licensed under [GPLv3](https://github.com/sadraiiali/FOSS4News/blob/master/LICENSE).


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fsadraiiali%2FFOSS4News.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fsadraiiali%2FFOSS4News?ref=badge_large)

## Contribute

Feel free to clone project, add your code and then submit a pull request. Any participate is willing :)

## Maintainers

- [Alireza Sadraii Rad](https://github.com/sadraiiali/)
- [Mehran](https://github.com/meh666ran)