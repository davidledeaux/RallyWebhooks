This repository contains some proof of concept ways to use Rally (Agile Central) webhooks.

sample_payload is an example of what an actual webhook payload looks like.  Sensitive information has been removed.  This can be useful for playing through a curl or rest client to push a request through to your application so you can see errors generated in the body.

google_web_app uses the Google Scripting engine to write a new row to a spreadsheet each time a webhook is fired at it.  It extracts the time of update, object type, formatted ID, artifact name and what changed.  Inspiration for this came from https://blog.runscope.com/posts/tutorial-capturing-webhooks-with-google-sheets.
