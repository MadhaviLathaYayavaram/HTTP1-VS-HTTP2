# HTTP1-VS-HTTP2

## HTTP - HyperText Transfer Protocol

IT is an application protocol standardized by WWW- World Wide Web since its invention in 1989. It is needed to transfer data among the networks using different methods and procedures. Version 1.1 was developed by Timothy Berners-Lee in 1989 to exchange information between a client computer and a client computer.  Here are some features and differences between the versions of HTTP.

###### Differences between HTTP/1 and HTTP/2

There should be less network delay to load a web page faster. There is one important concept that an increase in network bandwidth helps improve page load time. We can understand the difference and performance efficiency between the two versions of HTTP depending on different factors. Modern wi-fi networks use high bandwidth signals, so page load time has been increased many times more than the older dial-up networks which take more page load time. 

## HTTP1

- HTTP1.0 is established in 1991 and 1.1 version in 1997.

- Earlier, in the 1.0 version, there is only one request and one response was handled for every TCP connection. 

- In version 1.1, connection reuse is done to enable multiple requests and responses at the same connection.

- Pipelining to request several resources at a time is difficult in this type of connection. 

- Version1.1 provides faster web traffic delivery in comparing to version 1.0.

- It is relatively slower than HTTP2.

- Loads a single request for every TCP connection.

- Header compression has to be requested specially.

- Only two connections can be added to a single host. 

- The binary code-based protocol needs to be converted back when getting downloaded.

- SSL security is not required but recommended because of its digest Authentication.

- HTTP 1.0  defines 16 status codes and the error prompt is not specific enough relatively to version 2. 
- HTTP 1.1 defines 24 status codes at a time and also includes a warning header field to carry extra information about the status of a message.

- Authentication is encoded using base 64 and there is a threat due to this in version 1.0. But Digest Authentication and NTLM Authentication methods are implemented in version 1.1 which is relatively secured.

- Cache-control conditional headers and entity tags support caching techniques efficiently.
Adoption of HTTP/2 is done by modern browsers by default.




## HTTP2

- HTTP2 is established in 2015.

- Much faster than HTTP1 because of its high Page Load speed.

- Avoids network delay because of its multiplexing feature where requests and responses can be implemented at a time. 

- Performance Optimization provides support to deliver the pages faster than in first version. 

- It is supported and loaded fast in all the major browsers including Chrome, Edge, Firefox, and all others.

- Six connections can be added to a single host. 

- Header compression is included by default in HTTP2 as it uses HPACK.

- Uses SSL/TL security encryption for communications with minimum key size TLS 1.2.

- Headers and status codes work the same as in HTTP 1.1.

- TLS authentication features help in connection errors and improper security reasons.

- The cache maintenance feature is enhanced with the server push mechanism which helps to cancel the pushed stream if it already exists in the local cache.



