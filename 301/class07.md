# Read: 07 - APIs continued


### what i learned
 - i like this article a lot, we had to read it in class 02. the fundementals are areally cool. 
  i like how no matter how the teams were formed they all still seemed to excel even without contact, common backgrounds, ormuch in common. Pair programmign is proven way to be succecfull i hope i can one day join an amazing team of people who i will program with and find my place in the stars.

### APIS
- SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!
- request can be initiated by invoking the appropriate method on the request object, then calling .then() (or .end() or await) to send the request. For example a simple GET request:
- Old-style callbacks are also supported, but not recommended. Instead of .then() you can call .end():
-The Node client supports making requests to Unix Domain Sockets:

"// pattern: https?+unix://SOCKET_PATH/REQUEST_PATH
//          Use `%2F` as `/` in SOCKET_PATH
try {
  const res = await request
    .get('http+unix://%2Fabsolute%2Fpath%2Fto%2Funix.sock/search');
  // res.body, res.headers, res.status
} catch(err) {
  // err.message, err.response"

}
- GET requests The .query() method accepts objects, which when used with the GET method will form a query-string. The following will produce the path /search?query=Manny&range=1..5&order=desc.
-POST / PUT requests
A typical JSON POST request might look a little like the following, where we set the Content-Type header field appropriately, and "write" some data, in this case just a JSON string.
[Back to main](README.md)
