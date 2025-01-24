# Dolph Mathews

![Lint](https://github.com/dolph/cv/actions/workflows/markdown-lint.yml/badge.svg)
![Links](https://github.com/dolph/cv/actions/workflows/markdown-links.yml/badge.svg)

I am a highly experienced software engineer with a passion for automating
solutions and creating reliable, intuitive systems. My background includes
developing web applications, web services, and commandline tools. I enjoy
writing tests, publishing documentation, and optimizing processes.

- Email: [dolph.mathews@gmail.com](mailto:dolph.mathews@gmail.com)
- GitHub: [github.com/dolph](https://github.com/dolph/)
- LinkedIn: [Profile](https://www.linkedin.com/in/dolphmathews/)
- Location: Remote (USA)

## Education

### University of Texas at Austin (2005 &mdash; 2009)

Bachelor of Science, **Electrical & Computer Engineering**

## Experience

### *Lead Reliability Engineer*, IBM Quantum (2023 &mdash; present)

As IBM Quantum has grown in maturity from a research project to a
publicly-accessible product offering, I've advocated for the reliability of our
software services to become a key objective for the organization. I established
a reliability practice within the organization, leading the use of Grafana as a
broadly accessible tool for observability of system metrics and near-realtime
debugging of internal components for development teams and internal users
alike.

I measured and led the improvement of Quantum's job success rate year over year
from 96.17% in 2023 to 99.30% in 2024, and demonstrated that we can maintain a
job success rate as high as 99.85% over a 7-day period. I also discovered and
measured an internal system efficiency metric, and drove it up from 50.4% when
I first measured it in June 2023, to >90% in Q4 2024. These two achievements
have unlocked tens of millions of dollars of quantum compute capacity that was
otherwise being lost.

I formalized 24/7 incident management policies and organized a volunteer team
of subject matter experts to respond to software incidents within the
organization. By driving improvements through alerting, I reduced our Mean Time
to Detect customer impacting events from 368 minutes in 2023 to 58 minutes in
2024. This team also achieved a Mean Time to Acknowledgement of all SEV-1
incidents in 2024 of 9 minutes 10 seconds, which was previously estimated in
terms of hours. As a result, this team directly helped improve our US service
availability year over year from 97.0% in 2023 to 98.8% in 2024.

Core technology stack: [Grafana](https://grafana.com/),
[PostgreSQL](https://www.postgresql.org/), [Sysdig (statsd,
Prometheus)](https://sysdig.com/), [LogDNA](https://www.logdna.com/),
[Jaeger Tracing (OpenTelemetry)](https://www.jaegertracing.io/),
[PagerDuty](https://www.logdna.com/)

Primary development tools: [vim](http://www.vim.org/),
[git](https://git-scm.com/), [GitHub](https://www.github.com/),
[Fedora](https://getfedora.org/)

### *Technical Lead, Infrastructure*, IBM Quantum (2021 &mdash; 2023)

As Technical Lead for a team of 10+ engineers, I am responsible for
prioritizing the classical infrastructure work required to deploy and maintain
Quantum hardware at 9 physical sites, the surrounding compute infrastructure,
and the cloud services fronting them. We maintain dozens of
Kubernetes/OpenShift clusters, and hundreds of baremetal devices. The scope and
scale of the team's responsibilities would not be possible to manage without a
heavy reliance on automation, primarily using Ansible and Terraform.

My team supports hundreds of software engineers and researchers continuously
developing, deploying, and operating dozens of applications in multiple
environments. Our primary challenge is keeping up with rapidly evolving
business goals by helping prototypes mature into reliable production services.

Core technology stack: [Ansible](https://www.ansible.com/), [Concourse
CI](https://concourse-ci.org/), [Red Hat Enterprise Linux 8
(RHEL8)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux),
[Dell iDRAC](https://www.dell.com/en-us/dt/solutions/openmanage/idrac.htm),
[bash](https://www.gnu.org/software/bash/), [YAML](http://yaml.org/), [Sysdig
(statsd, Prometheus)](https://sysdig.com/), [LogDNA](https://www.logdna.com/),
[PagerDuty](https://www.logdna.com/), [Terraform](https://www.terraform.io/),
[Atlantis](https://www.runatlantis.io/), [Python 3](https://www.python.org/),
[TravisCI](https://travis-ci.org/)

Primary development tools: [vim](http://www.vim.org/),
[git](https://git-scm.com/), [GitHub](https://www.github.com/),
[Fedora](https://getfedora.org/)

### *Senior DevOps Engineer*, IBM Quantum (2019 &mdash; 2022)

As part of [IBM Quantum](https://www.ibm.com/quantum-computing/), I am
responsible for the entire lifecycle of backend infrastructure running both
production and research & development workloads.

I have led the deployment automation effort for all backend Linux systems,
which was previously done manually from docs with a handful of bash snippets to
a variety of different hardware configurations, operating systems, and
platforms. After I converted all available documentation to Ansible playbooks,
which I tested in Vagrant & VirtualBox, I helped standardize hardware and
operating system configuration by automating the provisioning process from
baremetal. I later introduced Concourse CI to provide a continuous integration
and continuous deployment platform, meeting business needs across multiple
geographically-distributed private networks while delivering changes across all
production devices multiple times per day without human intervention.

I have led the modernization of monitoring and alerting from backend
infrastructure from local log files to centralized logging via LogDNA, system
monitoring via Sysdig (which is built on Prometheus and `statsd`), and alerting
via PagerDuty.

I have also led the full operations lifecycle of geographically distributed Red
Hat OpenShift/Kubernetes clusters from baremetal and virtualized provisioning
to running clusters as part of [IBM Cloud
Satellite](https://www.ibm.com/cloud/satellite), primarily for neartime quantum
compute workloads.

- *Squad Lead*: As squad lead, I run daily standups, weekly backlog grooming,
  biweekly retrospectives, and biweekly sprint planning for a team responsible
  for backend infrastructure and Quantum control systems software. I also have
  worked to help other teams adopt agile practices.

- *Security Owner*: As security owner for almost all baremetal Linux systems in
  IBM Quantum, I leverage our continuous deployment capability to rapidly
  improve our security posture, mitigate and resolve vulnerabilities, and
  manage authorization for internal users.

Core technology stack: [Ansible](https://www.ansible.com/), [Concourse
CI](https://concourse-ci.org/), [CentOS 7](https://www.centos.org/), [Red Hat
Enterprise Linux 8
(RHEL8)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux),
[Dell iDRAC](https://www.dell.com/en-us/dt/solutions/openmanage/idrac.htm),
[bash](https://www.gnu.org/software/bash/), [YAML](http://yaml.org/), [Sysdig
(statsd, Prometheus)](https://sysdig.com/), [LogDNA](https://www.logdna.com/),
[PagerDuty](https://www.logdna.com/), [Terraform](https://www.terraform.io/),
[Python 3](https://www.python.org/)

Primary development tools: [vim](http://www.vim.org/),
[git](https://git-scm.com/), [GitHub](https://www.github.com/),
[Fedora](https://getfedora.org/), [Vagrant](https://www.vagrantup.com/),
[VirtualBox](https://www.virtualbox.org/)

### *Senior Developer Advocate*, IBM Developer (2017 &mdash; 2019)

As part of [IBM Developer](https://developer.ibm.com/), I worked on a team
responsible for creating and managing developer advocacy content such as
tutorials, articles, and code patterns covering topics including IBM Watson and
IBM Cloud. A code pattern is an open source example demonstrating how
developers can leverage specific IBM services in their projects and are
presented by developer advocates in labs, workshops, and presentations.

Several of my accomplishments with IBM Developer focus on allowing a small team
of developer advocates to build, deliver, and maintain thousands of pieces of
technical content spread across hundreds of git repositories in a scalable
manner. For example:

- automatically identifying and updating broken and outdated links,
- building a tool to interactively validate Markdown frontmatter in YAML (using
  JSON Schema),
- automating the conversion of a legacy documentation format (XML to Markdown),
- updating branding of IBM products and services, and
- writing Selenium tests to exercise previously-untested workflows in the IBM
  Cloud console.

> Dolph has gone out of his way to help the editorial team with several special
  projects. His help has been invaluable and has saved our team hours of work.
  He's streamlined and updated processes to make tools easier to use and to
  offload work from us. &mdash; Jill Amaya

I was also entrusted to serve as an administrator of IBM's open source presence
on GitHub, [github.com/IBM](https://github.com/ibm/), managing the creation of
open source projects and the integration with 3rd party services.

Core technology stack: [Python](https://www.python.org),
[bash](https://www.gnu.org/software/bash/), [JSON](http://www.json.org/),
[YAML](http://yaml.org/),
[Markdown](https://daringfireball.net/projects/markdown/syntax), [JSON
Schema](https://json-schema.org/)

Primary development tools: [vim](http://www.vim.org/),
[git](https://git-scm.com/), [GitHub](https://www.github.com/),
[TravisCI](https://travis-ci.org/), [Ubuntu Linux](https://www.ubuntu.com/)

### *Principal Software Engineer*, Rackspace (2011 &mdash; 2017)

At [Rackspace](https://www.rackspace.com/), I worked as an open source
[Python](https://www.python.org/) developer on a globally distributed team in
the [OpenStack](https://www.openstack.org/) community. After being hired as a
**Software Engineer**, I was promoted to **Principal Engineer** in November
2014.

During that time, I became a core contributor of [OpenStack
Keystone](http://github.com/openstack/keystone), the identity service for
OpenStack-based clouds, and I was subsequently elected by my peers as the
Project Technical Lead (PTL) and a member of the [OpenStack Technical
Committee](https://www.openstack.org/foundation/tech-committee/) (TC). Later, I
helped launch the OpenStack Innovation Center (OSIC), a joint partnership
between [Rackspace](https://www.rackspace.com/) and [Intel](https://01.org/),
as a technical lead and cross-project liaison. I also helped lead the broader
OpenStack technical strategy at Rackspace via the OpenStack Technical
Leadership Team and the Rackspace Private Cloud architecture group.

Reviewing code from other contributors was one of my most satisfying endeavors.
In the early days of OpenStack, I helped kickstart OpenStack's code review
discipline via [Gerrit](https://www.gerritcodereview.com/). Since then, I've
strived to provide other contributors with high-value constructive criticism,
with an eye towards fostering the community of new contributors, core
reviewers, and technical leads both within Rackspace and beyond.

I developed a rigorous appetite for a documentation-first approach (which
pushes developers to think through the user experience before diving into an
implementation), thorough automated testing (particularly important when
working with thousands of fellow technical contributors), and comprehensive
continuous integration (from `git push` to shipping release artifacts).

- *[Project Technical
  Lead](https://docs.openstack.org/project-team-guide/ptl.html)*: As PTL, I
  coordinated weekly team meetings via
  [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat), conducted [thousands
  of code
  reviews](https://www.stackalytics.com/?release=all&project_type=all&user_id=dolph)
  via [Gerrit](https://www.gerritcodereview.com/), triaged hundreds of issues
  via [LaunchPad](https://launchpad.net/keystone), and fostered & mentored a
  team of [core
  reviewers](https://docs.openstack.org/doc-contrib-guide/docs-review.html)
  from among dozens monthly active contributors in our open source community.

- *[Technical Committee](https://governance.openstack.org/tc/)*: As a TC
  member, I helped to govern the OpenStack community's structure, principles,
  values, scope, goals, and licensing.

- *[Stable Maintenance team
  member](https://docs.openstack.org/project-team-guide/stable-branches.html)*:
  As a stable maintenance team member, I was responsible for code reviewing
  commits, backporting patches via cherry picks, and producing tagged releases
  of stable branches.

- *[Vulnerability Management team
  member](https://security.openstack.org/vmt-process.html)*: As a vulnerability
  management team member, I was responsible for triaging, reproducing,
  documenting (via [CVE](https://cve.mitre.org/) processes), and patching
  vulnerabilities on supported stable branches.

Core technology stack: [Python](https://www.python.org),
[bash](https://www.gnu.org/software/bash/), [JSON](http://www.json.org/),
[YAML](http://yaml.org/), [Ansible](https://www.ansible.com/),
[MySQL](https://www.mysql.com/), [memcached](https://memcached.org/)

Primary development tools: [vim](http://www.vim.org/),
[git](https://git-scm.com/), [LaunchPad](https://launchpad.net/~dolph),
[Trello](https://trello.com/), [Gerrit](https://www.gerritcodereview.com/),
[Jenkins](https://jenkins.io/),
[Wercker](https://devcenter.wercker.com/overview-and-core-concepts/wercker-features/),
[TravisCI](https://travis-ci.org/), [Debian Linux](https://www.debian.org/),
[Ubuntu Linux](https://www.ubuntu.com/), [OS X](https://www.apple.com/macos/)

### *Software Engineer*, Akimeka (2009 &mdash; 2011)

At [Akimeka](http://www.akimeka.com/), I worked on a project for the Department
of Defense (DoD) Defense Healthcare Management System (DHMS) while holding a
Secret security clearance.

Core technology stack: [Java
EE](http://www.oracle.com/technetwork/java/javaee/overview/index.html),
[XML](https://en.wikipedia.org/wiki/XML), [JBoss
AS](https://en.wikipedia.org/wiki/WildFly) (now known as
[WildFly](http://wildfly.org/)), [JBoss
Seam](https://en.wikipedia.org/wiki/JBoss_Seam), [JavaServer
Faces](https://en.wikipedia.org/wiki/JavaServer_Faces) (JSF),
[Hibernate](http://hibernate.org/orm/), [Oracle
SQL](http://www.oracle.com/technetwork/database/), [XML-based
sneakernet](https://en.wikipedia.org/wiki/Sneakernet)

Primary development tools: [Eclipse](https://eclipse.org/), [IntelliJ
IDEA](https://www.jetbrains.com/idea/), [Perforce](https://www.perforce.com/),
[FogBugz](https://www.fogcreek.com/fogbugz/), [Code
Collaborator](https://smartbear.com/product/collaborator/overview/),
[Windows](https://www.microsoft.com/en-us/windows/)

## Side projects

I've had many more side projects, but this is a handful I enjoy talking about.

- [find-replace](https://github.com/dolph/find-replace): A fast find & replace
  shell command written in Go.

  Core technology stack: [Go](https://go.dev/)

- [dotfiles](https://github.com/dolph/dotfiles): I've been version controlling
  my desktop configuration files since 2013, across operating systems (OS X,
  Ubuntu Linux, and Fedora Linux), and across multiple desktop environments
  (Gnome, Xfce and i3). I now use Ansible to keep configuration across multiple
  workstations in sync.

  Core technology stack: [Ansible](https://www.ansible.com/),
  [bash](https://www.gnu.org/software/bash/)

- [github.com/dolph/recipes](https://github.com/dolph/recipes): I love to cook,
  and I version control my recipe collection.

  Core technology stack: [Github-flavored
  Markdown](https://guides.github.com/features/mastering-markdown/)

- [git-ready](https://github.com/dolph/git-ready): I found OpenStack's Gerrit
  workflow to be a little cumbersome and (ironically) anti-social, so I built a
  [Python](https://www.python.org/)-based CLI tool to eliminate that pain and
  promote positive social interactions.

  Core technology stack: [Python
  2](https://www.python.org/download/releases/2.0/),
  [bash](https://www.gnu.org/software/bash/)

- [pasteraw](http://github.com/dolph/pasteraw): Frustrated by slow pastebin
  services with poor CLI support, I built a fast, lightweight plaintext
  pastebin service that pushes content directly to a CDN-enabled object store.
  A few members of the OpenStack community adopted it, as well. Pastes are
  still available today via CDN, but the frontend has been shutdown.

  Core technology stack: [Python
  2](https://www.python.org/download/releases/2.0/),
  [Flask](https://flask.palletsprojects.com/en/2.0.x/), [OpenStack Swift
  (Object
  Storage)](https://docs.rackspace.com/docs/user-guides/infrastructure/cloud-config/storage/cloud-files-product-concepts/object-storage)
  [Vagrant](https://www.vagrantup.com/)

- [poker-hand-evaluator](https://github.com/dolph/poker-hand-evaluator): I
  found that evaluating and comparing poker hands to be an incredibly
  interesting and multifaceted problem. As a fun exercise, I built a command
  line tool in [Go](https://golang.org/), mostly using bitwise operations, to
  efficiently identify the best 5-card poker hand of a 7-card set. The result
  is a unique integer that represents the strength of the hand, allowing the
  hand to be compared to other 5- and 7-card hands to determine a winner.

  Core technology stack: [Go](https://go.dev/)
