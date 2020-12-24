# bread-storage-request-form
Web form for requesting a directory on Bread

## What is this?

It's a web form for creating new directories on Bread without human intervention

## How does it work?

It's a Flask app, run with GUnicorn, on BLT

## How do I run it?

`gunicorn app:app -b 127.0.0.1:8000 --daemon`
