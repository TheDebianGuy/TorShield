## TorShield ~ Multiplatform TOR proxy
<img src='https://forthebadge.com/images/badges/open-source.svg' width='200px' height='40'></img>&nbsp;<img src='https://forthebadge.com/images/badges/made-with-c-sharp.svg' width='200px' height='40'></img>
* [Installation](#installation)<br>
* [How does it work](#knowhow)<br>
* [FAQ](#faq)<br>
* [Useful links](#links)<br>
<br>
<b name="installation" font-size='30px'>How to install</b><br>
<a href='https://www.torproject.org/download/'>[1] Download TOR browser</a><br>
<img src='step_one.png'><img src='tor_binary.png'>
<p>[2] Specify the TOR binary path to TorShield</p>
<img src='runtime.png'>
<p>[3] Let your IP address be changed</p>
<img src='duckduckgo.png'>
<br>
<b name="knowhow" font-size='30px'>Info</b><br>
<p>The script basically changes global proxy settings and enviroment variables using system commands and eventually api calls. Theres a known issue that windows socks routing may not work due to unknown reasons, however it may work on your machine. You can check if socks settings work using the command <b>curl ifconfig.me</b> which returns your IP address.</p>
<br>
<b name="faq" font-size='30px'>FAQ</b><br>
<b>Does it protect all apps, not only browser?</b><br>
Yes it does, socks proxy routes all applications traffic<br>
<b>Are there any known issues?</b><br>
Yes, socks proxy may not work on windows for unknown reasons, 
also theres a problem if you use git, you'll have to disable proxy for it after
you stop using TorShield by typing following commands in cmd:
<pre>
git config --global --unset http.proxy 
git config --global --unset https.proxy
</pre>
<b>Are you going to continue developing this project?</b><br>
With new TOR browser updates I may update this script depending on new TOR features<br>
<br>
<b name="links" font-size='30px'>Links</b>
<pre>
<a href='https://tb-manual.torproject.org'>TOR browser manual</a>
<a href='https://github.com/torproject/tor/blob/master/LICENSE'>TOR project license</a>
<a href='https://www.avg.com/en/signal/proxy-server-definition'>How proxy works</a>
</pre>
