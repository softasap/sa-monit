sa-monit
========

[![Build Status](https://travis-ci.org/softasap/sa-monit.svg?branch=master)](https://travis-ci.org/softasap/sa-monit)

Important: for ubuntu 14.04 the latest possible version is 5.14 due to libssl-dev dependency.
So only "default" version supported

For more modern systems you can choose latest stable distribution, like  `5.25.2-1` at the time of release.
If "default" is too old for you.

```yaml
  roles:
    - {
        role: "sa-monit"
      }
```

Advanced:

```yaml
  roles:
    - {
        role: "sa-monit",
        monit_presets: ["basic", "basic_nginx", "elasticsearch"],
        monit_version: "5.14-2", #  FOR 16.04 "5.19.0-1"
        monit_gui_user: admin,
        monit_gui_password: xeR5hSdSQcCnFVLV8PLy
      }
```

Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html


