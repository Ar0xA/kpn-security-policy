howto:

apt-get install pdf2htmlEX
mkdir html
cd html
find ../kpn-security-policy -type f -name "*.pdf" -exec pdf2htmlEX {} \;

