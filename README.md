heroku-toolbelt Cookbook
========================
Install heroku toolbelt for ubunto vagrant box

Requirements
------------
wget

Attributes
----------

Usage
-----
#### heroku-toolbelt::default

Just include `heroku-toolbelt` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[heroku-toolbelt]"
  ]
}
```

License and Authors
-------------------
Licence: Apache v2
Authors: Ian Kenney
