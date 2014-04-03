# power-assert-karma-seed

Example project of [power-assert](https://github.com/twada/power-assert "power-assert") + [Karma](https://github.com/karma-runner/karma "Karma") + [browserify](https://github.com/substack/node-browserify "browserify").

Testing for Browser with [power-assert](https://github.com/twada/power-assert "power-assert").

![gif](http://i.gyazo.com/4daa1c15931e4de407a382c8fd895339.gif)

## Installation

```
npm install
npm install -g karma-cli
```

## Usage

### Browser Testing

``` sh
npm test
# or
karma start # and capture browser
```

### Node.js Testing

``` sh
mocha --require intelli-espower-loader
```

## Integrate WebStorm

Run Debug mode(main use case is **breakpoint**)

1. `karma start`
2. Open `http://localhost:9876/debug.html` form WebStorm.
3. We Can Set Breakpoint!!

![webstorm config](http://monosnap.com/image/HBgstQMP9xhAS72bBEAbU7s4T9nCd4.png)

More Detail on

* [Running JavaScript tests with Karma - WebStorm - Confluence](http://confluence.jetbrains.com/display/WI/Running+JavaScript+tests+with+Karma "Running JavaScript tests with Karma - WebStorm - Confluence")
* [Karma ユニットテストをWebStormでデバッグする - Kazzzの日記](http://d.hatena.ne.jp/Kazzz/20130524/p1 "Karma ユニットテストをWebStormでデバッグする - Kazzzの日記")

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT
