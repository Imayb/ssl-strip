# ssl-strip
Demostration of SSL strip attack where all traffic from the victims machine is routed via a proxy that is created by the attacker. I will be using a hotspot that the victim would connect to.

Used on a Kali VM in Orcale VM VirtualBox

[![git.png](https://i.postimg.cc/fTQJwczn/git.png)](https://postimg.cc/mhVbjF18)

[![git.png](https://i.postimg.cc/jdRtgZq5/git.png)](https://postimg.cc/LhQchk1K)

^cloning from github and using easy creds to change executable permission to run the installer using those commands

[![git.png](https://i.postimg.cc/hj8NVRd0/git.png)](https://postimg.cc/BL6hGyN8)

^ running the installer choosing Ubuntu and installing to /opt, was successful and metasploit is installed, ifconfig to check interfaces to use later

[![git.png](https://i.postimg.cc/x8Cg8wy8/git.png)](https://postimg.cc/VrxXHHhP)

^ Using sudo easy-creds to run it

[![git.png](https://i.postimg.cc/nzdYydbJ/git.png)](https://postimg.cc/R6HHfLZs)

^choosing FakeAP Attacks

[![git.png](https://i.postimg.cc/QNHzJzTs/git.png)](https://postimg.cc/kDPwnfsh)

^Choosing FakeAP Attack Static

[![git.png](https://i.postimg.cc/Lsxyzk4n/git.png)](https://postimg.cc/B81c3KK0)

^Don’t need this right now so choosing no

[![git.png](https://i.postimg.cc/fRK5N79B/git.png)](https://postimg.cc/Mnn10QtQ)

^ Answering all these questions of network interfaces, named the wifi “AttWIFI”

[![git.png](https://i.postimg.cc/4drQ5BDN/git.png)](https://postimg.cc/7GnzPMPp)

^ After hitting enter after the previous screenshot these screens show up, one is for logging. When victim connects to the wifi an IP address will be assigned and all traffic will be forwarded to the attackers machine. 

What can organizations do to protect their applications against such attacks?

Enable SSL site wide (i.e., use HTTPS only).

Enable HSTS (HTTP Strict Transport Security).

Enable Cert Pinning.

Enable secure cookies, i.e., ensure that all cookies are served with the secure attribute, so that your user’s browsers will only send those cookies back over SSL-protected connections and never disclose them over any non-SSL (HTTP) link.

Disable HTTP (non-SSL) access, or redirect users to the SSL version of the web site.
