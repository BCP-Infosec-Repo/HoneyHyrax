### Magic Words

```
The team you provided the key material to is now trying to encrypt an exploit payload to a remote device.
They are having issues.  
Can you help?

Problem:

Alice: We are trying to encrypt the following exploit payload, "ZWdhcmZpc3NPIGhzaW1hZXVxUyBlcmEgZG5lUyBvVCB0bmFXIFpkcm9XIGNpZ2FNIGVoVCAgIFpN"
Bob: We have tried your key with this equation, c = m^e Mod N?  When we send, we are not seeing the expected bytes on the wire?
Mallory: I was reading this book "Attacking Network Protocols: A Hacker's Guide to Capture, Analysis, and Exploitation 1st Edition by James Forshaw,
         Is there a problem here with the byte order?
Alice: Using the material you sent us, in our tests, we can decrypt the bytes sent, but the don't match the input bytes?
```

You need to confirm why the message/payload is not being properly sent.

Find the issue with the bytes. 

Focus just on the payload for now.  Its not a real exploit, its a challenge in encoded/decoding/OS/Network things. :)

Outcome:  Input bytes should be the same as the output bytes.  

