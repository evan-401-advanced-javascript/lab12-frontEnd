# OAuth Comparative Analysis
## OAuth Provider Name: GitHub
## OAuth Provider Name: Google
### Research Conducted By: Autstin Hedeen, Corey Change, Evan BC, Gina Pultorak
### Overall Score and Comments
#### Score (Out of 10): GitHub: 9/10, Google: 9/10 No noticable difference between the two when comparing implementation.
#### General Comments
Describe the stack (front-end only? full stack?), database, efficiency, etc. Describe the general usability and learnability.
Full stack. Mongo database. Unknown efficiency. General usability can be modified relatively easily for different oauth services. Learnability - following documentation learning was relatively easy for GitHub.
#### Pros
* GitHub - easy to follow documentation
* Google - high security standard
#### Cons
* GitHub - not aware of any
* Google - not aware of any
### Ratings and Reviews
#### Documentation
Documentation was straightforward. First time implementing, made it more challenging.
#### Systems Requirements
Above and beyond 'node' and 'linux', what dependencies or core requirements exist for this framework? brypt, jwt, mongoose, express, cors, morgan, superagent
Can it play at AWS/Heroku?  In process. Does it require a certain database? Mongo DB
#### Ramp-Up Projections
How long would/should it take a team of mid-junior developers to become productive? Great question. We estimate it will take a team about 4 hours to become productive.
#### Community Support and Adoption levels
How popular is this framework? GitHub is a very popular framework.
What big companies are running on it? Many big companies are running on it.
How is it "seen" in the general JS community?  n/a
Is there an active community of developers supporting and growing it? Yes, there is an active community of developers supporting it.
### Links and Resources
* [framework](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/)
* [docs](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/)
* [examples/tutorials](https://membrane-soa.org/service-proxy-doc/4.4/oauth2-github.htm)
### Code Demos
* [live/running application](http://xyz.com)
* [code repository](http://xyz.com)
### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
* npm start
* mongod --dbpath=./.db
* go to localhost:8080