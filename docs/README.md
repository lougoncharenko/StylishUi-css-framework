# Stylish UI

## About the css framework

     Welcome to Stylish UI, a lightweight CSS Framework. Stylish UI is a
    style sheet that provides styling to different html element on your
    website by adding class names. You should use Stylish UI if you are
    working on a small to medium application, if you feel that you dont
    need all the larger frameworks features, or if you just want to code
    and grow all the style by yourself. Here are some of Stylish UI's
    coolest characteristics:

## Coolest features

📦 Pretty small package

The complete source has ~5kb gzipped, or 28 kb inflated.

⛔ No JavaScript

Completly javascript free. Is just pure and simple CSS. You can test
it by disabling javascript and reloading this page.

🖌 Highly Customizable

50+ CSS custom properties available. Easily customizable from CSS or
SCSS. Theme constructor with immediate visual feedback available
(Button on the top left corner).

∈ Completely scoped

Styles are applied under the Stylish UI class names and all classes
and properties are prefixed. You can add Stylish UI on an existent
project with no harm and no side effects on the outer scope.

💎 Decoupled themes

Custom themes are just a set of CSS Custom properties. You can load
them dynamically or scope them to have multiple themes on the same
application - even same page (change this page theme on the bottom
left button).

## Getting Started

Install with NPM (Also available with Yarn)

```
npm i @louisagonch/stylishui
```

Then in your app

```
import '@louisagonch/stylishui'
```

Or download the package and add the css on your document:

```
<link rel="stylesheet" href="https://unpkg.com/@louisagonch/stylishui@1.0.0/dist/index.css">
```

## Colors

### Text-Color

 <table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
                <th>Example</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.color-blue</td>
                <td>color: blue</td>
                <td><p class="color-blue">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-red</td>
                <td>color: red</td>
                <td><p class="color-red">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-yellow</td>
                <td>color: yellow</td>
                <td><p class="color-yellow">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-green</td>
                <td>color: green</td>
                <td><p class="color-green">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-orange</td>
                <td>color: orange</td>
                <td><p class="color-orange">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-purple</td>
                <td>color: purple</td>
                <td><p class="color-purple">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-gray</td>
                <td>color: gray</td>
                <td><p class="color-gray">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-black</td>
                <td>color: black</td>
                <td><p class="color-black">Sample Text</p></td>
              </tr>
              <tr>
                <td>.color-white</td>
                <td>color: white</td>
                <td><p class="color-white">Sample Text</p></td>
              </tr>
              <!-- Add more rows as needed -->
            </tbody>
          </table>

### Background-Color

<table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
                <th>Example</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.background-blue</td>
                <td>background-color: blue</td>
                <td class="background-blue"></td>
              </tr>
              <tr>
                <td>.background-red</td>
                <td>background-color: red</td>
                <td class="background-red"></td>
              </tr>
              <tr>
                <td>.background-yellow</td>
                <td>background-color: yellow</td>
                <td class="background-yellow"></td>
              </tr>
              <tr>
                <td>.background-green</td>
                <td>background-color: green</td>
                <td class="background-green"></td>
              </tr>
              <tr>
                <td>.background-orange</td>
                <td>background-color: orange</td>
                <td class="background-orange"></td>
              </tr>
              <tr>
                <td>.background-purple</td>
                <td>background-color: purple</td>
                <td class="background-purple"></td>
              </tr>
              <tr>
                <td>.background-gray</td>
                <td>background-color: gray</td>
                <td class="background-gray"></td>
              </tr>
              <tr>
                <td>.background-black</td>
                <td>background-color: black</td>
                <td class="background-black"></td>
              </tr>
              <tr>
                <td>.background-white</td>
                <td>background-color: white</td>
                <td class="background-white"></td>
              </tr>
            </tbody>
          </table>

## Spacing

### Margin

 <table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.margin-xs</td>
                <td>margin: 0.25rem</td>
              </tr>
              <tr>
                <td>.margin-sm</td>
                <td>margin: 0.5rem</td>
              </tr>
              <tr>
                <td>.margin-md</td>
                <td>margin: 1rem</td>
              </tr>
              <tr>
                <td>.margin-lg</td>
                <td>margin: 2rem</td>
              </tr>
              <tr>
                <td>.margin-xl</td>
                <td>margin: 4rem</td>
              </tr>
            </tbody>
          </table>

### Padding

<table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.padding-xs</td>
                <td>padding: 0.25rem</td>
              </tr>
              <tr>
                <td>.padding-sm</td>
                <td>padding: 0.5rem</td>
              </tr>
              <tr>
                <td>.padding-md</td>
                <td>padding: 1rem</td>
              </tr>
              <tr>
                <td>.padding-lg</td>
                <td>padding: 2rem</td>
              </tr>
              <tr>
                <td>.padding-xl</td>
                <td>padding: 4rem</td>
              </tr>
            </tbody>
          </table>

## Typography

### Font-size

<table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
                <th>Example</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.font-size-xs</td>
                <td>font-size: 0.75rem</td>
                <td><p class="font-size-xs">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-size-sm</td>
                <td>font-size: 1rem</td>
                <td><p class="font-size-sm">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-size-md</td>
                <td>font-size: 1.25rem</td>
                <td><p class="font-size-md">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-size-lg</td>
                <td>font-size: 1.5rem</td>
                <td><p class="font-size-lg">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-size-xl</td>
                <td>font-size: 2rem</td>
                <td><p class="font-size-xl">Sample Text</p></td>
              </tr>
            </tbody>
          </table>

### Font-Weight

<table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
                <th>Example</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.font-weight-light</td>
                <td>font-weight: 300</td>
                <td><p class="font-weight-light">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-weight-regular</td>
                <td>font-weight: 400</td>
                <td><p class="font-weight-regular">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-weight-medium</td>
                <td>font-weight: 500</td>
                <td><p class="font-weight-medium">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-weight-bold</td>
                <td>font-weight: 700</td>
                <td><p class="font-weight-bold">Sample Text</p></td>
              </tr>
              <tr>
                <td>.font-weight-extra-bold</td>
                <td>font-weight: 800</td>
                <td><p class="font-weight-extra-bold">Sample Text</p></td>
              </tr>
            </tbody>
          </table>

### Font-families

<table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Styling</th>
                <th>Example</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.arial</td>
                <td>font-family: 'Arial', sans-serif;</td>
                <td><p class="arial">Sample Text</p></td>
              </tr>
              <tr>
                <td>.georgia</td>
                <td>font-family: 'Georgia', serif;</td>
                <td><p class="georgia">Sample Text</p></td>
              </tr>
              <tr>
                <td>.helvetica</td>
                <td>font-family: 'Helvetica', sans-serif;</td>
                <td><p class="helvetica">Sample Text</p></td>
              </tr>
              <tr>
                <td>.courier</td>
                <td>font-family: 'Courier New', monospace;</td>
                <td><p class="courier">Sample Text</p></td>
              </tr>
            </tbody>
          </table>

## Buttons

<table>
            <thead>
              <tr>
                <th>Class Name</th>
                <th>Example</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>.button-primary</td>
                <td><button class="button-primary">Sample Text</button></td>
              </tr>
              <tr>
                <td>.button-secondary</td>
                <td><button class="button-secondary">Sample Text</button></td>
              </tr>
              <tr>
                <td>.button-error</td>
                <td><button class="button-error">Sample Text</button></td>
              </tr>
              </tr>
            </tbody>
          </table>

## Container

## Flex and Grid
