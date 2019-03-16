# flarum-ext-lang-chinese
flarum extension - Chinese Language Pack

* Copy the code under ```vendor\dcluomax\flarum-ext-lang-chinese\```

* Steps to install without composer:

  add following code to ```vendor\composer\installed.json```

```php
{
        "name": "dcluomax/flarum-ext-lang-chinese",
        "version": "v0.1.0-beta.8",
        "version_normalized": "0.1.0.0-beta8",
        "require": {
            "flarum/core": "^0.1.0-beta.8"
        },
        "time": "2017-08-03T13:29:40+00:00",
        "type": "flarum-extension",
        "extra": {
            "flarum-extension": {
                "title": "Simplified Chinese",
                "icon": {
                    "image": "icon.svg",
                    "backgroundColor": "#DE2910",
                    "backgroundSize": "cover",
                    "backgroundPosition": "center"
                }
            },
            "flarum-locale": {
                "code": "zh",
                "title": "简体中文"
            }
        },
        "installation-source": "dist",
        "notification-url": "https://packagist.org/downloads/",
        "license": [
            "MIT"
        ],
        "authors": [
            {
                "name": "Max Luo"
            }
        ],
        "description": "Simplified Chinese language pack.",
        "keywords": [
            "locale"
        ]
    }
```
