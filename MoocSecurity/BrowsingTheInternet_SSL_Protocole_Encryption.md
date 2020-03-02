## SSL/TLS 

Before we start lets make a quick review on SSL and TLS :

- **SSL** : Secure Sockets Layer
- **TLS** : Transport Layer Security

they are both protocols used to send data online securely. SSL is older than TLS, but all SSL certificates can use both SSL and TLS encryption.

Now that we know what their purpose is, let's take a look at the type of vulnerability they have.


SSL is the standard in online security.  It is used to encrypt data sent over the Internet between a client (your computer) and a server (a website's computer),
normally if a hacker intercepts encrypted data, the hacker can't read it or use it without the private decryption key.

However, assaults on trust through the SSL/TLS-encrypted traffic are now common and growing in frequency, SSL can be intercepted, either for legitimate or illegitimate reasons.
Interception is achieved through the use of "middleboxes," which are between the website and the client's machine.
These middleboxes have proxy software that can delete and restart the SSL connection, allowing a middleman access to private information.  
This SSL certificate vulnerability can be avoided by using strict SSL.


## Protocol Encryption

Encryption is an interesting piece of technology that works by scrambling data so it is unreadable by unintended parties.
We can find it in mails for exemple, but encrypted data are not fully protected.

The list below contains most of the famous encryption protocol we know :
- **3DES** : Triple Data Encryption Algortihm
- **AES | AES256** (successor of 3DES) : Advanced Encryption Standard
- **RSA** : Rivest Shamir Adleman

In the list above the most secure encryption protocol of today is AES256 would take billions of years to break using current computing technology. 
Hackers would be foolish to even attempt this type of attack, Nevertheless, no **encryption system** is entirely secure.

That is why when you are browsing the internet, you should always think twice on what you are willing to share with others, you do not know if someone will be able to
intercept your data and decrypt it.

