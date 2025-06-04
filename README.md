# php-trilium-next-api

Simple API to talk to a Trilium Next instance. To generate the $config variable, create a file like the following:
```
trilium_endpoint=https://[your domain]/etapi/
trilium_key=[Your key]

zip=[Desired zip]

log=true
echo=true
```

Have PHP read it with `parse_ini_file()` and pass that function's output to this package.

The `log` and `echo` variables aren't in use right now; I plan to pull in a proper logger.
