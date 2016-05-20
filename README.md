ansible-role-bind
===

An ansible role for setting up BIND

## How to use

1. prepare configration & zone files

You need to prepare configration & zone files in your playbook. Put them into right directories which are defined in variables  
If you would like to change the paths, overwrite specific variables

## Variables

| parameter | defaults | choices | comments |
|:---|:---|:---|:---|
| bind_conf_src_path | files/bind/named.conf |  | The path of the bind configuration file|
| bind_zone_src_path | files/bind/named.conf |  | The path of the zone files|
