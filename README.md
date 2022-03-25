# Startpage
This project is just a small startpage / hub.

## Usage
Either head over to [startpage.toastyfiles.com](https://startpage.toastyfiles.com) and just put in your config, or if you don't want to rely on my website (maybe for privacy concerns), you can host your own!

The first time you enter the website you will be greeted by the config menu, in here you have to input a json object with your config.

```json
{
    "links": {
        "category": {
            "name": "link"
        }
    },
    "shortcuts": {
        "key": "link-name-to-open"
    },
    "calendar": {
        "url": "ics-link"
    }
}
```

You can omit any of the properties you don't want to use. To change any of the settings later you can press `Ctrl + Shift + S` to bring up and close the settings menu.

## Hosting
Just put the `index.html` in the webroot of your favourite web server and off you go!

## Quotes
If you wish to not use the quotes you will have to change the code to remove the api calls. If you implement the same api calls as [quotable.io](https://quotable.io) uses you can just replace the URL to use your own quote provider.