# NDC Oslo 2018
## Give it a REST presentation from [NDC Oslo 2018](https://ndcoslo.com/)

Ever wondered why someone created a REST API in the way they did? 

Ever wondered why someone consumed your REST API in the way they did?

In the past five years at Huddle we've been updating out public API to be more restful, more tolerant, and to handle the move from a monolithic application to one based on microservices with async operations.

We've also created clients for web, iOS, Android, Windows and OS/X that consume that same API and experienced some of the same pain as our customers when we have taken a wrong turn.

It's not been easy and it's time to share the knowledge of the real-world problems of maintaining a useable API that keeps everyone happy (some of the time).

Rather than concentrate only on the principles of REST and HATEOAS we'll examine everyday issues, best practice for both creators and consumers, and maybe highlight some gaffs along the way.

 - Initial design - the chicken and egg of where to start 
 - Extensibility and versioning, improving an API without breaking it for existing users
  - Patterns for async operations
  - Rate limiting on the server
  - Handling deprecation gracefully
  - Backend for frontends - how to handle (hide) the world of microservices behind your API
  - How to consume APIs to keep your application reliable
  - Extensibility and versioning, coping with change without rolling a new release
- Understanding caching, rate limiting for the client, and   dealing with weird responses
