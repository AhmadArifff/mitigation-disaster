# Integrate Laravel Pint to PHPStorm

Laravel Pint is an opiniated PHP code style fixer for minimalist developers.

Documentation : [Laravel Pint](https://laravel.com/docs/10.x/pint)

## Install Laravel Pint

```bash
composer require laravel-pint/laravel-pint
```

## Configure PHPStorm

1. Open PHPStorm
2. Go to `Preferences` > `Languages & Frameworks` > `PHP` > `Quality Tools` > `Laravel Pint`
3. Switch to `ON`
4. Click on `...` button
5. Setup Laravel Pint path to `/vendor/bin/pint`
6. Click `Apply` or `OK`
7. Next setup pint json path to `/pint.json`
8. Set ruleset to `laravel`
9. Check`Reformat only uncommited files`
10. And on external formatter choose `Laravel Pint`
11. Click `Apply` or `OK`


