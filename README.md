td-coap3
========

This repo contains the Test Descriptions for ETSI plugtest CoAP#3.

For each area of testing, there is a pair of files:

| Area              | source file                                                        | html version                                                       |
| ---               | ---                                                                | ---                                                                |
| Base CoAP         | [base.yml](http://github.com/cabo/td-coap3/blob/master/base.yml)   | [base.html](http://rawgithub.com/cabo/td-coap3/master/base.html)   |
| Block and Observe | [block.yml](http://github.com/cabo/td-coap3/blob/master/block.yml) | [block.html](http://rawgithub.com/cabo/td-coap3/master/block.html) |
| Link format       | [link.yml](http://github.com/cabo/td-coap3/blob/master/link.yml)   | [link.html](http://rawgithub.com/cabo/td-coap3/master/link.html)   |
| DTLS              | [dtls.yml](http://github.com/cabo/td-coap3/blob/master/dtls.yml)   | [dtls.html](http://rawgithub.com/cabo/td-coap3/master/dtls.html)   |

In the test descriptions, the following shorthands are used for the references:

| shorthand  | document                                                                                |
| ---        | ---                                                                                     |
| \[COAP]    | [draft-ietf-core-coap-18](http://tools.ietf.org/html/draft-ietf-core-coap-18.txt)       |
| \[OBSERVE] | [draft-ietf-core-observe-11](http://tools.ietf.org/html/draft-ietf-core-observe-11.txt) |
| \[BLOCK]   | [draft-ietf-core-block-14](http://tools.ietf.org/html/draft-ietf-core-block-14.txt)     |
| \[LINK]    | [RFC 6690](http://tools.ietf.org/html/rfc6690.txt)                                      |

The following parameters have not yet been assigned by IANA but are
needed for the DTLS tests:

* 0xC0 0xAC as the cipher suite identifier for TLS_ECDHE_ECDSA_WITH_AES_128_CCM_8
* For RPK:
  * client_certificate_type: 122
  * server_certificate_type: 123

