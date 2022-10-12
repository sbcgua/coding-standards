# Junior ABAP developer baseline

This article has *Beta* state. It should be updated and detailed, add more links.  
Inspired by developer baseline of Webbylab https://github.com/WebbyLab

I believe a developer should not be limited to ABAP only. They need a wider outlook to modern technologies/approaches/practices which may help in their work. The below is the list of topic a junior (yes, junior) developer should learn soon after his start in our company. It must not be an expert knowledge but must be at least general concept understanding and ability to judge and discuss these topics and technologies and explain why each concept is needed and how it is used. Self learning is high welcomed but, of course, it can be also guided by senior colleagues - constructive questions are always welcomed.

## SAP and ABAP related

### SAP Generics

- Navigation
- Transports
- Generic understanding of ERP modules and their purpose and flows

### Abap

Not limited to (obviously, all the basic language constructs are assumed), but these are important !

- Internal tables: standard, hashed, sorted - difference, typical usage, downsides, secondary keys
- SALV: creation, event handling, sorting, grouping, controlling field catalog, custom toolbars
- Exceptions: purpose and benefits over return codes, difference between check and no-check exceptions, cleanup section
- OOP
    - Classes vs Interfaces
    - Inheritance/polymorphism vs Composition
- Unit testing: test classes, interface mocks, implementing test doubles from scratch
    - usage of [mockup loader](https://github.com/sbcgua/mockup_loader) and [mockup loader toolkit](https://github.com/sbcgua/mockup_loader_toolkit)
- Debugging: breakpoints, watch-points, "halt here - `\h`", call stack, watches, compare variables, XML view

### DB and SQL

- DB structure: tables, views
- Table indexes: their benefits and downsides
- Joins: inner, outer
- Dynamic SQL and SQL injections

### Code analysis and performance

- Usage of Code inspector (SCI)
- Usage of [abaplint](https://github.com/abaplint/abaplint)
- Usage of SAT, SQL monitor

### Other

- NW752 dev edition setup
    - e.g. [blog](https://blogs.sap.com/2018/09/22/installing-netweaver-as-abap-7.52-sp-01-developer-edition-with-vagrant/) and [video](https://www.youtube.com/watch?v=-BeEF1U-cqQ)
    - or [this video](https://www.youtube.com/watch?v=eFzRdG4_gVs)

## Not ABAP related

### Web

- REST API principles
- HTTPS: principle, concept of symmetric and asymmetric encryption, how certificates work and authority is ensured
- What are proxy servers
- JSON
- XSLT
- Base64
- Encoding and code pages: unicode, utf16, utf8, ansi, cp1251 ...

### Git

- Concepts: repository, origin, commit, push, pull
    - [Nice video](https://www.youtube.com/watch?v=f-Br8cud2eI) on good git rules (though supposes understanding of git command line at least a bit)
    - [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
- Gitlab/Github UI
- Branches
- Pull/merge requests
- Code review concepts
- Usage of [abapGit](https://github.com/abapGit/abapGit)

### Computer science

- Algorithm complexity - O(1) vs O(n) vs O(n^2) vs O(log(n)) vs O(n*log(n))
    - [Nice video](https://www.youtube.com/watch?v=TesnXS0HeDw) (about JS, in russian)
- How binary search works
- Basic patterns: singleton, factory, 
- ... tbd

### Development concepts

- Scrum vs Kanban vs Waterfall
- CI/CD, Devops (values)
- TDD - test driven development
    - [Intro to TDD](https://hackernoon.com/introduction-to-test-driven-development-tdd-61a13bc92d92)
    - [TDD the whole point from the beginning](https://medium.com/@agile_ed/tdd-the-whole-point-from-the-very-beginning-9d8a45a5f465)
    - [DevTernity 2017: Ian Cooper - TDD, Where Did It All Go Wrong](https://www.youtube.com/watch?v=EZ05e7EMOLM)
    - [Red, Green, Refactor](https://www.codecademy.com/articles/tdd-red-green-refactor)
    - Last but not the least, [Robert Martin on TDD](https://www.youtube.com/watch?v=58jGpV2Cg50&t=1300s) (time frame ~21:40 - ~36:10, but the whole series is amazing!)
- DDD - Domain driven design
- Software Development Life Cycle (SDLC) - e.g. [here](https://www.tutorialspoint.com/sdlc/sdlc_overview.htm)
- MVC and code decoupling in general
- "make it work, make it proper, make it fast"

## Practical tasks

- TBD
