
A docset file for [Monome's Teletype](https://monome.org/docs/teletype/) module. Draws directly from the official [Monome docs](https://github.com/monome/docs) but repackages them for use with applications such as [Dash](https://kapeli.com/dash).

## Build

````
$ brew install dashing
$ dashing build mydocs
````

## Credits

The Monome docs are licensed with [Creative Commons 4.0](https://creativecommons.org/licenses/by/4.0/) and this repository (minimally) adapts and redistributes those works.

The only change made to the official Teletype docs source file is to hide the menu. However, the presentation of that work as a 'docset' is arguably an alteration of the work.

Thanks for technosophos, for the [dashing library](hhttps://github.com/technosophos/dashing) which has made this whole process easy.

## TODO

- Content vanishes when window is very small
- Add screenshots/screencast
- Remove CHANGELOG/Quickstart; e.g. focus just on OPS/MODs?