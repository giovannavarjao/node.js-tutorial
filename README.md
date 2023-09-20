# node.js-tutorial
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  var currentDate = new Date();
  var formattedDate = currentDate.toISOString(); // Format the date as an ISO s>
  res.end('Giovanna Silva Varjao! Current Date: ' + formattedDate);
}).listen(8036);




