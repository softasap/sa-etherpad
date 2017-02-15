sa-etherpad
===========

[![Build Status](https://travis-ci.org/softasap/sa-etherpad.svg?branch=master)](https://travis-ci.org/softasap/sa-etherpad)


Example of usage (all parameters are optional)

Simple


```YAML
  roles:
    - {
        role: "sa-etherpad"
      }
```

Advanced:

```YAML

  roles:
    - {
        role: "sa-etherpad",

        deploy_user: "etherpad",

        options_create_etherpad_user: true,
        option_nodejs_install_with_nvm: true,

        etherpad_install_dir: /opt/etherpad,

        nvm_version: 0.31.1,
        nodejs_version: "6.9.2",
        option_nodejs_link_globally: false,
        option_integrate_w_bash: false,
        option_integrate_w_zsh: false
      }

```      


Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
