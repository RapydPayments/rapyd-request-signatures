# Rapyd Request Signatures Code Sample
 
When you send an HTTPS REST request to the Rapyd Payments platform, you must include specified header parameters, including a signature. These headers are required for both the production platform and the sandbox. The headers are not required in the response from your remote authorization server.

The signing process helps secure requests in the following ways:

Verifies that the requester is an authorized user.
Protects data from tampering in transit.
Rejects requests from unauthorized persons.
When you send a request, you calculate the signature and insert the result into the signature header. When the platform receives the request, it performs the same signature calculation. If the resulting values do not match, the request is rejected.


## Demo Video (YouTube)
<a href="https://youtu.be/IUqDc4Siq70"><img src="https://files.readme.io/9e2d724-isaac-request-signatures.png" alt="thumbnail of video link for youtube video showing rapyd request signatures video" style="width:500px"></a>

## Resources
* Make your first API Call with Rapyd Payments documentation:
https://docs.rapyd.net/build-with-rapyd/docs/make-your-first-api-call
* Join the Rapyd Community:
https://community.rapyd.net 
