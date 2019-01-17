This repository contains some proof of concept ways to use Rally (Agile Central) webhooks.

google_web_app uses the Google Scripting engine to write a new row to a spreadsheet each time a webhook is fired at it.  It extracts the time of update, object type, formatted ID, artifact name and what changed.
