# This is a workflow trigger practice code

Deliberately created an issue in `index.py`. I was supposed to return the `total` from the function
but deliberately returned the `iterable` instead. I pushed the code to GitHub, so that I can raise
an `issue` on it and then simulate a workflow with an `issue` trigger.

The `schedule` event runs a cron job every midnight and triggers the `check-open-issues` job to send a message if there is an open issue.
Deliberately created an issue in the `app.py` file to see how it reacts to this event. Will raise this issue on Github.
