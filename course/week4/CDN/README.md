1 the users should build connection with local server not origin server. because if the user want to communicate with remote server, it takes long time, for the handshake phase and slow start phase.

We should let the local server to communicate with the remote server, and the remote server can send the response to the local server, because the local server always stay contact with remote server, so the package rate between these two servers are pretty fast.

There are two ways to achieve the load balancing
1 You can Use the local resolver  TL resolver, and a CDN resolver to get different IP address for the same domain name.

So the CDN solver need to make decision based on the location of the local server

Set the BGP in different locations with different prefix with the same domain. So the result would be the packets will travel with the same prefix will travel on the same way.

And I finish the Quiz for chapter 4
https://class.coursera.org/cloudnetworking-001/quiz/
The quiz is really useful to help learn the basic ideas.
