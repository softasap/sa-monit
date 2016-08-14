sa-monit
========

[![Build Status](https://travis-ci.org/softasap/sa-monit.svg?branch=master)](https://travis-ci.org/softasap/sa-monit)

Important: for ubuntu 14.04 the latest possible version is 5.14 due to libssl-dev dependency.

```
  roles:
    - {
        role: "sa-monit"
      }
```

Advanced:

```
  roles:
    - {
        role: "sa-monit",
        monit_presets: ["basic", "basic_nginx", "elasticsearch"],
        monit_version: "5.14-2", #  FOR 16.04 "5.19.0-1"
        monit_gui_user: admin,
        monit_gui_password: xeR5hSdSQcCnFVLV8PLy
      }
```
