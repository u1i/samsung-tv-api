# Samsung TV API

Based on [https://travis-ci.org/vrachieru/samsung-tv-api](https://travis-ci.org/vrachieru/samsung-tv-api)

This project is a library for remote controlling Samsung televisions via a TCP/IP connection. 
It currently supports modern (post-2016) TVs with Ethernet or Wi-Fi connectivity.

## Install

```
git clone https://github.com/u1i/samsung-tv-api
pip3 -r reqirements.txt
python setup.py install
```

## Usage

```python
from samsungtv import SamsungTV

tv = SamsungTV('192.168.xxx.xxx')
tv.power() # toggle power
```

```python
from samsungtv import SamsungTV

tv = SamsungTV('192.168.xxx.xxx')
tv.open_browser("http://www.yahoo.com")
```

## License

MIT