# Seb Insua
> *Consultant Engineer*<br />
> [me@sebinsua.com](mailto:me@sebinsua.com) • [github.com/sebinsua](http://github.com/sebinsua) • [sebinsua.com](http://sebinsua.com) • [twitter.com/sebinsua](http://twitter.com/sebinsua)

------------------------------------------------------------------------

### Summary

I first learnt to program at the age of sixteen after discovering a
flourishing homebrew community. Realising that self-taught amateurs
could create products by themselves was inspiring to me. I’m still
amazed by what can be created by small empowered teams.

Over the years I've worked with many languages within many different
environments. Nowadays I do a lot of commercial work in JavaScript
due to its prevalence but in my spare time I like Rust due to
its mixture of low-level and functional programming.

My software architectures and practices are influenced by: [the
twelve-factor app](http://12factor.net), a [conservative attitude
towards microservices](https://www.tigerteam.dk/2014/micro-services-its-not-only-the-size-that-matters-its-also-how-you-use-them-part-2/), unit testing & TDD, a light sprinkle of functional 
programming, the [Elm Architecture](https://github.com/evancz/elm-architecture-tutorial/),
and [Simple Made Easy](http://infoq.com/presentations/Simple-Made-Easy).

I specialise in combining technical knowledge with lateral thinking.
I particularly like to advise on designs that maximise a businesses
*technical leverage* while also reducing their exposure to *execution costs*.
Knowing when not to solve a problem is as important as knowing how to solve it.

**Technical specialties:** Full-stack software design and
implementation. I follow the mantra *the right tool for the right job* and
try to keep solutions as simple and common as possible.

**Other:** I've run small standups in the past; I also enjoy learning about:
product design, UX, and market analysis; I also ran a Hackathon once.

------------------------------------------------------------------------

### Experience

##### **[~](http://www.momentumlabs.io)** *London, United Kingdom / Remote*
###### **Freelancer** *Jun '13 – Present*

*Freelancing, consulting and open-source activities.*

- [Banking for your command line.](https://github.com/sebinsua/teller-cli) Written in Rust.
- [Access Twitter data without an API key.](https://github.com/sebinsua/scrape-twitter)
- [Quick and easy JSON transformations.](https://github.com/sebinsua/jstruct)
- [An Express.js middleware to allow one-line installation of analytics into Node.JS projects](https://github.com/sebinsua/express-keenio) for the [Sequoia Capital](https://www.sequoiacap.com/) backed startup [Keen IO](http://keen.io). This was a project born out of an idea I suggested as a way of reducing the time-to-setup of their analytics service from multiple hours/days to around 15 seconds.
- Continued work on my app Spokes. Designed with Sketch and programmed using Node, Koa, Redis, the graph database Neo4j, Swift, and ReactiveCocoa as well as a few other Cocoapods.

##### **[YLD](http://yld.io/)** *London*
###### **Node.js Engineer** *Jan '17 – Apr '17*

*YLD is one of London’s fastest growing software engineering consultancies working with European brands such as The Economist, Trainline and Thomas Cook.*

- Code reviews. Troubleshooting framework issues. Implementation of 4 Node microservices.
- Created shared helpers to ensure a set of data exists during test execution.
- Improved the error handling and logging of an in-house microservices framework.
- Wrote a bit of documentation explaining the process of migration between SQLite and MySQL.

##### **[McKinsey & Company](http://www.mckinsey.com/)** *Western Europe*
###### **Full-stack Engineer** *Apr '16 – Dec '16*

*McKinsey & Company is a worldwide management consulting firm.*

- Code reviews. Mentoring. Documentation. Architecture.
- D3. React. Redux. Node.js.
- Wrote a number of open-source projects (e.g. [`redux-saga-helpers`](https://github.com/sebinsua/redux-saga-helpers) and [`react-redux-wizard`](https://github.com/sebinsua/react-redux-wizard)).

##### **[The Economist](http://www.economist.com/)** *London, United Kingdom*
###### **Software Engineer** *Sep '15 – Dec '15*

*The Economist is an English-language weekly newspaper.*

- React. ES6. Node.
- Numerous components (e.g. [`@economist/component-articletemplate`](https://github.com/economist-components/component-articletemplate)) used in [The World In 2016 project](http://www.theworldin.com) and potentially other projects.

##### **[Home Office](https://www.gov.uk/government/organisations/home-office)** *London, United Kingdom*
###### **Contract Technology Lead** *Jan '15 – Sep '15*

*The Home Office is a ministerial department of the Government of the United Kingdom, responsible for immigration, security, and law and order.*

- Rebuilt a sprawling legacy system into 6 Node.js microservices harnessing infrastructure, services and libraries built for the Passport Exemplar project.
- 1 JWT Authentication API with LDAP as its backing service; 1 old-school Express.js front-end app; 1 single-page app built with React + Flux + ES6 (Babel); 2 RESTful Express.js APIs; and 1 command-line app to run tasks on the Postgres database.
- Gave strategic advice on the architecture of a new project, and later presented this plan at ’Show and Tell’ to a wide range of people throughout the organisation.
- Created some early prototypes using Java 8 + Dropwizard + Swagger.

##### **[Red Badger](https://red-badger.com/)** *London, United Kingdom*
###### **Contract Node.JS Consultant** *Mar '14 – Jul '14*

*Red Badger is a creative software workshop.*

- This was a client-facing role in which I provided training to an external team.
- Node.JS, RabbitMQ, Elasticsearch, Redis.

##### **[Hailo](https://hailoapp.com/)** *London, United Kingdom*
###### **Contract JavaScript Engineer** *Sep '13 – Jan '14*

*Hailo is the evolution of the hail – a free smartphone app which puts people just two taps away from a licensed taxi, and lets cabbies get more passengers when they want them.*

- Created a series of single-page dashboard apps. Conversations with internal customers helped me to come up with ideas on how to simplify business processes. For example a way of signing off groups of driver’s profile changes was given a UX that defaulted to approval but forced the user to sign a receipt of the changes: this helps with speed while also ensuring accountability.
- Other components were created so that behaviour relating to presentation was well-separated from configuration and data input; or made so that they could be updated in real-time, for example: an animated map of driver locations.

##### **[BIZZBY](https://bizzby.com/)** *London, United Kingdom*
###### **Senior Node.JS Engineer** *Apr '13 – Jun '13*

*BIZZBY is app your service to help you book a trusted local service in 30 seconds.*

##### **[We R Interactive](http://werinteractive.com/)** *London, United Kingdom*
###### **Team Lead** *Oct '12 – Apr '13*

*We R Interactive blends the best of games, film and TV production to create social games that bring global audiences together around sport and music.*

- Designed and lead the creation of a back-end system to support a sport game as well as recruiting developers for my team.
- The system was decomposed into multiple services and stored data in Cassandra. I created a service which would automatically generate a series of questions from a stream of data and a template, a real-time market-outcome resolution service that would automatically resolve a series of previously generated questions depending on a simple DSL and a stream of real-life data, and a service that could have data pushed to or pulled from it and parse this data into a common format before feeding it into a message queue for deeper processing.
- Setup a continuous integration system using Jenkins, and used Puppet to automate deployment of some of the services to AWS. Later on third-party data issues were reported to stakeholders and dealt with through design chances relating to logging and testing the data quality.

##### **[Saffron Digital](http://saffrondigital.com/)** *London, United Kingdom*
###### **Team Lead** *Oct '10 – Oct '12*

*Saffron Digital is the global, market-leading provider of connected device video, DRM, advertising and platform services. Saffron Digital was acquired by HTC in 2011.*

- Project leader and architect of the HTC Watch project in which I lead a team of five developers. Due to my early work on internationalisation and implementation of multiple payment services we were able to run this globally in close to 20 countries. Later on the project became a baseline for future web services for other clients.
- Significant input in re-engineering development process as we moved from being a startup to a larger company. For example: an engineer empowering company culture; Git instead of SVN; continuous integration; modern deployment tools; etc.
- Architecture and development of a new platform based on understandings gleaned from previous services. Worked on service to orchestrate and configure encoders in order to run encodes in parallel on AWS.
- A client-side application for Samsung Connected TVs and set-top boxes written in object-orientated JavaScript.

###### **PHP Developer** *Feb '10 – Oct '10*

- A RESTful web service for FOX to support a fully localised Family Guy video streaming Android application. A CMS was also created as well as reporting tools to give the business metrics to measure activity.
- A web service for Paramount Studio’s the League of Extraordinary Dancers iPhone Application. This was interoperable with the iTunes video store in order to check receipts.

*Please refer to [my Linkedin profile](http://www.linkedin.com/in/sebinsua) for the complete list of work experiences along with recommendations.*

------------------------------------------------------------------------

### Education

##### **Coursera** *Online*
###### **Machine Learning** *Feb '16*

- [Course Certificate, License E3XLGER56CQ3](https://www.coursera.org/account/accomplishments/verify/E3XLGER56CQ3)

##### **University of Kent** *Canterbury, United Kingdom*
###### **Bachelor’s degree in Computer Science** *2005 – 2009*

- Courses included Computer Systems and Algorithms, Data Structures and Complexity, Data Mining and Knowledge Discovery, Operating Systems and Architecture, Software Engineering Practice, Database Systems, and Distributed Systems and Networks.
- While studying here I also coordinated and guided a team of four developers creating a DJ mixing application in Java for my final project.

##### **Cranbrook School** *Cranbrook, United Kingdom*
###### **GCSEs & A-Levels** (secondary education) *2000 – 2005*

------------------------------------------------------------------------

### Interests

Design, Economics, Philosophy, Poetry.
