# Tech
!DOCTYPE html>
<html manifest="manifest.appcache">
<!--
    Exchange the line above for this to enable offline support
    <html manifest="manifest.appcache">

    Please make your homework before doing this:
        http://www.alistapart.com/articles/application-cache-is-a-douchebag/
        http://appcachefacts.info
 -->
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">

    <title>Settings</title>
    <base target="_blank">
    <style>
    @import url("https://fonts.googleapis.com/css?family=Open+Sans");

    *,
    *::before,
    *::after {
        box-sizing: border-box;
    }

    html,
    body {
        width: 100%;
        margin: 0;
        padding: 0;
        position: relative;
        -webkit-margin-start: 0;
        -webkit-margin-end: 0;
    }

    body {
        background: #000000;
        font-family: 'Open Sans', sans-serif;
        color: #ffffff;
    }

    A {
        text-decoration: none;
    }

    /* Set a style for all buttons */

    button {
        background-color: #ffffff;
        color: black;
        padding: 14px 20px;
        margin: 8px 0;
        border: none;
        cursor: pointer;

        border-radius: 15px;
        width: 100%;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }

    button:hover {
        opacity: 0.8;
    }
</style>
</head>

<body>




    <div id="main">

     
       <button id="hotspot">Internet Sharing</button>

     <button id="dev">Developer Options</button>
             <button id="acd">Accessibility</button>

        <button id="record">Take picture</button>

        <button id="dial">Dial number</button>

        <button id="send-sms">Send SMS</button>

        <button id="add-contact">Add contact</button>

       

     


        <button id="open-settings">Open Settings</button>


       

       
        <button id="geolocation">Get location</button>
        <div id="geolocation-display">Geolocation coords should show up here</div>

    </div>
       <script>

      document.getElementById('hotspot').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "hotspot"

            }

          })

         

        }

          }, false)

        var lock = navigator.mozSettings.createLock();

	lock.set({'tethering.wifi.enabled': true});

lock.set({'tethering.wifi.ip': "192.168.1.1"});

lock.set({'tethering.wifi.prefix': "24"});

lock.set({'tethering.wifi.dhcpserver.startip': "192.168.1.10"});

lock.set({'tethering.wifi.dhcpserver.endip': "192.168.1.30"});

lock.set({'tethering.wifi.ssid': " Hotspot"});

lock.set({'tethering.wifi.security.type': "wpa-psk"});

lock.set({'tethering.wifi.security.password': "89281838"});

        

    

    </script>
     <script>

      document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>

 document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
    document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
  document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
 document.getElementById('dev').addEventListener('click', function (e) {
            if (window.MozActivity) {
                var act = new MozActivity({
                    name: "configure",
                    data: {
                        target: "device",
                        section: "developer"
                    }
                })
            }
            else {
                window.alert('This Page Is Work only for educational purposes')
            }
        }, false)
    </script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>
document.getElementById('acd').addEventListener('click', function(e) {

        if(window.MozActivity) {

          var act = new MozActivity({

            name: "configure",

            data: {

              target: "device",

              section: "accessibility"

            }

          })

        }

        else  }

        }

      }, false)

    </script>
    <script>

    <script type="text/javascript" src="js/base.js"></script>
    <script type="text/javascript" src="js/webapp.js"></script>
    <script type="text/javascript" src="js/offline.js"></script>

    <!--
        Loosely based on fxosstub: https://github.com/Jaxo/fxosstub
    -->

</body>
</html>
