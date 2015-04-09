# varnishncsa-monitor

VarnishNCSA Monitor - Bash wrapper script to provide pretty colorized output of request/responses information

### Usage
```
varnishncsa_monitor [-l hostname] [-n instance] [-t] [-e] -[c] [-m] [-j] [-h]
```

#### Arguments
  `-l`   host to monitor (default is localhost), possible to specify remote machine (but script should be deployed manually and available on $PATH for remote user)

  `-n`   specify Varnish instance - name or absolute path where daemon keeps temporary files and persistent state

  `-t`   trim static files from output
 
  `-e`   display only 50x errors

  `-c`   display only 40x errors

  `-m`   display only 404 errors

  `-j`   disable colorized output

  `-h`   print program usage and exit

### LICENSE

This work is provided under the MIT License
