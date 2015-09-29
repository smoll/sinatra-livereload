sinatra-livereload example
===

This demonstrates that Sinatra & the Sinatra::Reloader plugin work together, but this requires a browser refresh to see changes to app.rb in the browser.

LiveReload integration is not working correctly for me, however. Pull requests are welcome, please!

# Usage

0. clone repo
0. in one terminal window, `bundle && bundle exec rackup -p 4567`
0. in a different terminal window, `bundle exec guard`
0. navigate to [http://localhost:4567](http://localhost:4567) in your preferred browser
0. make changes to `app.rb`
0. **(EXPECTED:)** browser automatically refreshes to reflect changes
