# Faded Text
![](https://img.shields.io/npm/dt/faded-text)
![](https://img.shields.io/github/package-json/keywords/knouy/faded-text)
![](https://img.shields.io/bundlephobia/min/faded-text)
![](https://img.shields.io/bundlephobia/minzip/faded-text)
![](https://img.shields.io/npm/v/faded-text)
![](https://img.shields.io/npm/collaborators/faded-text)
![](https://img.shields.io/github/package-json/v/knouy/faded-text)
> Letter-by-letter and word-by-word text fade animation.
## Table of Contents
* [Requirement](#requirement)
* [Installation](#installation)
  * [CDN](#cdn)
    * [jsDelivr](#jsdelivr)
  * [Package manager](#package-manager)
    * [npm](#npm)
    * [Yarn](#yarn)
* [Usage](#usage)
  * [Documentation](#documentation)
  * [Example](#example)
    * [HTML](#html)
    * [JS](#js)
    * [Rendering](#rendering)
    * [Demo](#demo)
* [Author](#author)
## Requirement
* [Node.js](https://nodejs.org/) (npm)
## Installation
### CDN
#### jsDelivr
```bash
https://cdn.jsdelivr.net/npm/faded-text@0.0.13/dist/faded-text.min.js
```
### Package manager
#### npm
```bash
npm i faded-text
```
#### Yarn
```bash
yarn add faded-text
```
## Usage
### Documentation
<table>
    <thead>
        <tr>
            <th>Function</th>
            <th>Description</th>
            <th colspan="3">Arguments</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>.charFadeIn()</b></td>
            <td>Display the matched elements by fading them to opaque letter-by-character.</td>
            <td rowspan="4">
                <b>textDuration</b><br>
                (default: 1000)<br>
                Type: Integer<br>
                <br>
                An integer determining the number of milliseconds the total animation will run.
            </td>
            <td rowspan="2">
                <b>charDuration</b><br>
                (default: 1000)<br>
                Type: Integer<br>
                <br>
                An integer determining the number of milliseconds the character animation will run.
            </td>
            <td rowspan="4">
                <b>delay</b><br>
                (default: 0)<br>
                Type: Integer<br>
                <br>
                An integer indicating the number of milliseconds to delay execution of the animation.
            </td>
        </tr>
        <tr>
            <td><b>.charFadeOut()</b></td>
            <td>Hide the matched elements by fading them to transparent letter-by-letter.</td>
        </tr>
        <tr>
            <td><b>.wordFadeIn()</b></td>
            <td>Display the matched elements by fading them to opaque word-by-word.</td>
            <td rowspan="2">
                <b>wordDuration</b><br>
                (default: 1000)<br>
                Type: Integer<br>
                <br>
                An integer determining the number of milliseconds the word animation will run.
            </td>
        </tr>
        <tr>
            <td><b>.wordFadeOut()</b></td>
            <td>Hide the matched elements by fading them to transparent word-by-word.</td>
        </tr>
    </tbody>
</table>

### Example
#### HTML
```html
<div id="idElement">Hello world</div>
```
#### JS
```js
import FadedText from 'faded-text';

const FADED_TEXT = new FadedText('idElement');

FADED_TEXT.charFadeIn();
```
#### Rendering
![Hello world](https://raw.githubusercontent.com/knouy/faded-text/master/hello-world.gif)
#### Demo
https://knouy.github.io/faded-text
## Author
### [Tanguy Sanquirgo](https://github.com/knouy)
