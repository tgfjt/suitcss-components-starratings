# components for star-ratings

provides the star-ratings UI.

## Install

- npm: `npm install suitcss-components-starratings`
- Download: [zip](https://github.com/tgfjt/suitcss-components-starratings/releases/latest)

## Available classes

* `StarRatings`
* `StarRatings-star`

## Configurable variables

* `--StarRatings-letterspase`
* `--StarRatings-star`
* `--StarRatings-color-active`
* `--StarRatings-color-inactive`

## Usage

```html
<div class="StarRatings" aria-label="4 Stars">
  <span class="StarRatings-star" star="4"></span>
</div>

<div class="StarRatings" aria-label="2.5 Stars">
  <span class="StarRatings-star" star="2.5"></span>
</div>
```

## Test

`npm run build-test`
