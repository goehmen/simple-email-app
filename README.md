# simple-email-app
hit button - get email 

Notes:
Just need to spin up a VM & call mailx

Need an auth mechanism in front.

Need html/css to createa a button & the button simply sends me an email.

could look at: 
- fritter/python
- sinatra/ruby  <-- this is the direction I'm going
  - sinatrarb.com for quick up & running ruby 

For login:
- csquared/sinatra-google-auth 
- console google developer to register app & get key/secret
- also - nice to do an OKTA integration

For email:
- mail script search for 'ruby smtp'  for smtp server, use google server

For web form:
- html = "\<form\>" .
- take the "hello world" text from simplest example script in hi.rb (from sinatrarb.com) and sub in html instead of Hello World text 
