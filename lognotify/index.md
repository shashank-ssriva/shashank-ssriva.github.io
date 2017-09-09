<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-93972091-1', 'auto');
  ga('send', 'pageview');

</script>
## [lognotify : - My first ever Python project](https://github.com/shashank-ssriva/lognotify)

``lognotify`` is a simple utility that displays a pop-up notification showing me the exact error message in real-time while I am working on my PHP web-app. This utility is very simple, small & highly customisable. You can customise it to tailor to your specific needs. For example, you can customise it to monitor your system logs, Apache logs, MySQL logs & potentially any log-file.

```shell
root@shashank-dbserver /h/s/lognotify# lognotify
No log-file specified. Kindly specify a valid log-file for monitoring. Exiting now...
```
```bash
root@shashank-dbserver /h/s/lognotify# lognotify /var/log/apache2/other_vhosts_access.log2
Log-file you specified doesn't seem to be present. Please specify a valid log file.
```
```bash
root@shashank-dbserver /h/s/lognotify# lognotify /var/log/apache2/other_vhosts_access.log
192.168.0.51:80 127.0.0.1 - - [08/Sep/2017:15:00:51 +0200] "GET /jsdate/jsDatePick.min.1.3.js HTTP/1.1" 404 517 "http://localhost/CabBIlls/feedData.php" "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/60.0.3112.113 Safari/537.36"
```

See my [GitHub Repository](https://github.com/shashank-ssriva/lognotify) for more information.

## Screenshot

Below is the pop-up notification I saw because of a resource being not available(404) :

<img src="https://github.com/shashank-ssriva/lognotify/blob/master/lognoify_in_action.png" height="350" width="250">

## YouTube Demo Video

Click below thumbnail to watch the demo video  

<a href="http://www.youtube.com/watch?feature=player_embedded&v=K8I_xFdfYFs
" target="_blank"><img src="http://img.youtube.com/vi/K8I_xFdfYFs/0.jpg">
