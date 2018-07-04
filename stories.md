# General Interview Questions

### About yourself
  - Arc: 
    - Curious and Adaptable | Sponge
    - Highly rewarded as Software Engineer
    - Languages | International Experience | Python
    - Javascript | Full Stack | Back-end system design puzzles
    - Project Manager | Communication and Collaboration
    - I'm really excited about joining a forward looking engineering team 
    - tackle juicy engineering challenges, and help steer an impactful product
    - domain agnostic


    - Realization about technology | New problem spaces
    - Team Software Engineers to steer product

  - Long form
    - At a fundamental level I'm just a really curious and adaptable person. I've been described as sponge like by friends and family because I love to seek out new environments and soak up everything I can. What I love about being a software engineer is that these traits are so highly rewarded.
    - I came to programming through a love of languages, I used to live and work internationally and I picked up a few foreign languages like Hindi and a bit of Japanese, and I started teaching myself Python as a hobby to understand what computer languages were. 
    - That turned into a deeper study of JavaScript and building full stack web applications. I basically got hooked on the creative joy in building things, particularly the back end system design puzzle and tradeoffs. (optimizing databases, horizontal scaling)
    - I also kind of had a realization about technology, that it isn't about gadgets necessarily, but that technology is actually about knowledge and building off prior knowledge and using automation to abstract away things to free up mental space for tackling new problem spaces. 
    - In my previous life I was a project manager as well, so I appreciate the value in communication, collaboration, and understanding different stakeholders. 
    - Really just looking to contribute to a team of software engineers to help steer a great product to market.

### Five Whys
- Before, Now, Future 
- Tech 

### Greatest Strength
  - List: Communicator, Curious, Adaptable, Patient
  - Ideas: 
    - Communicator
      - Thoughtful communicator who tends to work well with others, it sounds like a simple thing, but oddly it is a hard one to teach so I think I lucked out on that. Most other things are teachable. 
      - It is beneficial across domains, in an engineering team it amplifies what you can learn.
    - Curious 
      - I'm always looking around the corner, wanting to keep going, see what is next. That I think has made me a great learner and helped me to push beyond where other people might otherwise stop. But it is important to be aware of that too. You have to ship! 
    - Adaptable
      - It isn't always comfortable, but it is a natural tendency of mine to go outside of my comfort zone. I grew up on the central coast, so I went to school in New York, I then moved to India and picked up Hindi and founded a school, I then moved to Osaka. Then I decided to switch careers and teach myself to code and become a software engineer. 
      - It has trained me to adapt to lots of different environments and find ways to be successful. 
      - Don't give up easily
    - Patient and like to look at all sides of a problem
      - I think this is a fundamental analytical skill
      - I always try to consider a problem from all sides, hesitant to just go with my first idea, but rather a lot of creativity comes out of examining your second and third ideas. Pixar story. 
  
### Greatest Weakness
  - List: Questions, Perfectionist
  - Ask a lot of questions
    - The reason I do it is because it helps me train my mental model by constantly challenging it
    - Important for me to keep it in check by batching questions, and it is important for me to not bother people with too many questions
    - I enjoy working with others so it comes naturally to me, but maybe not so to other people which I respect
  - Perfectionism, I don't mean this to be a weakness disguised as a strength, I consider perfectionism to absolutely be a weakness. It can be paralyzing and counterproductive. So not letting the perfect be an enemy of the good is something I have to keep in the forefront of my mind. 

### What is your dream job?
  - I'm a really values driven person and I also seek out intellectual rewards for fulfillment. I tend to be really excited be ideas and technology that I feel has a positive social impact or potential, or that is otherwise just otherwise undeniably compelling. 
  - That said, at this stage I'm domain agnostic, but really interested to work with progressive technology
  - This is cliche, but in this space if you aren't ahead of the curve you are behind it, so I am ideally looking to join a software engineering team that is pushing tech forward and where the engineers have some creative impact on steering the product.
  - I'm also inspired by potential, and working on products where you don't even quite know what it is yet, and teams are still looking for the edges of what their ideas can accomplish. 

### Fit for this company?
  - Name things I like about this company
  - Answer with my dream job
  - Like how they distinguish themselves in a crowded market

### Technical Strengths and Interests
  - Love writing beautiful code
    - modular and readable
  - Love seeing the full stack
    - From front end MVC frameworks
    - API layers and servers
    - databases and caching systems
    - Dockerizing and deploying
    - Architecture and optimization work is conceptually what gets me excited
  - Particularly strong with JavaScript
  - Interested in Data Science, Python machine learning, creative AI
  - Love thinking about data flow
  - Scribe v conjurer, 80 20 rule

### Technical Weaknesses and Goals
  - High interest but need more experience with dev ops
  - Want more exposure to horizontal scaling, deployment with AWS
  - Some exposure and reading with Kubernetes, Docker swarm, Amazon ECS, dynamic scaling, data persistence with EBS volumes, etc. 

### Recent project
  - Two come to mind, give you a quick overview and happy to drill down further.
  - Marzagat - System Design Decisions
    - Restaraunt reviews | my microservice
    - Inherit Front End | Gut Backend
    - Optimize Query Performance | Benchmark DBs 12s -> 1ms
    - Stress Test with Artillery and New Relic (middle ware removal) for throughput
    - Implement Redis cache to bring avg latency down 30%
    - Server side rendering for SEO and ttfb 50 ms
    - Dockerize, deploy on AWS EC2, with EBS volumes 
  - Creator's Block
    - MVP stage creative writing assistant tool 
    - inspired by creative AI projects i've seen
    - Predictive Text Emulation engine with markov chain
    - What it does, shakespeare example
    - Lots of fun ideas about where to go with it

# Project Specific Questions

### Challenges
  - 1) Optimizing Schema
    - Problem: Inherited a schema, need to optimize for web scale, optimize core query performance
      - initially was at 12 seconds
    - Action:
      - index
      - remove redundancies
      - identify unnecessary data
      - denormalizaiton
    - Result: 
      - improved read time to less than 1ms
    - Also benchmarked against PostgreSQL

  - 2) Increasing Throughput 
      - Stress test
      - Remove middleware
      - Implement redis cache

  - 3) SSR 
      - Bug


  - SDC Schema Design and Optimization | Inheriting Front End
  - Mongo, redundancy, denormalization, unnecessary information

  - SDC Optimize for webscale 
    - Seed to 10M
    - Isolate DBs
    - Stress test for throughput
    - Implement redis cache
    - SSR
    - Configure for EC2
  - SDC Server side rendering bug with Google Maps React
  - FEC Optimal way to fetch data 
  - FEC Designing components for lightbox
  - FEC Defining clear component contracts, jest and enzyme
    - shallow rendering, snapshots
  - MVP Storing parsed source text in memory, data structure

### Mistakes and Failures || What I would do Differently
  - SDC Attempting to adjust Front End prematurely, better to tune backend first and maintain API
  - SDC recognizing value of denormalized data
  - FEC jQuery toggling, but spagetthi code, React better
  - MVP put the logic in the component itself, need to separate it out

### Toughest Bug
  - SSR Bug with Google Maps React 
    - changed to another library
  - Problem: 
    - Multiple subcomponents that should have been rendering, but they were not
    - Was working previously
  - Action:
    - Looked into the error messages, reference attribute error in React,
    - Had to dig through the react package 
  - Result:
    - Switched libraries 

### Enjoyed
  - Identifying areas to make abstract
  - Finding ways to optimize throughput 
  - Configuring as docker containers and using docker compose up
  - Designing an API
  - Wireframing React components
  - Seeing the full stack, durable, scalable, modular

### Leadership
  - Coordinating and anticipating for proxy server
  - Helping a more solo team member stay integrated
  - Forge ahead of team examine Dockerizing, SSR, deployment
  - Founded a night school education program, Manager at a Consulting Company

### Conflicts
  - Style guide conversations (airbnb linter versus not)
    - some people were lazy or resistant to things
    - walk through the advantages 
  - Standardizing server side rendering approach (next versus not)
    - looked briefly into it, next seems good but requires you to use particular architecture
    - abstracts away a lot of the difficulty
  - Choosing to use Docker or not, made up pros and cons list, brought everyone together
    - easy spin up and use
    - extra configuration
    - people just hadn't used it before
    - forged ahead and made suggestions
  - Interesting discussions about where to pass in 
  



