<p align="center"><img src="https://i.imgur.com/iOlG06h.png" width="400"></p>

<p align="center">
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Laravel Vue Base

A Laravel Vue SPA starter project template. I recommend using the Homestead environment for maximum coding ease and pleasure.

## How To Install cloned repo

1. Clone

```
git clone <Repo> <DestinationDirectoryName>
```

2. Run

```
composer install
```

3. Run

```
npm install
```

4. Create .env file. Copy all content in .env.example file and paste in .env file
5. Run command to generate app key

```
php artisan key:generate
```

6. Run Development. For hot reloads run the watch command

```
npm run dev || npm run watch
```

7. If you're using Homestead (recommended)

-   update Homestead.yaml by adding path to your project.

8. Run

```
sudo vim /etc/hosts
```

-   add your site to the list and save
