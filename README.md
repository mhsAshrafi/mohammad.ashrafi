# mohammad.ashrafi
for Planit Project


Assume you were asked by duckduckgo to performance test their application.
You are given a requirement which states "The system should scale to 2000 users". What other questions would you need to ask in order to get enough information to create a workload model?
  The most important question is about the infrastructure and how the system deploys in real operation. 
  Do we have a real clustering server? 
  What are the specifications of the servers? 
  Can we use a caching system or CDN for static components (banners-jpg-font,...). 
  What are the specifications of the network and bandwidth?
  Can I suggest some changes to gain more performance?(for example change the order of CSS/JS loading- Minify the JS Component - ...)
/*--------------------------------------------------------------------------------*/
Please rewrite the requirement above so that it is more descriptive and testable?
  For more accurate analysis, you can monitor the server on IP/Port.
  The script should report TPS for all elements of the search process.
  Put the "SearchTermsDuckDuckgo.csv" file on C:// and PLZ dont remove the space char from Terms.
  Using Plugin in Jmeter is not forbidden.
  
/*--------------------------------------------------------------------------------*/
As well as creating a script in a tool to do the performance testing, what other factors would need to be considered for a performance testing engagement?
  who is responsible for out of service status?
  who is responsible for changing the content and evaluating this change for performance metric benchmarking.

