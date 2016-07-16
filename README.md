# dotloader
A fun animated loading bar for the web.

## Usage

Include [dotloader.min.css](dotloader.min.css) in your webpage.

````html
<link href="dotloader.min.css" rel="stylesheet" />
````

Use the following HTML to show dotloader.

````html
<div class="dotloader">
  <div class="dl-dot dl-dot1"></div>
  <div class="dl-dot dl-dot2"></div>
  <div class="dl-dot dl-dot3"></div>
  <div class="dl-dot dl-dot4"></div>
  <div class="dl-dot dl-dot5"></div>
</div>
````

## Customization

By default, the dotloader dots will be colored black.  This can be easily changed by overriding the ````background-color```` css property.
````css
.dl-dot {
  background-color:white;
}
````
