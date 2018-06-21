# subtitle
Python3 library to perform basic actions on subtitle (*.srt) files.
This library utilizes the googletrans library (https://github.com/ssut/py-googletrans).
Install using:
```python
$ pip3 install googletrans
```
## usage
The example below shows how to use the library.
```python
from subtitle.subtitle import Subtitle

subtitle = Subtitle()
subtitle.translate('subs.srt')
```
