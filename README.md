## TorShield ~ Menu
<img src='https://forthebadge.com/images/badges/open-source.svg' width='200px' height='20'></img>&nbsp;<img src='https://forthebadge.com/images/badges/works-on-my-machine.svg' width='200px' height='50'></img>
* [Installation](#installation)<br>
* [How does it work](#knowhow)<br>
* [Useful links](#links)<br>
<br>
<b name="installation">How to install</b><br>
<a href='https://www.torproject.org/download/'>[1] Download TOR browser</a><br>
<img src='step_one.png'><img src='tor_binary.png'>
<p>[2] Specify the TOR binary path to TorShield</p>
<img src='runtime.png'>
<p>[3] Let your IP address be changed</p>
<img src='duckduckgo.png'>
<br>
<p name="knowhow">The script basically changes global proxy settings and enviroment variables using system commands and eventually api calls. Theres a known issue that windows socks routing may not work due to unknown reasons, however it may work on your machine. You can check if socks settings work using the command `curl ifconfig.me` which returns your IP address.</p>
<br>
<pre name="links">
<a href='https://tb-manual.torproject.org'>TOR browser manual</a>
<a href='https://github.com/torproject/tor/blob/master/LICENSE'>TOR project license</a>
<a href='https://www.avg.com/en/signal/proxy-server-definition'>How proxy works</a>
</pre>
