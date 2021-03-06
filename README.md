<img src="http://i.imgur.com/rVCVUSU.png" align="right">

# aaOceanC4D

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

aaOcean Shader and Deformer by [Amaan Akram][0], ported to Cinema 4D by
[Niklas Rosenstein][2].

![](screenshot.png)

## Examples

*by Serge Mustu*

<table>
  <tr>
    <td><img src="example/render-01.jpg"></td>
    <td><img src="example/render-02.jpg"></td>
  </tr>
  <tr>
    <td><img src="example/render-03.jpg"></td>
    <td><img src="example/render-04.jpg"></td>
  </tr>
</table>

## Installation

* Download a build from the [Releases] page that matches your OS
  and Cinema 4D version
* Unpack the downloaded ZIP archive into your Cinema 4D plugins directory

## Build Instructions

* Install [Craftr]
* Clone the repository in the Cinema 4D application plugins directory
* On OSX: `$ brew install libomp`
* `$ git submodules update --init`
* `$ craftr -cb --variant=release`

## Todolist/Ideas

* [ ] Shader/Deformer with on-demand wave sampling (no texture precomputation)

## Honorable Mentions

* Amaan Akram for the [aaOcean Suite] and its source code
* Sponsor for initial port [Partner Ship Design GmbH][1]

[Releases]: https://github.com/NiklasRosenstein/c4d-aaOcean/releases
[Craftr]: https://craftr.net
[aaOcean Suite]: http://www.amaanakram.com/plugins-shaders/aaocean-suite/
[0]: http://www.amaanakram.com/
[1]: http://www.psd.de/
[2]: http://niklasrosenstein.com/

## Changelog

### v1.0.1

- R20 Update
