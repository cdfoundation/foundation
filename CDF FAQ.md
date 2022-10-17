# CDF FAQ

## What is Continuous Delivery (CD)?

CD is a software engineering approach in which teams produce software in short cycles, ensuring that the software can be reliably released at any time. The rise of microservices, cloud native architectures has caused a corollary rise in continuous delivery practices. This is related to CI/CD that includes Continuous Integration (CI) -- the practice of merging all developer working copies to a shared mainline several times a day.

## What is being announced?

The Continuous Delivery Foundation (CDF) is a new, neutral organization that will grow and sustain an open continuous delivery ecosystem. It will provide unified governance and vendor-neutral stewardship, as well as oversight of funding and operations. The first projects of the CD Foundation are Jenkins, Jenkins X, Spinnaker, and Tekton.

## Why did the CD community form the foundation? Why is it needed?

There is a strong need across the industry to collaborate on defining industry specifications around pipelines, workflows and other CI/CD areas, as well as provide foundational support for CI/CD tools. For example, the Jenkins community is seeking a "full service" foundation to host Jenkins (one of the most popular CI/CD projects) and build a platform for increased collaboration. There is also a desire for an industry-wide neutral DevOps/CD conference.

## Does this represent a shift in the cloud native ecosystem?

Yes, the market has shifted to containerized and cloud native technologies, so the ecosystem of CI/CD systems, DevOps and related tools has radically changed. The CNCF Cloud Native Interactive Landscape illustrates how diverse the [CI/CD space](https://landscape.cncf.io/category=continuous-integration-delivery&format=card-mode&grouping=category) is and the many projects and vendors active in the space.

By establishing a vendor-neutral CDF, the industry’s top developers, end users, and vendors can evangelize CI/CD as methodologies, define/document best practices, and create training materials to enable any software development team around the world to deliver code changes faster and more reliably, whether they are cloud native or not. 

## Why should developers care?

The challenges CI/CD projects face today, including tool complexity and lack of industry standardization around pipelines and other CI/CD tools, are stifling growth and innovation. Lacking a neutral, legal entity and strong governance, projects struggle to attract valuable support from new developers and organizations. Projects maintainers and developers spend a significant amount of time and money on workarounds in areas such as security procedures and oversight. This takes attention away from new development and innovation. A foundation with broad industry support will be able to more quickly define industry specs and create more opportunities for cross-project collaboration to improve tools for developers.

## Who uses CD?

CD is widely utilized across cloud computing, enterprise IT, and is rapidly expanding into other top industry verticals. In networking, for example, operators are working side by side with vendors to develop CI/CD tooling that enables developers to work directly with branches of upstream projects -- slashing the time to implement new features and address bugs from months to days. When working with cloud native technologies, like [Kubernetes](https://kubernetes.io/), setting up a CI/CD pipeline will speed up the release lifecycle. This enables the developer to release multiple times a day, keeping teams nimble enough to iterate quickly. 

## How does CDF relate to progressive delivery?

Progressive delivery is a form of modern continuous delivery techniques such as canarying, feature flags, A/B testing, validated deploy groups and more. Progressive delivery techniques and technologies go hand and hand with continuous delivery. For more information on what progressive delivery is, read James Governor’s Redmonk blog on this topic: [https://redmonk.com/jgovernor/2018/08/06/towards-progressive-delivery/](https://redmonk.com/jgovernor/2018/08/06/towards-progressive-delivery/) 

## How will this impact the development of open source software?

Continuous delivery improves velocity, productivity, and sustainability of software development teams. The CDF fosters collaboration between the industry’s top developers, end users and vendors to ensure that the CD approach to software engineering reaches its full potential to advance open source software development.

## Which projects will be included in the CDF?

The CDF is launching with four projects: [Jenkins](https://jenkins.io/), [Jenkins X](https://jenkins-x.io), [Spinnaker](https://www.spinnaker.io/), and [Tekton](http://github.com/tektoncd), and there are more interested projects in the pipeline. We invite people to follow the CDF Technical Operating Committee where project decisions will be made in the future: [https://github.com/cdfoundation/toc](https://github.com/cdfoundation/toc).

## Do I have to be a member to contribute to CDF projects?

Absolutely not, technical contributions to open source projects in the CDF or any Linux Foundation initiative do not require membership. Organizations join CDF as members because they want to take an active role in supporting the growth and evolution of continuous delivery models and best practices on top of sustaining the open source projects within the CDF. If you are interested in joining, please see [https://cd.foundation/members/join/](https://cd.foundation/members/join/).

## Do I have to pay to play or contribute to a CDF project?

As answered above, CDF is a "pay to sustain" organization and no technical contributions require membership.  The members of CDF have a voice in how the budget is spent to sustain the organization for the long term (think events, marketing, infrastructure, diversity scholarships and so on).

## What is Jenkins?

[Jenkins](https://jenkins.io/) is the leading open source automation server supported by a large and growing community of developers, testers, designers and other people interested in continuous integration, continuous delivery and modern software delivery practices. Built on the Java Virtual Machine (JVM), it provides more than 1,500 plugins that extend Jenkins to automate with practically any technology software delivery teams use. In 2019, Jenkins surpassed 200,000 known installations making it the most widely deployed automation server.

## What is Jenkins X?

[Jenkins X](https://jenkins-x.io/) is an open source CI/CD solution for modern cloud applications on Kubernetes. Jenkins X provides pipeline automation, built-in GitOps and preview environments to help teams collaborate and accelerate their software delivery at any scale. Jenkins X automates CI+CD for Kubernetes using the best of breed OSS tools such as Jenkins, Tekton, Prow, Skaffold, Kaniko, and Helm.

## Why are Jenkins and Jenkins X becoming a part of the CDF?

Jenkins and Jenkins X will be part of a neutral community aligned with technical interests, and receive help in building their developer communities and project governance. The CDF will also assist with Jenkins and Jenkins X marketing and documentation efforts. 

## How does this affect existing Jenkins users?

Donating Jenkins and Jenkins X to the CDF will foster greater collaboration among developers, end users, and vendors in the industry. See this email and conversation with the Jenkins community for more details: [https://groups.google.com/forum/#!msg/jenkinsci-dev/1w57jl3K4S4/OFDYSEfXEwAJ](https://groups.google.com/forum/#!msg/jenkinsci-dev/1w57jl3K4S4/OFDYSEfXEwAJ)

## What is Tekton?

[Tekton](http://github.com/tektoncd) is a set of shared, open source components for building CI/CD systems. It modernizes the Continuous Delivery control plane and moves the brains of software deployment to Kubernetes. Tekton’s goal is to provide industry specifications for CI/CD pipelines, workflows and other building blocks through a vendor neutral, open source foundation. The source of Tekton comes from [https://github.com/tektoncd/pipeline](https://github.com/tektoncd/pipeline).

## Why is Tekton becoming a part of the CDF? Why is Google donating the code?

As a founding member of the CDF, Google is donating [Tekton](http://github.com/tektoncd). Just as Kubernetes revolutionized application development by providing a standard set of APIs to interact with in the cloud, Google’s goal is to offer the same advantages to DevOps practitioners through the CDF. The CDF will provide industry specifications, secure, practical, and extensible continuous delivery building blocks that can be used to deploy code anywhere.

## What will happen with knative build with Tekton?

Pluggability has been a core feature of knative since Day 1. The goal of decoupling Build from Serving is to reinforce this pluggability concept. Users that are already happy with a build system can use that with Knative Serving. Tekton will continue to support the Knative ecosystem as a first-class target environment. Tekton pipelines will deploy to Knative environments.

Knative Build will remain a part of Knative for the foreseeable future, focusing on source-to-container workflows for Serverless environments. The two projects will remain closely aligned on standards and interfaces.

## What is Spinnaker?

[Spinnaker](https://www.spinnaker.io/) is a cloud-first Continuous Delivery platform originally created by Netflix and currently jointly led by Netflix and Google. It supports all major cloud platforms and Kubernetes, with contributions from their respective providers. Spinnaker is typically used in organizations at scale, where DevOps teams support many developers by providing "golden path" app deployment pipelines.

## Why are Google/Netflix donating Spinnaker into CDF?

With Spinnaker recently formalizing its governance, moving it to a foundation is a natural next step for the community. Spinnaker is designed as a Continuous Delivery platform and is often used in combination with Jenkins, so the CDF is really an ideal home for the project. 

Spinnaker is also a multi-component system that conceptually shares a lot of ideas with Tekton — seeing both projects come together under one foundation is a tremendous opportunity to move the state of Continuous Delivery forward together.

## How does this impact Spinnaker users?

With Spinnaker in the CDF, there’ll be additional opportunities for the community to create simpler, more powerful end-to-end experiences, and to collaborate on a single set of common standards for CI/CD. Spinnaker users collectively have a great deal of experience in the Continuous Delivery domain, and joining the CDF provides a great opportunity to share that expertise with the broader community.

Spinnaker users will also benefit from the extensive CI/CD knowledge represented within the CDF community, more consistency across the various tools they’re using, and of course, from a continually improving ecosystem!

## What will be the process for future CI/CD projects to come into the CDF?

Additional projects are expected to join the CDF through its soon to be formed Technical Oversight Committee (TOC): [https://github.com/cdfoundation/toc](https://github.com/cdfoundation/toc) with the focus of bringing together the CD ecosystem to build specifications and projects around portability and interoperability.

## What are the next steps for the CDF?

The next steps are to bootstrap governance structures. A governing board, technical and outreach/marketing committees will all be formed. We plan to do this over the coming months and invite new members to join our community. If you’re interested in joining the community to advance CD, see [https://cd.foundation/members/join/](https://cd.foundation/members/join/)

## How is the CNCF involved and why was a separate foundation necessary?

The first thing to note is that CD is applicable across the entire software industry and just not modern cloud native applications. [The Cloud Native Computing Foundation](http://cncf.io) (CNCF) is a sister foundation to the CDF with its [own governance structure and mission](https://github.com/cncf/foundation/blob/master/charter.md#1-mission-of-the-cloud-native-computing-foundation). Each foundation has a different mission as defined by their founding members and technical experts.  The CNCF believes most CD-related tooling is out of scope and broader than their focused cloud native [definition](https://github.com/cncf/toc/blob/master/DEFINITION.md), which is focused on containerization, microservices, service meshes, and orchestration. CDF goes beyond cloud and containers to include legacy infrastructure, mobile, IoT, bare metal and more. The CNCF and CDF are both under the larger Linux Foundation umbrella and plan to collaborate in many areas including co-locating conferences. For example, the CDF will be hosting a Continuous Delivery Summit (CDS) event at [KubeCon + CloudNativeCon Europe 2019](https://events.linuxfoundation.org/events/kubecon-cloudnativecon-europe-2019/), May 20th in Barcelona, Spain.

## How does the CDF support or work with other players in the DevOps space?

The CDF’s mission is to provide a neutral home for the developers, end users and vendors to collaborate on CI/CD methodologies. In this respect, CDF will support DevOps practitioners through the publication of best practices, training materials and industry guidelines focusing on portability.  

Organizations interested in becoming members of the new foundation and shaping its governance should visit the [CDF Join page](https://cd.foundation/members/join/). Developers can sign up to the [CDF Mailing List here](lists.cd.foundation/g/main). Any projects interested in joining the CDF, can contact the Technical Oversight Committee ("TOC") [https://github.com/cdfoundation/toc](https://github.com/cdfoundation/toc). 

## Where can I learn more about CDF and stay up to date?

The CDF is always publishing content to support the projets of the CDF and the developers of those projects. We publish on topics of case studies, whitepapers, code releases, events, and much more. Get involved with the links below:

- [Newsletter](https://cd.foundation/stay-connected/)
- [Email Lists](https://lists.cd.foundation/g/main) 
- [Blog](https://cd.foundation/blog/)
