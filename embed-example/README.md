
try qlik-embed on Stage

reference docs: https://qlik.dev/embed/qlik-embed/quickstart/qlik-embed-webcomponent-quickstart/

run locally:

(first time only) install http-server, e.g. with npm install -g http-server
(first time only) add "127.0.0.1 example.qlik-stage.com" to your /etc/hosts file
run: http-server --cors -S -C cert.pem --port 443

browser: https://example.qlik-stage.com/