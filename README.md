```
  ___                              ____       _           _   
 |_ _|_ __ ___   __ _  __ _  ___  / ___|  ___| | ___  ___| |_
  | || '_ ` _ \ / _` |/ _` |/ _ \ \___ \ / _ \ |/ _ \/ __| __|
  | || | | | | | (_| | (_| |  __/  ___) |  __/ |  __/ (__| |_
 |___|_| |_| |_|\__,_|\__, |\___| |____/ \___|_|\___|\___|\__|
                      |___/  v1.6
```

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/websemantics/Image-Select/master/LICENSE) [![GitHub forks](https://img.shields.io/github/forks/websemantics/Image-Select.svg)](https://github.com/websemantics/Image-Select/network) [![GitHub stars](https://img.shields.io/github/stars/websemantics/Image-Select.svg)](https://github.com/websemantics/Image-Select/stargazers)
[![Percentage of issues still open](http://isitmaintained.com/badge/open/websemantics/Image-Select.svg)](http://isitmaintained.com/project/websemantics/Image-Select "Percentage of issues still open")

> We designed this plugin extension as a humanized UI element for social networking sites that need to facilitate relations between people. Research shows that people are extremely sensitive to photos of others, so we needed to revamp the traditional UI elements to make them more intuitive and human.

## New Style
> Fresh flat styles and new logo & web design for better user experience

<img src="http://websemantics.github.io/Image-Select/img/sample-w540@2x.png" style="width:540px" alt="Image Select"/>

#### Try [Live](http://websemantics.github.io/Image-Select/) or [Examples](http://websemantics.github.io/Image-Select/example.html)

## Use Scenarios

You can use these plugin extensions for modelling multiple (one-to-many) or single (one-to-one) relations between people.

We couldn't find any scripts that had this full functionality, so we developed it ourselves on top of Chosen. Hope you find it helpful, and get back if you have any feedback/improvements.

## Installation

- Clone locally, `git clone https://github.com/websemantics/Image-Select`
- Install dependencies, `bower install`
- Browse to `index.html` or `example.html`

### Via Bower

`bower install image-select`

To get information about available packages

`bower info image-select`

## Usage

You only need to add a `data-img-src` attribute to your `<option>` tag.
```HTML
<select class="my-select">
  <option data-img-src="img/adnan.png">Adnan Sagar</option>
  <option data-img-src="img/rena.png">Rena Cugelman</option>
  <option data-img-src="img/tavis.png">Tavis Lochhead</option>
  <option data-img-src="img/brian.png" selected="selected">Brain Cugelman</option>
</select>
```
Then call Chosen as you would with the options you need.
```JAVASCRIPT
$(".my-select").chosen();
```

# Used by

[PyroCMS Social Field Type](https://github.com/websemantics/social-field_type)

![demo](https://raw.githubusercontent.com/websemantics/Image-Select/master/img/social_field_type.gif)

## Related
Chosen, http://github.com/harvesthq/chosen
