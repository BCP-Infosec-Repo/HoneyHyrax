### Magic Words

```
The team you provided the key material to is now trying to encrypt an exploit payload using the key material.
They are having issues.  
Can you help?

Problem:

Alice: We are trying to encrypt the following exploit payload, "ZWdhcmZpc3NPIGhzaW1hZXVxUyBlcmEgZG5lUyBvVCB0bmFXIFpkcm9XIGNpZ2FNIGVoVCAgIFpN"
Bob: We have tried your key with this equation, c = m^e Mod N?  When we send, it seems to not be the expected bytes?
Mallory: I was reading this book "Attacking Network Protocols: A Hacker's Guide to Capture, Analysis, and Exploitation 1st Edition by James Forshaw,
         Is there a problem here with the byte order?
```

You need to confirm why the message/payload is not being properly sent.

Focus just on the payload for now.  

