## Cargo Bay _v0.8.8_

[![Build Status](https://travis-ci.org/Kunstmaan/cargobay.svg)](https://travis-ci.org/Kunstmaan/cargobay)

Cargo Bay is a utility library with some useful and commonly used components and snippets.


### Includes
- [Cookie-consent bar](src/cbCookieConsent/)
- [Float label form](src/cbFloatLabelForm/)
- [Full image background fallback](src/cbFullImgBg/)
- [Has space](src/cbHasSpace/)
- [Responsive audioplayer](src/cbAudioplayer/)
- [Scroll-to](src/cbScrollTo/)
- [Scroll-to-top](src/cbScrollToTop/)
- [Sidebar Toggle](src/cbSidebarToggle/)
- [Tabs](src/cbTabs/)
- [Toggle](src/cbToggle/)
- [Videolink](src/cbVideolink/)

### Installing using Bower
```
bower install cargobay
```


### Contribution

##### Git Flow
Cargo Bay works with [git-flow](https://github.com/nvie/gitflow).

For a contribution to Cargo Bay, you need to follow the [following workflow](https://github.com/nvie/gitflow#initialization) with the addition of a pull-request.

Example for adding a feature:
- Start from develop (make sure to pull first)
- `git flow feature start -your feature name-`
- `git flow feature publish -your feature name-`
- start making your changes (commit and push regularly)
- when done, make a pull-request from your feature branch to develop
- after the pull-request is accepted, do `git flow feature finish -your feature name-`


### License
Cargo Bay is licensed under the [MIT license](http://opensource.org/licenses/MIT).
