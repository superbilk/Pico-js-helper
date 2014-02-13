Pico-js-helper
==============

Include js as easy as
    {{ js("filename.js") }}

Plugin for [Pico](http://pico.dev7studios.com/), also see their Github Repository [https://github.com/gilbitron/Pico](https://github.com/gilbitron/Pico)


Installation
------------

copy the php file in your plugin folder

Setup
-----
You may add the following line to your ```config.php```

    $config['js_path'] = "/javascripts";

The path is related to your template path. e.g. ```/my_website/public/theme/my_theme/javascripts```

And in your twig templates you simply use ```{{ js("filename.js") }}``` to include ```/my_website/public/theme/my_theme/javascripts/filename.js```
