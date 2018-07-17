- copy entire repo into TC_ROOT\aws2\stage\src folder

- add blueTheme40 to your custom kit or the kit inside TC_ROOT\aws2\stage\solution\kit.json under modules like so:

          "modules": [
                    "tc-aw-solution",
                    "blueTheme40"
                    ],

- Open Tc-dos prompt

- Go to TC_ROOT\aws2\stage directory
    initenv   ("initenv iis" if iis is used)
    gwtcompile   ("gwtcompile iis" if iis is used)
 

- Copy awc.war from output into your webserver or iis if needed
- Login in and enjoy new Theme (plmTheme)
