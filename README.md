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

## How To Install Vue Scaffolding

To install Vue scaffolding on your project, you must have laravel/ui package installed on your laravel project.
Navigate to your project directory in your terminal / command-line and run the following command to install the package

```
composer require laravel/ui
```

Once the package is installed, you can run the following artisan command to generate the Vue Scaffolding.

```
php artisan ui vue
```

Once the scaffolding is installed, you will see the following new folder and files generated in your resources > js folder.

![scaffolding](https://i.imgur.com/1KpAlHV.png)

With that, it also adds some new dependencies in our package.json file.

```
"vue": "^2.5.17",
"vue-template-compiler": "^2.6.10"
```

Run the following command to install dependencies

```
npm install
```

Once all the dependencies are installed, it’s time to build.

Run the following npm command

```
npm run dev
```

## Using Vue Example Component

Now, since we have everything ready, let’s make use of example component which is provided by default Vue scaffolding.

The component is globally registered in _resources > js > app.js_ file.

```
Vue.component('example-component', require('./components/ExampleComponent.vue').default);
```

Since the component is globally registered, we can use inside our Vue Instance. Open _welcome.blade.php_ file

Include the following script just before the end of the body tag or in the header below the title.

```
<script src="js/app.js"></script>
```

This will include the js which we built in the last step on the welcome page. Now since we have Vue instance and it’s a component available on the page. We can use the Vue component.

You can use the example-component inside any div with an id of the app. For the demonstration, I have just placed it after the Laravel text.

```
<div class="content" id="app">
    <div class="title m-b-md">
        Laravel
    </div>

    <example-component></example-component>

    ...
</div>
```

This should spit the content of Component’s template.

![scaffolding](https://i.imgur.com/yzkNsHD.png)

Have Fun with Laravel & Vue.
