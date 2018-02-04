# IPRBLCK (IP Real-time Blocklist Check)

Script purpose:
-----------------
This script allows you to use a text file with several IP addresses to query against multiple IP Real-time blocklists. 




How to use:
-----------------
A text file with the name "IPs.txt" should be created in the same directory the script is located. 




Requirements/dependencies:
--------------------------
- Python 2.7.x
- dnspython library (git://github.com/rthalley/dnspython.git)



Installing the library:
-----------------------
git clone https://github.com/rthalley/dnspython.git

cd dnspython/

python setup.py install 



Sources queried:
-----------------
'b.barracudacentral.org',
'spam.rbl.msrbl.net',
'zen.spamhaus.org',
'bl.deadbeef.com',
'bl.emailbasura.org',
'bl.spamcannibal.org',
'bl.spamcop.net',
'blackholes.five-ten-sg.com',
'blacklist.woody.ch',
'bogons.cymru.com',
'cbl.abuseat.org',
'cdl.anti-spam.org.cn',
'combined.abuse.ch',
'combined.rbl.msrbl.net',
'db.wpbl.info',
'dnsbl-1.uceprotect.net',
'dnsbl-2.uceprotect.net',
'dnsbl-3.uceprotect.net',
'dnsbl.ahbl.org',
'dnsbl.cyberlogic.net',
'dnsbl.inps.de',
'dnsbl.njabl.org',
'dnsbl.sorbs.net',
'drone.abuse.ch',
'drone.abuse.ch',
'duinv.aupads.org',
'dul.dnsbl.sorbs.net',
'dul.ru',
'dyna.spamrats.com',
'dynip.rothen.com',
'http.dnsbl.sorbs.net',
'images.rbl.msrbl.net',
'ips.backscatterer.org',
'ix.dnsbl.manitu.net',
'korea.services.net',
'misc.dnsbl.sorbs.net',
'noptr.spamrats.com',
'ohps.dnsbl.net.au',
'omrs.dnsbl.net.au',
'orvedb.aupads.org',
'osps.dnsbl.net.au',
'osrs.dnsbl.net.au',
'owfs.dnsbl.net.au',
'owps.dnsbl.net.au',
'pbl.spamhaus.org',
'phishing.rbl.msrbl.net',
'probes.dnsbl.net.au',
'proxy.bl.gweep.ca',
'proxy.block.transip.nl',
'psbl.surriel.com',
'rbl.interserver.net',
'rdts.dnsbl.net.au',
'relays.bl.gweep.ca',
'relays.bl.kundenserver.de',
'relays.nether.net',
'residential.block.transip.nl',
'ricn.dnsbl.net.au',
'rmst.dnsbl.net.au',
'sbl.spamhaus.org',
'short.rbl.jp',
'smtp.dnsbl.sorbs.net',
'socks.dnsbl.sorbs.net',
'spam.abuse.ch',
'spam.dnsbl.sorbs.net',
'spam.spamrats.com',
'spamlist.or.kr',
'spamrbl.imp.ch',
't3direct.dnsbl.net.au',
'tor.ahbl.org',
'tor.dnsbl.sectoor.de',
'torserver.tor.dnsbl.sectoor.de',
'ubl.lashback.com',
'ubl.unsubscore.com',
'virbl.bit.nl',
'virus.rbl.jp',
'virus.rbl.msrbl.net',
'web.dnsbl.sorbs.net',
'wormrbl.imp.ch',
'xbl.spamhaus.org',
'zombie.dnsbl.sorbs.net'
