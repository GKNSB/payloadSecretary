# payloadSecretary
Sudo type me a payload

Have you ever found yourself having to perform a test, and a client has provided you with a VM inside a VDI inside a citrix application through internet explorer? Of course without the ability transfer over your precious tools in that god-forsaken environment? 

Well, you can just base64 encode whatever you want to move over, put the string in the respective parameter, and leave the secretary to do the job. Type dat shit away! Quick and dirty, it helped me, might help you, that's all.

```
pip3 install keyboard

python3 payloadSecretary.py
```

After running, you'll have 10 seconds to move the focus to whatever window you want the typing to occur in. 