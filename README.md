Work in progress, not intended for public testing!
===============================

SABYenc - yEnc Encoding/Decoding for Python
===============================

Mofied the original yenc module by Alessandro Duca <alessandro.duca@gmail.com>
for use within SABnzbd.

The module was extended to do header parsing and full yEnc decoding from a Python
list of chunks, the way in which data is retrieved from usenet.


Testing
===============================
For testing we use `pytest` (install via `pip install pytest`) and test can simply be executed by browsing to the `sabyenc` directory and running:
```
pytest
```