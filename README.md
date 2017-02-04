# bin
General useful scripts

== Another CASA install script ==  
Installation into Python Virtual Environment
> virtualenv --system-site-packages venv  
> source venv/bin/activate  
> mkdir venv/local/casa

Installing CASA
> ./installCASA.sh -f casa-release-4.5.3-el6.tar.gz -l venv/local/casa/

General installation of CASA to system (/usr/local)
> ./installCASA.sh -f casa-release-4.7.0-el7.tar.gz

