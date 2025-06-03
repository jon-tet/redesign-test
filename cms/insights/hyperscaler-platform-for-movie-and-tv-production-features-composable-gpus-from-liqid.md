---
title: Redesign Builds Hyperscaler Platform for Movie and TV Production
slug: >-
  hyperscaler-platform-for-movie-and-tv-production-features-composable-gpus-from-liqid
updated-on: '2025-02-12T15:48:12.034Z'
created-on: '2023-06-26T09:21:12.274Z'
published-on: '2025-02-12T15:48:59.990Z'
f_lead-text-2: >-
  Redesign Group uses flexibility and scalability to enhance the customer
  production environment
f_author: cms/authors/joe-sanginario.md
f_featured-image:
  url: >-
    https://cdn.prod.website-files.com/63292785af73226ede52b1c8/64a4028c8529a87c8c30967f_hyper-converged-platform.avif
  alt: null
f_seo-description: >-
  Redesign Group uses flexibility and scalability to enhance the customer
  production environment
f_seo-image:
  url: >-
    https://cdn.prod.website-files.com/63292785af73226ede52b1c8/64a4028c8529a87c8c30967f_hyper-converged-platform.avif
  alt: null
f_seo-title: >-
  Hyperscaler Platform for Movie and TV Production Features Composable GPUs from
  Liqid
f_category: cms/category/consulting.md
f_featured: true
f_is-news: false
f_linking-out: false
f_publish-date: '2023-06-26T00:00:00.000Z'
layout: '[insights].html'
tags: insights
---

Artist Anywhere, a business unit within the Redesign Group, is a cloud platform that’s purpose built for Content Creators. With datacenter locations in Los Angeles and London, it’s been used by hundreds of feature film and TV shows across every major Studio, providing a global production pipeline for distributed Animation and VFX teams.  

### The Challenge  

The Content Creation process has historically been fragmented across disparate phases of feature film, TV series, or Animation projects. Each phase often includes different teams, locations, workflows, and storage infrastructure. As the digital technologies involved within the content creation process become more complex and ubiquitous, data growth has become unmanageable. The department most impacted by the size and complexity of media storage requirements is Visual Effects. The Visual Effects teams have become the glue to bringing the creative vision of the Director to life. Reference material and metadata from pre-production and production is critical for maintaining creative context during the post-production enrichment process. The fragmented approach to managing metadata and files requires a significant amount of data management, manual handoffs, and the invariable human error, leading to loss of context. This loss of context impacts downstream post-production processes, making it more time consuming and costly to produce creative content.  

Additionally, the Media & Entertainment industry has established a new baseline of content spend, rising from 371 original content releases in 2019 to over 1,300 content releases in 2022. That number is expected to remain consistent, with over $125B in content spend projected for 2023. This places a heavy burden on a supply chain that’s already operating at capacity. There simply aren’t enough people to maintain the new baseline without the help of technology innovations.  

The \[RE\]DESIGN Group recognized the need for innovation in the form of workflow automation and tapping into the future potential of Artificial Intelligence capabilities. The Artist Anywhere platform was created to connect the fragmented phases of the content creation supply chain into a common data hub, where critical metadata and reference material could be made available to globally dispersed teams in real-time. To enable automation and eventually take advantage of AI, Redesign needed to first solve the problem of capturing all the data into a common repository. The Artist Anywhere cloud platform provides a high-performance filesystem that’s accessible for remote users, Onset data capture teams, editorial and VFX teams, and the ability to localize files at the edge for 4k reviews. The platform maintains real-time access to metadata and files regardless of user location. In addition, Artist Anywhere is a Production Tracking  pipeline that leverages the Autodesk Shotgrid database and Artist Anywhere’s Studio Workflow Suite of tools, enabling VFX Crew members to automate many time- intensive data management tasks, so they can work better and work faster.  

Artist Anywhere deploys a complete production pipeline for VFX teams, including multifactor authentication, remote access to virtual and physical workstations optimized for creative applications, high performance storage, data protection, a cloud-based delivery system with a transfer application for worldwide vendors, a suite of automation tools, and a real-time data fabric that connects users at the Edge or Cloud, enabling line speed access to all files.  

The initial launch of the Artist Anywhere platform was built using commodity hardware, virtualization technologies, and manual deployments. As the platform grew to support dozens of simultaneous projects with several hundred VFX users, the ability to compose new virtual or physical workstation profiles or to modify workstation configurations in real-time based on user feedback, became critical.  

To address these shortcomings, the Redesign team launched a project to build an entirely new, flexible platform that would allow pools of resources such as CPUs, GPUs and SAS storage to be dynamically assigned to virtual machines as needed. This allowed the Artist Anywhere cloud platform to meet peak performance requirements, rapidly on-board new users and to better adapt to invariable hardware failures.  

### Solution  

After significant research and testing, Redesign’s solution architecture team designed a new platform, dubbed the Hyperscaler Appliance. The Hyperscaler is a completely integrated appliance which includes Dell networking, Dell servers, a Mellanox RDMA fabric with Vcinity RAD-X services for RDMA over WAN, highly performant SAS storage, and pools of GPUs connected using Liqid’s Matrix Composable Disaggregated Infrastructure (CDI) software. The Hyperscaler includes virtual deployments of WekaIO software for workstation storage and Pixit Media software for primary Production storage. The appliance includes the multi-tenant Artist Anywhere Production Portal for on-boarding and off-boarding users to cloud workstations across any cloud provider or workstation virtualization technology. It also runs Redesign’s queuing system which integrates with S3 archival storage for data protection and archiving. The queuing system ensures that the folder and file structure from Production is emulated within the customer’s cloud archive environment and also provides pipeline visibility into the global namespace.  

The composable infrastructure capability with Liqid offers benefits both in terms of workload management and resiliency, ensuring clients continue to experience the performance they expect while dramatically reducing the time IT invests in managing the resources. Redesign can dynamically assign GPUs to servers and client workstations as business requirements dictate. The Hyperscaler configuration can support up to 30 to 40 GPUs per fabric, giving the Artist Anywhere platform the flexibility to deploy four-times their previous limit of five GPUs per conventional server chassis. This also enables future AI use-cases that can be extended to major studios and their production teams, by integrating meta data and reference material with language models and creative applications. To provide fault tolerance against a NAS gateway failure interrupting production, a storage HBA is composed into the NAS gateway server. In the event of a hardware failure, client VMs with both storage and GPU capacity can be reassigned to a different Hyperscaler platform, ensuring customers continue their work uninterrupted.  

“When designing a modern High Performance Computing (HPC) platform, it’s critical to ensure that every component of your architecture acts as an enabler to workflow, automation and AI,” according to Joe Sanginario, founder of The Redesign Group.

> “In the past, technology decisions and solutions have often been made within organizational silos that were unaware of the constraints that those decisions introduced at the pipeline layer. We’ve shattered those constraints by designing a true hyper-converged pipeline. Data access is extensible and in real- time. This is not S3 syncing, this is efficient RDMA access that doesn’t require any computing overhead. Our infrastructure is pipeline aware, meaning we can query metadata instantly and build pipeline automation tools that enable users to manage workflow rather than files. This is built with commodity components, in the smallest form factor, yet abstracted into software for composability. That is pipeline flexibility that can solve today’s toughest data management challenges while maintaining an innovation lifecycle for whatever comes next.”  

In addition to offering the Hyperscaler platform as a service with the Artist Anywhere Cloud, Redesign also sells the Hyperscaler platform to HPC customers that prefer to build their own internal multi-tenant cloud capabilities.  

### The Benefits  

The Hyperscaler platform with composable GPUs and storage HBAs also simplifies the scoping process for on-boarding new clients. “We can confidently purchase commodity infrastructure and configure those components to achieve any desired workflow outcome for our users.

> “With the Hyperscaler platform, we’re able to scale our business more easily and rapidly. The lead time for on-boarding new clients has been dramatically reduced. We’ve cut our public cloud costs in half by hosting most of our data and compute requirements internally, and we’re pleased to offer a more resilient platform that can maintain productivity for our users.” said Sanginario.  

### About Liqid  

LIQID Inc.’s composable infrastructure software platform, Liqid Matrix TM, unlocks cloud-like speed and flexibility plus higher efficiency from on-prem infrastructure. Now IT professionals can configure, deploy, and scale physical, bare-metal servers in seconds, then reallocate valuable accelerator and storage resources via software as needs evolve. Dynamically provision previously impossible systems or scale existing investments, and then redeploy resources where needed in real-time. Unlock cloud-like datacenter agility at any scale and experience new levels of resource and operational efficiency with Liqid.

‍
