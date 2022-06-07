Lighthouse
=========

Role for installation Lighthouse.

Requirements
------------

No

Role Variables
--------------


|Variables|Default| Description |
|-|:-:|-:|
| lighthouse_distr_local |    "/tmp/lighthouse.zip"   | Путь сохранения загружаемого файла |
| lighthouse_unarch_dest | "/usr/share" |Путь распаковки lighthouse|


------------

No

Example Playbook
----------------

```yaml
  - name: Install Lighthouse
    hosts: lighthouses
    vars:
      lighthouse_unarch_dest: "/var/www/html"
```

License
---

BSD

Author Information
------------------

https://github.com/Nb3l77eo
