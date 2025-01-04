# http3

Experimental HTTP/3 tooling for Java / JVM systems.

Motivation / bets:
* I want to properly understand HTTP/3 and WebTransport (and therefore also QUIC), and implementing from scratch is a 
  good way to do that
* Both HTTP/3 and WebTransport will offer very interesting new capabilities to websites and apps 
* WebTransport appears to require HTTP/3 at every layer (including LB <-> application), so having it readily available
  for Java apps is important

Other ideas:
* Thorough automated testing is important, so use or build something like h2spec for verification
* If the project goes well, it could be packaged up as something to build clients on
  * Or maybe even the basis for an HTTP/3-only client
* Loom means it can be declarative, and hopefully easier to implement and understand the threading model (eg thread per
  stream)

Documentation:
* HTTP/3 RFC: https://datatracker.ietf.org/doc/html/rfc9114
* QUIC RFC: https://datatracker.ietf.org/doc/html/rfc9000
* WebTransport MDN: https://developer.mozilla.org/en-US/docs/Web/API/WebTransport

## Contributing

I'm not currently looking for external code contributions. If you'd like to help:

* Give your feedback in [Discussions](https://github.com/lopcode/http3/discussions)
* Share the repo in your circles / social media
* Star the repo 🌟

Thank you for being enthusiastic about the project!