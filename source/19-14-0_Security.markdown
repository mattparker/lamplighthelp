# 19.14.0    Security

> We've made a lot of changes to increase the security of the new version of {{Lamplight}}. First of all, you'll notice a 'Digicert' logo on the login page. We use 256-bit SSL encryption to prevent eavesdropping of the information travelling between your 

We've made a lot of changes to increase the security of the new version of {{Lamplight}}. First of all, you'll notice a 'Digicert' logo on the login page. We use 256-bit SSL encryption to prevent eavesdropping of the information travelling between your computer and our server. The server itself is in a physically secure location.

Other standard good practice we follow includes (in brief):

  * all forms are hashed to prevent Cross-Site Request Forgery attacks (CSRF)
  * all data input is filtered and validated
 * all data is escaped when displayed
  * all database transactions use parameters and quoting
  * application code is outside of the web directory.

We also use a number of techniques to secure the server itself. 

###### core module

