
try embed on SDE https://foq.eu.foq.pte.qlikdev.com/
reference: https://qlik.dev/embed/qlik-embed/quickstart/qlik-embed-webcomponent-quickstart/

run locally with: http-server --cors -S -C cert.pem --port 443

make sure to have the following in the /etc/hosts file:
127.0.0.1 example.qlik-stage.com
or
127.0.0.1 example.qlikdev.com

browser: https://example.qlik-stage.com/
or
https://example.qlikdev.com/
