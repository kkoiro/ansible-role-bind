ansible-role-bind
===

An ansible role for setting up BIND

## How to use
1. prepare configration & zone files

You need to prepare configration & zone files in your playbook. Put then into expected directories which as default are **files/bind/{{ hostname }}/** and **files/bind/{{ hostname }}/master/**.

