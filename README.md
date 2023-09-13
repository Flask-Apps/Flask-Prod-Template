# Flask-Prod-Template

## Why use Celery?

- We'll use it to handle long-running tasks.
- Every application will eventually require this to offload time or computation intensive processes like main sending, automatic database housekeeping or things like processing uploaded documents(eg: images), from web server threads on external workers
