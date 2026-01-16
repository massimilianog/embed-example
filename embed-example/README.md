
try qlik-embed on Stage

reference docs: https://qlik.dev/embed/qlik-embed/quickstart/qlik-embed-webcomponent-quickstart/

run locally:

- (fisrt time only) generate openssl key pairs using the command:
  - openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
- (first time only) install http-server, e.g. with npm install -g http-server
- (first time only) add "127.0.0.1 example.qlik-stage.com" to your /etc/hosts file
- run: http-server --cors -S -C cert.pem --port 443

browser: https://example.qlik-stage.com/