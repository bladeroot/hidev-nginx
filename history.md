hiqdev/hidev-nginx commits history
----------------------------------

## [0.4.4] - 2016-11-15

- Fixed `dump` action
    - [249e5d4] 2016-11-15 fixed `dump` action: used perform for before/after [sol@hiqdev.com]
- Added vhost response `timeout` option
    - [c29edec] 2016-11-15 Added vhost response timeout option [d.naumenko.a@gmail.com]

## [0.4.3] - 2016-10-21

- Fixed `setLocalIps()`
    - [3ab36c2] 2016-10-21 fixed IPs doubling [sol@hiqdev.com]
    - [3f3d62b] 2016-10-12 fixed setLocalIps() [sol@hiqdev.com]
    - [4ef1798] 2016-09-02 added ip read-only property to VhostController [sol@hiqdev.com]

## [0.4.2] - 2016-09-02

- Added multiple ips and local ips
    - [d0c7ba5] 2016-09-02 used `chkipper` [sol@hiqdev.com]
    - [3b8fcdc] 2016-07-29 added multiple ips and local ips [sol@hiqdev.com]
    - [00bc8a8] 2016-05-30 fixed tests [sol@hiqdev.com]

## [0.4.1] - 2016-05-30

- Fixed X-Real-IP when ssl is disabled
    - [cf7fa7e] 2016-05-30 csfixed [sol@hiqdev.com]
    - [7403c56] 2016-05-30 fixed x-real-ip when ssh is disabled [sol@hiqdev.com]
    - [297ec05] 2016-05-24 used `hiqdev/hidev-hiqdev` [sol@hiqdev.com]

## [0.4.0] - 2016-05-24

- Changed: redone to `composer-config-plugin`
    - [986e83e] 2016-05-24 fixed tests [sol@hiqdev.com]
    - [c205e6f] 2016-05-24 redone to `composer-config-plugin` [sol@hiqdev.com]

## [0.0.2] - 2016-05-13

- Fixed tests
    - [1b237cd] 2016-05-13 fixed functional tests with assertFiles [sol@hiqdev.com]

## [0.0.1] - 2016-05-13

- Fixed dependencies constraints
    - [8cbb8d7] 2016-05-13 fixed dependencies constraints [sol@hiqdev.com]
    - [c880ceb] 2016-05-13 fixing dependencies constraints [sol@hiqdev.com]
- Added Let's Encrypt integration
    - [230e3de] 2016-05-12 + `/tmp/php-fpm.sock` fpm socket variant [sol@hiqdev.com]
    - [8c9b014] 2016-05-12 fixed test case according to changes [sol@hiqdev.com]
    - [5d2ae9d] 2016-05-12 renamed `do` -> `make` [sol@hiqdev.com]
    - [4d971e6] 2016-05-12 added `VhostController::getDomains` [sol@hiqdev.com]
    - [1a2c6c8] 2016-05-12 + allow well-known for letsencrypt [sol@hiqdev.com]
    - [c271ba9] 2016-05-12 csfixed [sol@hiqdev.com]
    - [215b457] 2016-05-12 enabled before and after in nginx goal [sol@hiqdev.com]
    - [9ee4d6e] 2016-05-12 added `aliases` [sol@hiqdev.com]
    - [bfcfded] 2016-05-12 fixed pathes building [sol@hiqdev.com]
    - [a7d46eb] 2016-05-11 used asset-packagist.org and hidev-config moved to src/config [sol@hiqdev.com]
    - [b7d7eb1] 2016-05-11 fixed functional test [sol@hiqdev.com]
    - [3c808f8] 2016-05-11 + LetsEncrypt integration [sol@hiqdev.com]
    - [d981b7d] 2016-05-08 + nginx deploy and restart actions [sol@hiqdev.com]
- Added basics
    - [ea1f5b0] 2016-05-07 added default vhost with same name [sol@hiqdev.com]
    - [56019ba] 2016-05-06 csfixed [sol@hiqdev.com]
    - [ad8e303] 2016-05-06 fixed tests [sol@hiqdev.com]
    - [e592bcd] 2016-05-06 added functional tests [sol@hiqdev.com]
    - [eeffa35] 2016-05-06 inited [sol@hiqdev.com]

## [Development started] - 2016-05-06

[cf7fa7e]: https://github.com/hiqdev/hidev-nginx/commit/cf7fa7e
[7403c56]: https://github.com/hiqdev/hidev-nginx/commit/7403c56
[297ec05]: https://github.com/hiqdev/hidev-nginx/commit/297ec05
[986e83e]: https://github.com/hiqdev/hidev-nginx/commit/986e83e
[c205e6f]: https://github.com/hiqdev/hidev-nginx/commit/c205e6f
[1b237cd]: https://github.com/hiqdev/hidev-nginx/commit/1b237cd
[8cbb8d7]: https://github.com/hiqdev/hidev-nginx/commit/8cbb8d7
[c880ceb]: https://github.com/hiqdev/hidev-nginx/commit/c880ceb
[230e3de]: https://github.com/hiqdev/hidev-nginx/commit/230e3de
[8c9b014]: https://github.com/hiqdev/hidev-nginx/commit/8c9b014
[5d2ae9d]: https://github.com/hiqdev/hidev-nginx/commit/5d2ae9d
[4d971e6]: https://github.com/hiqdev/hidev-nginx/commit/4d971e6
[1a2c6c8]: https://github.com/hiqdev/hidev-nginx/commit/1a2c6c8
[c271ba9]: https://github.com/hiqdev/hidev-nginx/commit/c271ba9
[215b457]: https://github.com/hiqdev/hidev-nginx/commit/215b457
[9ee4d6e]: https://github.com/hiqdev/hidev-nginx/commit/9ee4d6e
[bfcfded]: https://github.com/hiqdev/hidev-nginx/commit/bfcfded
[a7d46eb]: https://github.com/hiqdev/hidev-nginx/commit/a7d46eb
[b7d7eb1]: https://github.com/hiqdev/hidev-nginx/commit/b7d7eb1
[3c808f8]: https://github.com/hiqdev/hidev-nginx/commit/3c808f8
[d981b7d]: https://github.com/hiqdev/hidev-nginx/commit/d981b7d
[ea1f5b0]: https://github.com/hiqdev/hidev-nginx/commit/ea1f5b0
[56019ba]: https://github.com/hiqdev/hidev-nginx/commit/56019ba
[ad8e303]: https://github.com/hiqdev/hidev-nginx/commit/ad8e303
[e592bcd]: https://github.com/hiqdev/hidev-nginx/commit/e592bcd
[eeffa35]: https://github.com/hiqdev/hidev-nginx/commit/eeffa35
[3b8fcdc]: https://github.com/hiqdev/hidev-nginx/commit/3b8fcdc
[00bc8a8]: https://github.com/hiqdev/hidev-nginx/commit/00bc8a8
[d0c7ba5]: https://github.com/hiqdev/hidev-nginx/commit/d0c7ba5
[3ab36c2]: https://github.com/hiqdev/hidev-nginx/commit/3ab36c2
[3f3d62b]: https://github.com/hiqdev/hidev-nginx/commit/3f3d62b
[4ef1798]: https://github.com/hiqdev/hidev-nginx/commit/4ef1798
[249e5d4]: https://github.com/hiqdev/hidev-nginx/commit/249e5d4
[c29edec]: https://github.com/hiqdev/hidev-nginx/commit/c29edec
