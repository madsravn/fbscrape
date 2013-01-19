# Facebook Page Photo Scrapper

This is an experiment on writing an Facebook page image scrapper with CoffeeScript and NodeJS. 

Using openly available data on the Facebook Graph API we look for images that are posted by a page and download them to our local machine. 

Good for backing up images for Facebook pages and other purposes that I shall not mention.

## Install

Make sure you have NodeJS installed. Then do: 

    npm install fbscrap -g

## How To Use

For basic use, you need to have two things:

* The page ID of the Facebook page you want to scrap, e.g. if the page is [https://www.facebook.com/Starbucks](https://www.facebook.com/Starbucks), the page ID will be `starbucks`

* Any active access token. You can get an access token by going to this page: [https://developers.facebook.com/tools/explorer](https://developers.facebook.com/tools/explorer)

To run the command, type

    fbscrap -p <page id> -t <access token>

Type `fbscrap -h` for full options.

    ===Facebook Page Image Scrapper===

      Usage: fbscrap [options]

      Options:

        -h, --help             output usage information
        -V, --version          output the version number
        -p, --page <page>      Facebook Page ID that you want to scrap. For example, 
                               https://www.facebook.com/starbucks page ID will be starbucks
        -t, --token <token>    Your access token. Generate an access token from 
                               https://developers.facebook.com/tools/explorer
        -l, --limit <limit>    Maximum number of images that you want to scrap, defaults to 10
        -o, --output <output>  Where to store the images. Defaults to ./images

## Disclaimer

This tool is meant for personal use only. The author of this tool is not responsible for any damages or loss caused by the use of this tool. With great power comes great responsibility. You are responsible to keep your fapping material safe and sound.



