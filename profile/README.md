![Duo Security](/images/duoLogo-web.png)

# Duo Security on GitHub

Duo Security hosts a variety of repositories for use by developers that want to integrate their applications with Duo.
Some highlights:
* API clients for integrating with Duo's [Auth API](https://duo.com/docs/authapi) and [Admin API](https://duo.com/docs/adminapi)
* Web SDK repositories for adding Duo 2FA to a [web application](https://duo.com/docs/duoweb)
* [Duo Unix](https://duo.com/docs/duounix), for adding Duo 2FA to Unix and Linux authentication
* Duo Log Sync for consuming Duo logs from your own applications

----

Duo Security has deprecated and archived all the Web SDK v2 repositories.  Please see the [Frequently Asked Questions](https://duosecurity.github.io/faq.html) for more information.

----

Duo Security is deprecating the use of insecure TLS protocols and ciphers for interacting with the Duo APIs, effective June 30, 2023:
- TLS 1.0
- TLS 1.1
- These TLS 1.2 ciphersuites:
    - TLS_RSA_WITH_3DES_EDE_CBC_SHA
    - TLS_RSA_WITH_AES_256_CBC_SHA
    - TLS_RSA_WITH_AES_256_CBC_SHA256
    - TLS_RSA_WITH_AES_128_CBC_SHA
    - TLS_RSA_WITH_AES_128_CBC_SHA256
    - TLS_RSA_WITH_AES_128_GCM_SHA256
    - TLS_RSA_WITH_AES_256_GCM_SHA384
    - TLS_ECDHE_RSA_WITH_3DES_EDE_CBC_SHA


For more information on this deprecation, see [this Knowledge Base article](https://help.duo.com/s/article/7546) and [the Duo blog](https://duo.com/blog/weak-cipher-tls-1-0-1-1-deprecation-with-duo-mfa).

Please see the READMEs in each repo for SDK-specific information on the requirements for TLS 1.2 support.