# websocket-issue

To replicate, install the bundle.  Then:

```
jruby server.rb
```

which will create a server listening on port 7000 on 127.0.0.1.

Then, open test.html in a browser.  It sends/receives on Java 8, but does not on Java 11.