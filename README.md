# Samsung TV API

Based on [https://github.com/vrachieru/samsung-tv-api](https://github.com/vrachieru/samsung-tv-api)

This project is a library for remote controlling Samsung televisions via a TCP/IP connection.
It currently supports modern (post-2016) TVs with Ethernet or Wi-Fi connectivity.

## Enable Developer Mode on your TV

Open 'Apps' and navigate to 'My Apps'. Press the '123' button and enter the numbers 1,2,3,5 in sequence. You should now see a screen where you can enable developer mode and enter the IP address of your client / laptop from where you'll run this tool.

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
