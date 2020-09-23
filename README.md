<div align="center">

## Open Source Proxy Server \(vb6\),nt\-service,http\(s\),ftp,telnet,ssl,ras  \(cinaproxy\) w9x/me/nt/2k/xp

<img src="PIC2002881111322134.jpg">
</div>

### Description

Complete proxy solution(source,docs) 1 connection to the internet and even more pc's in your lan that want to connect,too?: http-proxy, web-server (php-support,XML-support,dir),socks4/5,smtp relay, telnet-port-mapping, internet-mail support,remote admin via Crypto API, atomic syncer (uses settings from system), dyndns updater and many many more (full details see below) techniques used: winsock.ocx, crypto api, msxml, Java, rasapi,

ip-blocking,iphelper-api, own secure-socket layer, user-behavior, use as local adblock proxy, auto disconnect auto reconnect, flatrate support, RAS-Manager (also usable without proxy), http-logging and other protocols, fully customizable (YOU can modify the source), web-server for intranet (also usable for anti-virus pattern-files that has to be distributed via lan), collect your anti-virus-pattern-files on connect via ras, set your dynamic dy..dns ip,set online state....

more stable, more config, less errors

the cina proxy is a multifunctional proxy project completly written in vb6. project life time more than 2 years. good combination of techniques and algorithms shown in serveral other projects that have same aims. the project is just a tutorial how to design a smart proxy for your lan. it is not a solution, but it can solve serveral problems that might not sell your firewall. This project is just in alpha release phase, but if you are interested in proxy programming send your feedback and vote.Please vote and give feedback if this is the tool youa re looking for. it is not NAT or a firewall, but can be used beside ones.

-->service under 9x/Me/Nt/XP/2k

see Documentation at website...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[preneco](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/preneco.md)
**Level**          |Advanced
**User Rating**    |4.9 (89 globes from 18 users)
**Compatibility**  |VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/preneco-open-source-proxy-server-vb6-nt-service-http-s-ftp-telnet-ssl-ras-cinaproxy-w9x-me__1-37736/archive/master.zip)





### Source Code

<html><body>
<p><a href="http://prdownloads.sourceforge.net/cinaproxy/cinaproxy_win32_src.zip?download"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif"><b><img src="http://www.pscode.com/vb/images/winzipicon_medium.gif" width="43" height="42" border="0"></b></font></a><b><font size="-1" face="Verdana, Arial, Helvetica, sans-serif"><a href="http://prdownloads.sourceforge.net/cinaproxy/cinaproxy_win32_src.zip?download" target="_blank">Download new
 Release Stable V05</a></font></b></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">Sorry I couldn't
 upload the source up to Pscode.com<br>
 so if you want the documentation please visit: <a href='http://www.cinaproxy.de.vu' target="_blank"><br>
 <b>Project Home Page</b></a> or <a href='http://sourceforge.net/project/showfiles.php?group_id=45079' target="_blank"><b>Source
 Code and Installer</b></a></font> </p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><b>Using the Cina
 Proxy Server Project</b></font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">What can you do
 with the code?<br>
 </font></p>
<ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">it's simple,
 this project and it's subprojects are examples what<br>
 you can do with the cXPLib Library </font>
 <ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">a simple
 proxy server (Cina) </font>
 <ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">http,https
 (SSL,TSL),ftp </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">adblocker
 (ads, banners, cookies, javascript)</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">intelligent
 cache </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">ftp-gateway</font>
 </ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">a web server
 </font>
 <ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">what
 is cgi under visual basic </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how
 to integrate php cgi module (php.exe) </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how
 to integrate java-classes into your server (java.exe) </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">xml
 support (MSXML4, JAVA XERXES)</font>
 </ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">a smtp
 server (nslookup dns-server..) </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">a SOCKS4
 and SOCKS5 Server</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">a telnet
 gateway</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">a multiple
 internet mail gateway (POP/IMAP/SMTP per User)</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">smartremote
 server for user-specific behavior of the proxy (level of ad-block, xml
 on/off...) and starting a ras-connection</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">flatrate-support</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">dynamic
 port-forwarding</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">dyndns-support</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">atomic
 time syncher for german time (uhrzeit.org)</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">executes
 exes on ras-connect (like the silent anti-virus updater of Symantec)</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">can shutdown
 the server on demand and if it is not longer used</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">time management
 for ras-behavior</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">restriction
 and access management per server</font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">....</font>
 </ul>
 <p> </p>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">Tutorial for...</font>
 <ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">what can
 Winsock.ocx do within a Visual Basic Application </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">what can't
 Winsock.ocx do and what are problems </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i make up a ras-connection (rasapi32.dll) </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i dis2connect from lan </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i run exes at dial up </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i implement a atomic time sync-er </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i implement a dyndns-updater </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i get the ip-addresses and adapters from my system </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i implement a secure socket (MS Crypto Api 2) and layers </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i implement a winsock-pool that strikes back incoming requests </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i use threads in vb (COM) </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i use System-Tray (Admin/GoOnline) </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i use transparent forms (bitmap regions on forms that are transparent)
 </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i skin my apps </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i paint on menues </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i make a Server-Application </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i make a Remote Client Agent </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i use zlib zip compression utility 1.1.4 </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">how can
 i use res-files and international ressources </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">.... </font>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">some project
 files from earlier releases (mail: pop2,imap,smtp with filesystem)<br>
 but not supported any more. </font>
 </ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">why the GPL?
 </font>
 <ul>
 <li><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">some of
 my modules contain procs that use algos from other talented<br>
 programmers (from planet-sourcecode.com, sourceforge.net, vbip.com)<br>
 so i want to give everybody who's interested at hardcore visual basic
 the<br>
 possibility to check out the code freely.<br>
 <br>
 i think the gpl is a good alternative to freeware or adware.<br>
 Also i do not commercially use the compilers and thats the point.<br>
 </font>
 </ul>
</ul>
</body>
</html>

