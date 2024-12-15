# software-architecture-patterns-for-developers

A linked in learning course https://www.linkedin.com/learning/software-architecture-patterns-for-developers/

Notes:
Pattern Example: The best example of Try Parse Pattern is int.TryParse() in .NET

int z=0;
if(int.TryParse(input,out z))
//code if input is int
else
//returns z false
//means the input is not int; can't parse
Categories of Architecture Patterns (as per the tutor):
i. Application Landscape: Help us create a single application that us used by the enduser/another application. The application can consist multiple applications behind the scenes.
This will be hidden from the enduser.
Types:

1. Monolith
2. N-tier
3. Service-oriented
4. Microservices
5. Serverless
6. Peer-to-peer

ii. Application Structure: Design an individual applications. This pattern explains how a single executable should be built. So, it is a structure of a single executable or a part of a larger application.
Types:

1. Layered
2. Microkernel
3. Command Query Responsibility Segregation (CQRS)
4. Event sourcing
5. Command Query Responsibility Segregation and event sourcing combined

iii. User interface pattern: How the user interacts with the application itself. These could be regarded as a mere software design patterns, but consist of multiple components and they can define a large part of an application.

Types:

1. Model-View-Controller (MVC)
2. Model-View-Presenter (MVP)
3. Model-View-ViewModel (MVVM)
