----
# Welcome to WCG! #

----
## What is WCG? ##
WCG is a modern economic system based on cryptography and blockchain technology based on NXT.

With WCG, you can manage and interact with

 - your **assets**
 - your **businesses**
 - your **customers**

in such a way that no trusted third parties are required anymore.

----
## Dependancies! ##
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`
----
## Run it! ##

  - click on the WCG icon, or start from the command line:
  - Unix: `./start.sh`
  - Mac: `./run.command`
  - Window: `run.bat`

  - wait for the JavaFX wallet window to open
  - on platforms without JavaFX, open http://localhost:27876/ in a browser

----
## Compile it! ##

  - if necessary with: `./compile.sh`
  - you need jdk-8 as well

----
## Improve it! ##

  - we love **pull requests**
  - we love issues (resolved ones actually ;-) )
  - in any case, make sure you leave **your ideas** at BitBucket
  - assist others on the issue tracker
  - **review** existing code and pull requests
  - cf. coding guidelines in DEVELOPERS-GUIDE.md

----
## Troubleshooting the NRS (Nxt Reference Software) ##

  - How to Stop the NRS Server?
    - click on Nxt Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on BitBucket

  - Permissions Denied?
    - no spaces and only latin characters in the path to the NRS installation directory
    - known jetty issue

----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md

  - in the wiki:
    - nxtwiki.org

  - on the forums:
    - nxtforum.org
    
----
## Get NXT! ##

  - *pre-packaged* - `https://bitbucket.org/JeanLucPicard/nxt/downloads/nxt-client-{version}.zip`

  - *dependencies*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

  - *repository* - `git clone https://bitbucket.org/JeanLucPicard/nxt.git`
  
----
