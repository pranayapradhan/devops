"# devops" 
DevOps Fundamentals and Prerequisites
1. DevOps Fundamentals and SDLC
1.1 What Is DevOps?
DevOps is a culture and set of practices that improve an
organization's ability to deliver applications.
It focuses on improving software delivery through:
Automation
Quality assurance
Monitoring
Testing
Continuous integration and continuous delivery
In summary: DevOps improves application delivery by combining
automation, quality practices, continuous monitoring, and continuous
delivery.
1.2 Why DevOps?
Traditional approach
Previously, application delivery often involved separate teams and many
manual processes:
---
Role                                Responsibility
---
System Administrator                Creates and manages servers
Build and Release Engineer          Builds, releases, and deploys
applications
Modern DevOps approach
Today, DevOps practices bring development and operations processes
closer together. Automation helps teams deliver applications faster and
more reliably.
Typical workflow:
``` text
Developer (Application)
        |
        v
DevOps (Build, Test, Deploy)
        |
        v
Production (Customer)
```
1.3 SDLC (Software Development Life Cycle)
The Software Development Life Cycle (SDLC) describes the stages involved
in planning, building, testing, and delivering software.
Planning --- Gather and understand user requirements.
Defining --- Document requirements and project scope.
Designing --- Create the high-level design (HLD) and low-level
design (LLD).
Building --- Develop the application.
Testing --- Perform quality assurance (QA), functional testing,
and server/environment testing.
Deployment --- Release the application to production for
customers.
---
2. Prerequisites and Virtual Machines
2.1 Roles in a Company
---
                            \# Role                  Responsibility
---
                             1 **Business Analyst    Gathers and analyzes
                               (BA)**                end-user
                                                     requirements.

                             2 **Product Manager**   Defines the product
                                                     vision, goals, and
                                                     priorities.

                             3 **Product Owner       Manages the product
                               (PO)**                backlog and creates
                                                     an action plan for
                                                     prioritizing work.

                             4 **Solution / Software Designs the technical
                               Architect**           structure of the
                                                     system and selects
                                                     suitable technologies
                                                     and frameworks.

                             5 **Developers**        Build the product,
                                                     including the user
                                                     interface (UI), APIs,
                                                     and database
                                                     integrations.

                             6 **QA Engineers**      Test the product's
                                                     quality,
                                                     functionality, and
                                                     performance.

                             7 **Database            Designs, manages,
                               Administrator (DBA)** secures, and
                                                     maintains databases.

                             8 **DevOps Engineer**   Builds CI/CD
                                                     pipelines and manages
                                                     development, testing,
                                                     and production
                                                     environments.

                             9 **Release Manager     Plans, coordinates,
                               (Optional)**          and manages software
                                                     releases.

                            10 **Site Reliability    Ensures service
                               Engineer (SRE)**      availability,
                                                     performance, and
                                                     reliability,
                                                     including after
                                                     releases.

                            11 **Technical Writer**  Creates documentation
                                                     for users and
                                                     developers.
---