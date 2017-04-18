# Dolph Mathews

- Email: [dolph.mathews@gmail.com](mailto:dolph.mathews@gmail.com)
- Twitter: [@dolphm](https://twitter.com/dolphm)
- Blog: [dolphm.com](http://www.dolphm.com/)
- LinkedIn: [Profile](https://www.linkedin.com/in/dolphmathews/)
- GitHub: [github.com/dolph](https://github.com/dolph/)

## Rackspace (June 2011 &mdash; present)

At [Rackspace](https://www.rackspace.com/), I worked as an open source Python developer in the OpenStack community. I was rapidly promoted to Software Engineer V, and then advanced to Principal Engineer in November 2014.

During that time, I become a core contributor of [OpenStack Keystone](http://github.com/openstack/keystone), the identity service for OpenStack-based clouds, and I was subsequently elected by my peers as the Program Technical Lead (PTL) and a member of the OpenStack Technical Committee (TC). Later, I helped launch the [OpenStack Innovation Center](https://osic.org/), a joint partnership between Rackspace and Intel, as a technical lead and cross-project liaison. I also helped lead the broader OpenStack technical strategy at Rackspace via the OpenStack Technical Leadership Team and the Rackspace Private Cloud architecture group.

In the early days of OpenStack, I helped move the the OpenStack community from a traditional GitHub-based workflow to performing code reviews via Gerrit. Since then, I've strived to provide other contributors with high-value constructive criticism, with an eye towards fostering new contributors, core reviewers, and technical leads both within Rackspace and beyond.

I developed a rigorous appetite for a documentation-first approach (which pushes developers to think through the user experience before diving into an implementation), thorough automated testing (particularly important when working with thousands of fellow technical contributors), and comprehensive continuous integration (from `git push` to shipping release artifacts).

- Core technology stack:
  - Languages & data formats: Python, bash, JSON, YAML
  - Deployment automation: Ansible
  - Data stores: memcache, MySQL, LDAP
  
- Development tools:
  - Editor: vim
  - Version control: git
  - Issue management: LaunchPad, Trello
  - Code review: Gerrit
  - Continuous integration: Jenkins, Wercker, TravisCI

## Akimeka (June 2009 &mdash; May 2011)

At [Akimeka](http://www.akimeka.com/), I worked as a software engineer for the Department of Defense (DoD) Defense Healthcare Management System (DHMS) while holding a Secret security clearance.

- Core technology stack:
  - Languages & data formats: Java EE, XML
  - Application server: JBoss
  - Application framework: JBoss Seam
  - Interface framework: JavaServer Faces (JSF)
  - ORM: Hibernate
  - Data store: Oracle SQL, XML-based sneakernet

- Development tools:
  - IDE: Eclipse
  - Version control: Perforce
  - Issue management: FogBugz
  - Code review: Code Collaborator

## Side projects

- [git-ready](http://dolphm.com/git-ready/): I found OpenStack's Gerrit workflow to be a little cumbersome and (ironically) anti-social, so I built to a tool to eliminate that pain and promote positive social interactions.

- [github.com/dolph/recipes](https://github.com/dolph/recipes): I love to cook, and I manage my recipe collection with version control nearly every day.

- [pasteraw](http://pasteraw.com/): Frustrated by slow pastebin services with poor CLI support, I built an incredibly fast, lightweight plaintext pastebin service that pushes content directly to a CDN-enabled object store.

- [@SteamyDeals](https://twitter.com/steamydeals): As a PC gamer, I found it difficult to keep up with [Steam's](http://store.steampowered.com/) frequent sales, deep discounts, and rapidly expanding product catalog, so I built a bot to identify and track highly-rated, popular games, and send notifications only when those products reach their best prices. On the backend, it features a full CI/CD pipeline that deploys a serverless PaaS-based architecture (utilizing application containers, message queues, and a fully-managed SQL service) from just a `git push`.

- [hyperf](https://github.com/dolph/hyperf) (unfinished): Faced with a need for the statistical analytics of [ApacheBench](https://httpd.apache.org/docs/2.4/programs/ab.html), the need for more flexibility in building HTTP requests, and a desire to generate as much concurrency as possible, I picked up [Rust](https://www.rust-lang.org/) and set out to write a modern command line tool for measuring HTTP performance.

- [poker-hand-evaluator](https://github.com/dolph/poker-hand-evaluator): I found that evaluating and comparing poker hands to be an incredibly interesting and multifaceted problem. As a fun exercise, I built a command line tool in [Go](https://golang.org/), mostly using bitwise operations, to identify the best 5-card poker hand out from a 7-card set. The result is a unique integer that represents the strength of the hand, allowing the hand to be compared to other 5- and 7-card hands to determine a winner.
