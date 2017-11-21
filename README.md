sa-monit
========

[![Build Status](https://travis-ci.org/softasap/sa-monit.svg?branch=master)](https://travis-ci.org/softasap/sa-monit)
[![License: MIT](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)

Important: for ubuntu 14.04 the latest possible version is 5.14 due to libssl-dev dependency.

```YAML
  roles:
    - {
        role: "sa-monit"
      }
```

Advanced:

```YAML
  roles:
    - {
        role: "sa-monit",
        monit_presets: ["basic", "basic_nginx", "elasticsearch"],
        monit_version: "5.14-2", #  FOR 16.04 "5.19.0-1"
        monit_gui_user: admin,
        monit_gui_password: xeR5hSdSQcCnFVLV8PLy
      }
```

Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-monit  role using the command


`
   ansible-galaxy install softasap.sa-monit
`

the role will be available in the folder library/sa-dehydrated

Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-monit"
       }

```




Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

