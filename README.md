racktables-quickstart
=========
Install 0.20.7 racktables on openshit
Howto
=========
`rhc app create racktables php-5.3 mysql-5.1  --from-code https://github.com/sheepkiller/racktables-quickstart.git`
Log as admin/admin

Customize
=========
1. fork this repo
2. Edit `.openshift/share/secret.php.tmpl`
3. commit
4. `rhc app create racktables php-5.3 mysql-5.1  --from-code <your fork>`

Hey, this repo is out of date !
=========
1. fork this repo
2. copy source tarball content
3. clone https://github.com/RackTables/racktables-contribs
4. copy to racktables-contrib/demo.racktables.org/init-full-<version>.sql to .openshift/share/init.sql

