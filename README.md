#Transforming into Your Teams Web Security Guru#
##Information and links from the O'Reilly Fluent 2015 conference talk:##

####Important starting points####

Organization | Link
------------ | ----
SANS | https://sans.org
OWASP | https://owasp.org
CWE | https://cwe.mitre.org
CVE | https://cve.mitre.org
CAPEC | https://capec.mitre.org/data/index.html#search

CWE/SANS Top 25 Most Dangerous Software Errors
https://cwe.mitre.org/top25/

But wait, there's more...
https://cwe.mitre.org/top25/archive/2011/2011_onthecusp.html


####AppSec Knowledge - Know the vulnerabilities####

Title	| Link
----- | ----
Web Top 10 | http://goo.gl/1lZpjT
Mobile Top 10 | http://goo.gl/PcqNyc
Cloud Top 10 | http://goo.gl/paAE3R
Proactive Controls Top 10 | http://goo.gl/SDtOi4
Cheat Sheets | http://goo.gl/99nI6h
The OWASP Guide to Building Secure Web Apps & Web Services | http://goo.gl/olLtHw
The OWASP Testing Guide | http://goo.gl/4XQiAv
The OWASP Code Review Guide | http://goo.gl/5FizT7


####AppSec Knowledge - Know the tools####

Tool | Links | Notes
---- | ----- | -----
ZAP Proxy | http://goo.gl/smh3Vm | OWASP’s Proxy
Burp Suite | http://goo.gl/wCMGqA | "java -jar -Xmx1024m /path/to/burp.jar http://portswigger.net/burp/help/suite_gettingstarted.html"
Fiddler | http://goo.gl/VqpnOU | Requires .NET or Mono

Distro | Links | Notes
------ | ----- | -----
Kali | https://www.kali.org | "General Security Testing   See also:  http://www.blackmoreops.com"
OWASP Web Testing Environment | https://www.owasp.org/index.php/OWASP_Web_Testing_Environment_Project | OWASP specific, mainly contains OWASP tools
Samurai-WTF | http://www.samurai-wtf.org | Web Security Testing
Santoku | https://santoku-linux.com | Mobile Security Testing
MobiSec | http://mobisec.professionallyevil.com | Mobile Security Testing
OWASP Broken Web Apps | http://sourceforge.net/projects/owaspbwa | Set of vulnerable apps

Also, take a look at this site:	http://www.toolswatch.org


####Static Analysis####

__Discovering Sources and Sinks__
* http://code.google.com/p/domxsswiki/wiki/Introduction/
* http://www.webappsec.org/projects/articles/071105.shtml/
* http://html5sec.org/
* http://goo.gl/vf61Km  		(Spreadsheet of srcs/snks for JSPrime tool)


Automation tools

Scanner | Link
------- | ----
NodeJsScan | https://github.com/ajinabraham/NodeJsScan
NodeJsScan (forked - with new rules) | https://github.com/steilhet/NodeJsScan
Static-DOM-XSS-Scanner | https://github.com/ajinabraham/Static-DOM-XSS-Scanner
Scanjs | https://github.com/ajinabraham/scanjs
Yasca | http://scovetta.github.io/yasca/


####Dynamic Analysis####

__Targets__
* Google Gruyere
  * http://google-gruyere.appspot.com/start/
    * http://google-gruyere.appspot.com/part1/

* OWASP Test Apps List
  * https://www.owasp.org/index.php/OWASP_Vulnerable_Web_Applications_Directory_Project#tab=On-Line_apps

* IBM Altoro Mutual Bank
  * http://altoromutual.com/

* OWASP Faux Bank
  * http://github.com/thatcoderguy/owasp-faux-bank/
    * http://www.fauxbank.co.uk/

* The Goats
  * https://www.owasp.org/index.php/OWASP_WebGoat_Project/
  * https://www.owasp.org/index.php/Category:OWASP_WebGoat.NET
  * https://www.openhub.net/p/owasp-goatdroid-project/
  * https://code.google.com/p/owasp-igoat/wiki/NewDownloads/
  * https://github.com/OWASP/NodeGoat/
    * http://nodegoat.herokuapp.com/

* Others
  * http://www.ntobjectives.com/hackazon/
  * http://hackyourselffirst.troyhunt.com/
