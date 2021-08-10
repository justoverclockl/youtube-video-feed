# Youtube Video Feed Widget

![License](https://img.shields.io/badge/license-MIT-blue.svg) [![Latest Stable Version](https://img.shields.io/packagist/v/justoverclock/youtube-video-feed.svg)](https://packagist.org/packages/justoverclock/youtube-video-feed) [![Total Downloads](https://img.shields.io/packagist/dt/justoverclock/youtube-video-feed.svg)](https://packagist.org/packages/justoverclock/youtube-video-feed)

A [Flarum](http://flarum.org) extension. Fetch last 3 youtube videos from youtube

![11](https://user-images.githubusercontent.com/79002016/128869390-947be3b5-bf7d-4de2-b072-0d1821421173.png)

## Important

Youtube serve video thumbnail in max resolutions only if the width of your video is equal or more than 321px, under that width, the images is in low quality.


## Installation

Install with composer:

```sh
composer require justoverclock/youtube-video-feed:"*"
```

## Updating

```sh
composer update justoverclock/youtube-video-feed:"*"
php flarum migrate
php flarum cache:clear
```

## Links

- [Packagist](https://packagist.org/packages/justoverclock/youtube-video-feed)
- [GitHub](https://github.com/justoverclock/youtube-video-feed)
- [Discuss](https://discuss.flarum.org/d/PUT_DISCUSS_SLUG_HERE)
