# A Node.JS Forward Proxy Server

### Packages used:
* ```http```
* ```url```
* ```net```


### Usage
#### Clone the repository:  
    $ git clone https://github.com/gl14916/nodejs-forward-proxy-server.git  
    $ cd nodejs-forward-proxy-server

#### Start forward proxy server using the following command:
```$ npm start``` or ```$ node proxy.js```  

### Specification
By default, the proxy server listens on port ```2560```, change it in the last line of code (```proxy.js:75```).  
If you wish to use a port number under ```1024```, you need to run this proxy server as root (```$ sudo npm start``` or ```$ sudo node proxy.js```)

### License
MIT
