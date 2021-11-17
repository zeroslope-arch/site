## ZeroSlope Platform

About 8 years ago, I started working on a .net scaffold specifically around my Dependency Injection Composition Root pattern. I wanted to create super lean and performant scaffold I could drop into a new project and get running quickly. It evolved into a way to introduce other engineers to Composition Root. What I discovered during this phase, was how approachable the pattern was to engineers of most any skill level. I decided to pivot my scaffold to focus on two main principals; Lean Architecture & Developer Adoption.

To avoid analysis paralysis and ensure what I was developing would stay true to the idea I had in my head, I came up with a series of Tenants that I can always look back on and make sure I am making the right architectural decisions.

### The Tenants of ZeroSlope

1) Developer Focused: Developer quality of life is the largest focus of the pattern. When at a crossroads on a design pattern, whichever leans closer to developer maintainability should win.
2) Developer Adoption: The pattern and processes should lend to developers of all skill levels to work within it. The more comfortable or skillful the developer, the deeper into the stack they can work.
3) Lean and Clean: The pattern should have minimal abstraction that does not remove the need to repeat configuration, or repeat code usage. ie: The pipeline should always be abstracted away from everyday developer use. No code should live within controllers other than service method calls. When possible, use nuget/npm packages to remove redundant framework setup.
4) Simple Composition: The framework is made up of Pipeline, Controllers, Services, and (not always) Composition Root. As part of #3, this framework should be lean and be familiar to developers as they onboard into the framework.
5) Language Agnostic: Aside from language specific requirements, a developer should be able to move from Java ZeroSlope to Node ZeroSlope to .net Core ZeroSlope. They should find the general structure and naming conventions to be familiar which will boost developer confidence and velocity.


### Lean Microservice Architecture

todo

### Developer Adoption

todo

### Switching Technologies

If an engineer was working on the Java variant of ZeroSlope, and needed to work on a .net project with little to no experience in .net, hopefully the platform would provide a jumping-off point to get the engineer comfortable quickly.


### Self Promotional Architecture

One concept I really wanted to focus on with this platform was the idea that the architecture would encourage engineers to learn at their own page. I want engineers to be able to dive as deep into the pattern as they feel comfortable.


### Holistic Platform

todo

### Language Agnostic

todo

### Cloud Agnostic

todo

### Configurable Solution Generation

todo
