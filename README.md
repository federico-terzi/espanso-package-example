# espanso-utility

[#espanso-utility](https://github.com/pietrzak-pro/espanso-utility) loves [#programmers](https://en.wikipedia.org/wiki/Programmer)

Utility package for [#espanso](https://espanso.org/) - Cross-platform Text Expander written in [#rust](https://www.rust-lang.org/). For more information, read the [#documentation](https://espanso.org/docs/).

## Instalation

1. Install [#espanso](https://espanso.org/) as documented [here](https://espanso.org/install/).

2. Install [#espanso-utility](https://github.com/pietrzak-pro/espanso-utility) from a repository with following command:

```
espanso install espanso-utility https://github.com/pietrzak-pro/espanso-utility --external
```

## Triggers

| Trigger | Replace | Version | Status |
| --- | --- | --- | --- |
| :#hw | [#espanso-utility](https://github.com/pietrzak-pro/espanso-utility) loves [#programmers](https://en.wikipedia.org/wiki/Programmer) | >= 0.1.0 | done |

## Progress

- [ ] __#version/0/0/1__
    - [x] Fork [#espanso](https://espanso.org/) repository
    - [x] Prepare initial configuration in [Readme.md](espanso-utility/README.md)
    - [x] Configure package structure in [package.yml](0.1.0/package.yml)
    - [x] Prepare gitflow
    - [x] Add `:#hw` test trigger
    - [x] Add `:#espanso and :#espanso/utility` triggers
    - [ ] Add `:#date` trigger
    - [ ] Add `:#datetime` trigger
    - [ ] Add `:#updated/documentation` trigger
    - [ ] Update documentation for new triggers

## FAQ

### How do I escape trigger?

The proposed way to do it is by adding backslash (`\`) after colon (`:`) in trigger body. It can be deleted afterwards, eg: `:\datetime`.

## License
[#espanso](https://espanso.org/) was created by [#people/federico_terzi](http://federicoterzi.com/) and is licensed under the [#license/gpl/3.0](https://github.com/federico-terzi/espanso/blob/master/LICENSE). The same license applies to [#espanso-utility](https://github.com/pietrzak-pro/espanso-utility) package.
