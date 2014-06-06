Keen R&B
=======

**[Live Demo](http://nealshyam.com/krb)**

*A tool for building Keen.io redirect &amp; beacon URLs*

Detailed explanation to come -- but basically, you input your

- Project ID [persisted for your convenience]
- API Write Key [persisted for your convenience]
- Target Collection (defaults to TEST - you must explicitly uncheck this box and include a collection for production use)
- Any relevant tracking/identifying data you want to keep track of or analyze later on. 
  - The geo-ip & user agent addons are added automatically, so don't worry about the `${keen.ip}` or `${keen.user_agent}` properties. 
- For redirects, you must add a end URL

and R&B will build you two URLs that you can drop into emails or whatever you're tracking. That's pretty much it. Forks & Pulls welcome.
