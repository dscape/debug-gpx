# Debug NPM

A simple tool to cut segments so you can easily deb ug your GPX files using common editors such as [wtracks], [gpxsee], or [run particles][run].

## Installation

```
npm install -g debug-npm
```

## Usage

The program slices the GPX file while you are debugging it. You can then refresh in your editor. Back on the terminal hit `control+c` to restore the file to the original state.

```
debug-gpx --file my_run.gpx --from 100 --to 200
```

Or in "interactive" mode

```
debug-gpx --file my_run.gpx
```

[wtracks]: https://opoto.github.io/wtracks/
[gpxsee]: https://www.gpxsee.org
[run]: http://renderfast.com/RunParticles/