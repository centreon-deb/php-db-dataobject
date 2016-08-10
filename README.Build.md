Build instructions for the impatient


```bash
curl https://raw.githubusercontent.com/centreon-deb/php-db-dataobject/debian/bootstrap | sh
cd php-db-dataobject && git deb-pkg -C -U -u 1.11.5 -d origin/debian build
```

Further instruction in the [README.Build.md](README.Build.md) file.
