data2server
===========

The goal is to send the data acquired in Labview to a web server (RESTful).

The data are encoded in JSON.

If the web server doesn't confirm the data's reception, the data stays in the queue.
If the queue becomes too large, a .txt file is created with all the datas and send to a FTP.

Dependencies
------------
https://github.com/Philmod/Labview-JSON

Use
---
main.vi

Contribute
----------
Please feel free to contribute.

TODO list
---------
- If there's a FTP issue, send the .txt files by email.
- Possibility to send a array of clusters (JSON), it would be faster.