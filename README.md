# primerintento
# /etc/nsswitch.conf
#
#    This file is read once by the first process in a Cygwin process tree.
#    To pick up changes, restart all Cygwin processes.  For a description
#    see https://cygwin.com/cygwin-ug-net/ntsec.html#ntsec-mapping-nsswitch
#
# Defaults:
# passwd:   files db
# group:    files db
# db_enum:  cache builtin
# db_home:  /home/%U
# db_shell: /bin/bash
# db_gecos: <empty>
db_home: /%H
# Estoy personalizando la variable de entorno de la home de cygwin para que corresponda con el usuario de Windows

```
