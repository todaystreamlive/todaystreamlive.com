<!DOCTYPE html>
<html>

<head>
  <script src="https://cdn.jsdelivr.net/npm/cdnbye@latest"></script>
  <script src="https://ipl-2023-schedule.pages.dev/playerjs.js" type="text/javascript"></script>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
  
  <div id="player"></div>
  <div id="player"></div>
  <script src="https://cdn.jsdelivr.net/npm/cdnbye@latest"></script>
  
  <script>
 var urlParams = new URLSearchParams(window.location.search);
      var dtvhindi=urlParams.get('url'); 
    var player = new Playerjs({
        id:"player",
        file: dtvhindi,
        hlsconfig: {
            p2pConfig: {
                live: true,        // set to false in VOD mode
                // token: YOUR_TOKEN
            }
        }
    });
</script>

</body>
</html>

<!-- BEGIN: Powered by Supercounters.com -->
<center><script type="text/javascript" src="//widget.supercounters.com/ssl/online_i.js"></script><script type="text/javascript">sc_online_i(1703490,"ffffff","e61c1c");</script><br><noscript><a href="https://www.supercounters.com/">free online counter</a></noscript>
</center>
<!-- END: Powered by Supercounters.com -->
