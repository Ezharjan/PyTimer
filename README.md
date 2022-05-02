# PyTimer

This is a simple timer written with Python.

## Setup
1. change the codes in `playsound.py` as below:

```python
    def winCommand(*command):
        bufLen = 600
        buf = c_buffer(bufLen)
        # command = ' '.join(command).encode('utf-16') # original ones
        command = ' '.join(command) # after changed
```

## Tutorial

- pip3 install -r requirements.txt
- python timer.py --time xxx  ===> time: unit is second (Default time is 20 minutes)
- eg: python timer.py --time 10 ===> 10 seconds timer




