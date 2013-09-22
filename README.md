imaplib2
========

Threaded Python IMAP4 client version 2.36.

Based on RFC 3501 and original imaplib module.

This is a version of imaplib that uses threads to allow full use of the
IMAP4 concurrency features, and to de-couple a user of imaplib from i/o
lags, except where explicitly allowed.

Documented in imaplib2.html

Install imaplib2.py into your Python library path.
