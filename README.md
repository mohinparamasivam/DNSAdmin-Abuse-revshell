# DNSAdmin Group AD Abuse
## Create Custom DLL with Reverse Shell in new thread

DLL Created using MSFVENOM crashes the DNS service after it restarts because it does not fork as a separate process for the elevated shell.
That’s not a good thing during a pentest since it will distrupt DNS requests in an organisation. To get around this, we can add a function in the DLL that starts an elevated shell in a new thread and keeps the DNS service running.

<b> Blog : https://medium.com/r3d-buck3t/escalating-privileges-with-dnsadmins-group-active-directory-6f7adbc7005b</b> 


<b>Youtube Link (IPPSEC) :  https://www.youtube.com/watch?v=8KJebvmd1Fk  </b>

<b> DLL Template :  https://github.com/dim0x69/dns-exe-persistance </b>

<b> C++ Reverse Shell :  https://github.com/tudorthe1ntruder/reverse-shell-poc </b>






