# varnishncsa-monitor

VarnishNCSA Monitor - Bash wrapper script to provide pretty colorized output of request/responses information

Supports Varnish (varnishncsa utility) of 3.x and 4.x versions

### Usage
```
varnishncsa_monitor [options]
```

#### Options
  `-l`   host to monitor (default is localhost), possible to specify remote machine (but script should be deployed manually and available on $PATH for remote user)

  `-n`   specify Varnish instance - name or absolute path where daemon keeps temporary files and persistent state
  
  `-r`   filter output by response handler (hit / miss/ pass / pipe)

  `-5`   display responses of 50x http codes

  `-4`   display responses of 40x http codes
  
  `-3`   display responses of 30x http codes

  `-2`   display responses of 20x http codes 

  `-m`   display responses of 404 http codes only

  `-t`   trim static files from output

  `-j`   disable colorized output

  `-h`   print program usage and exit

### Screenshot

![VarnishNCSA Monitor](/ScreenShot.png?raw=true "VarnishNCSA Monitor")

### LICENSE

This work is provided under the MIT License
