
---

This server is adapted from
[sinatra_sockets](http://github.com/maxpleaner/sinatra_sockets),
another boiler I made.

---

Steps:

1. bundle
2. bundle exec rake db:create db:migrate
2. bundle exec thin start

---

This version has a lot of stuff removed since it's serving no front-end.
It's just the API for the webpack client

Important files:
  - websocket stuff in ws.rb
  - regular routes in server.rb
  - crud generator
  - server push
---
