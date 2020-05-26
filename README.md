<div align="center">
    <a href="https://summerofcode.withgoogle.com/projects/#6091933446832128"><img src="https://i.imgur.com/d5n5JXA.png" width="720" alt="google-summer-of-code"></a>
    <h2>
Improving compmodelmatch.org @ <a href="https://github.com/nrnb">NRNB</a> 
    </h2>
</div>

<p align="center">
	<a href="#project-abstract">Project Abstract</a> | 
	<a href="#pull-requests--issues">Pull Requests & Issues</a> | 
	<a href="#updates">Updates</a> | 
	<a href="#links">Links</a>
</p>

<p align="center">
	Check out my <a href="https://medium.com/stray-stream/">blog</a> or follow me on <a href="https://twitter.com/sjha2048">Twitter</a> for more updates.
</p>
<br>

## Project Abstract

Compmodelmatch is the project to match researchers with different expertise. The set of capabilities we need is best approximated by an online data management system. There exist a few such systems, we have selected SEEK platform (Wolstencroft et al., 2015) that provides the integration and interlinking of heterogeneous data sets in systems biology. The SEEK platform is used in the FAIRDOMHub public service (Wolstencroft et al., 2017) to upload and publish research assets. The SEEK platform is open-source and built using Ruby on rails. SEEK platform has well-developed data sharing policies that are upheld through assigned roles. Researchers remain in control of their own assets and can decide who to share them with, and when to publish them. External resources (such as PubMed) can be searched via the SEEK interface through available RESTful Application Programming Interfaces (APIs). Thus, users can easily create libraries of publications related to their projects. The main web user interface of SEEK allowed users to browse projects, institutions, people, publications and many other assets available. Documents can be made public or be restricted through a comprehensive permissions system that controls visibility to projects and individuals. Content is indexed on upload and available through a Solr search.

## Objectives 

- Better page design and navigation 
- Customization to serve as NRNB hub for providing expertise and requesting help
- Sign-up using social media platforms 
- Fetching user data from ORCID
- Security improvements 


**Mentors**: [@vcellmike](https://github.com/vcellmike) and [@pepe454](https://github.com/p)


## Pull Requests & Issues

#### [compmodelmatch](https://github.com/pepe454/compmodelmatch)

Pull Requests

- [#10](https://github.com/pepe454/CompModelMatch/pull/10): [feat: UI] minor tweaks to registration page
- [docker-hub](https://hub.docker.com/repository/docker/sjha2048/compmodelmatch)[feat:deployment] added docker support.

Issues


## Updates

### Community Bonding (May 4, 2020 - June 1, 2020)

we finalized the workflow and decided that vagrant will be our first choice for setting up the development enviornment

### Blog posts 

I will be documenting my journey after each evaulation phase.

- GSoC 2020: Acceptance [l’ acceptation](https://medium.com/stray-stream/gsoc-2020-acceptance-l-acceptation-f1e3003ae6cf).

## Links

- [GSoC 2020 Proposal NRNB - sjha2048](https://docs.google.com/document/d/104erXLjouNObUAcLWz_Vva5jHKpp3zuxMAo2Ct4ZI3A/edit?usp=sharing)
- [Project Link](https://summerofcode.withgoogle.com/projects/#6091933446832128) on GSoC Website.


## Footnotes

- We have weekly meetings over google meet on every monday at 10am EST 
- I will update the blog post section every week when the coding peroid starts
- Project progress is being monitored on a Notion Kanban board, I will update the link of the board when coding period is over 