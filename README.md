Keen R&B
=======

**[Live Demo](http://nealshyam.com/krb)**

*A tool for building Keen.io redirect &amp; beacon URLs*

Detailed explanation to come -- give R&B:

- Project ID [persisted for your convenience]
- API write key [also persisted]
- Target event collection 
  - Defaults to TEST, so you must explicitly uncheck this box and include a collection for production use
- Any relevant tracking/identifying data you want to keep track of or analyze later on. 
  - The geo-ip & user agent addons are added automatically, so don't worry about the `${keen.ip}` or `${keen.user_agent}` properties. 
- For redirects, you must add a referral URL

and it will generate beacon & redirect URLs that you can use in emails or whatever you want to measure. That's it.
