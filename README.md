# animated-content-placeholder [![Bower version](https://badge.fury.io/bo/animated-content-placeholder.svg)](http://badge.fury.io/bo/animated-content-placeholder) [![Travis state](https://travis-ci.org/Collaborne/animated-content-placeholder.svg?branch=master)](https://travis-ci.org/Collaborne/animated-content-placeholder) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Collaborne/animated-content-placeholder)

Animated placeholder used while loading elements on the page. This element is built for [Polymer](https://www.polymer-project.org).

This element is based on the [deconstruction of the Facebook placeholders](http://cloudcannon.com/deconstructions/2014/11/15/facebook-content-placeholder-deconstruction.html) by George Phillips.

It provides a basic animation on the background, and the possibility of overlaying it with maskers to create the illusion of a loading element on the page.

To use the element:

`bower install animated-content-placeholder`

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="animated-content-placeholder.html">
    <custom-style>
      <style is="custom-style">
        .background-masker {
          background: #fff;
          position: absolute;
        }

        .background-masker.header-top {
          top: 0;
          left: 48px;
          right: 0;
          height: 4px;
        }

        .background-masker.header-left {
          top: 4px;
          left: 48px;
          height: 16px;
          width: 8px;
        }

        .background-masker.header-bottom {
          top: 20px;
          left: 48px;
          right: 0;
          height: 10px;
        }

        .background-masker.subheader-left {
          top: 30px;
          left: 48px;
          height: 12px;
          width: 8px;
        }

        .background-masker.subheader-right {
          top: 30px;
          left: 200px;
          right: 0;
          height: 12px;
        }

        .background-masker.subheader-bottom {
          top: 42px;
          left: 48px;
          right: 0;
          height: 8px;
        }
      </style>
    </custom-style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<animated-content-placeholder>
<div class="background-masker header-top"></div>
  <div class="background-masker header-left"></div>
  <div class="background-masker header-bottom"></div>
  <div class="background-masker subheader-left"></div>
  <div class="background-masker subheader-right"></div>
  <div class="background-masker subheader-bottom"></div>
</animated-content-placeholder>
```

### Styling
The following custom properties and mixins are available for styling:

Custom property | Description | Default
--------------- | ----------- | ---------
`--animation-height` | Height of the animated background |

## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2017 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
