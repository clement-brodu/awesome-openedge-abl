# Awesome OpenEdge ABL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet), [awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core)

A collection of libraries, tools, frameworks and software for OpenEdge ABL

Contributions are always welcome! Please take a look at the contribution guidelines and quality standard pages first.
We also accept proprietary and commercial software, as long as they offer a free trial version.

As you may notice, almost none of the resources on this list are published by Progress. 😢

If you think open source is a good idea, don't hesitate to recommend it to Progress: [https://openedge.ideas.aha.io/ideas/OPENEDGE-I-976](https://openedge.ideas.aha.io/ideas/OPENEDGE-I-976)

## IDE

### Progress Developer Studio (PDSOE)

- [CABL](https://github.com/Riverside-Software/sonar-openedge) - Code Analyzer for ABL in SonarQube, allow to create openedge rules in SonarQube/Sonarlint
- [CABL Rules](https://riverside-software.fr/) - Commercial sets of rules, ready to use **[$]**

### Visual Studio Code

- [vscode-abl/vscode-abl](https://github.com/vscode-abl/vscode-abl) - Rich OpenEdge ABL support for Visual Studio Code, fork of chriscamicas/vscode-abl.
- [chriscamicas/vscode-abl](https://github.com/chriscamicas/vscode-abl) - Openedge plugin with Compiler, Debugger,...
- [ezequielgandolfi/openedge-zext](https://github.com/ezequielgandolfi/openedge-zext) - Another Openedge plugin

### Notepad++

- [3P : Progress Programmers Pal](http://jcaillon.github.io/3P/) - An OpenEdge ABL (formerly 4GL Progress) code editor / IDE running on notepad++

## CI/CD

- [PCT](https://github.com/Riverside-Software/pct) - A set of Ant tasks for the OpenEdge environment, you should/must use it !
- [ABLDuck](https://github.com/spazzymoto/ablduck) OpenEdge automated documentation generation based on JSDuck (can be used with PCT)
- [latte](https://github.com/progress/latte) - Open Source Gradle Plugin (forked from [grabl](https://gitlab.com/grabl/grabl)) to build openedge project, based on PCT **[Depracated]**
- [OEDF](https://community.progress.com/s/question/0D54Q00008JWqzR/introducing-openedge-devops-framework-10) - Non Open Source fork of latte 😡, developed by Progress. **[Proprietary] [Free]**

## Tools and libraries

- [genoas](https://community.progress.com/s/question/0D54Q00007qckt1SAA/sample-program-to-generate-an-openapi-spec-file-from-a-catalog-file) - Generate OpenApi Specification from JSDO catalog
- [DataDigger](https://github.com/patrickTingen/DataDigger) - A dynamic, open source dataviewer for your Progress / OpenEdge databases
- [opendege-profiler-parser](https://github.com/BalticAmadeus/opendege-profiler-parser) - Progress OpenEdge Profiler data parsing to OpenTracing format by Baltic Amadeus
- [InjectABL](https://github.com/PeterJudgeZA/InjectABL) - OpenEdge InjectABL Inversion of Control container/Dependency Injection module
- [Profiler Control Tool](https://community.progress.com/s/question/0D54Q00007qbvABSAY/profiler-control-tool) - Can be used to perform profiler analysis of a Progress based application. **[Deprecated]**
- [ABLUnit](https://docs.progress.com/bundle/openedge-developer-studio-olh-117/page/Overview-of-ABLUnit-testing-framework.html) - Unit testing framework for the ABL
- [OEUnit](https://github.com/CameronWills/OEUnit) - Unit testing framework for OpenEdge ABL before the ABLUnit **[😴 inactive]**
- [OEMock](https://github.com/msabbott/OEMock) - Create mock for test with OEUnit **[😴 inactive]**
- [log4oe](https://github.com/msabbott/log4oe) - Logging framework for OpenEdge ABL based on log4j **[😴 inactive]**
- [Smart Component Library](https://www.consultingwerk.com/products/smartcomponent-library) - The OpenEdge modernization frameworg for Desktop, Web and Mobile by Consultingwerk **[$]**
- [ProTop](https://wss.com/progress-openedge-monitoring-with-protop/) - Progress OpenEdge Monitoring tool by White Star Software **[$]**

## Usefull resources

- [ADE-SourceCode](https://github.com/consultingwerk/ADE-Sourcecode) - Progress OpenEdge ADE Sourcecode uploaded by Consultingwerk 👍 (shouldn't that be done by Progress ? 😩)
- [Smart Component Library Documentation](https://www.consultingwerk.com/support/documentation) - Documentation of Smart Component Library (Jira, Class documentation...)

## Other

- [GenericService](https://gitlab.com/rdroge/genericservice) - Generic way of exposing an 'industry standard' REST api from ABL using PASOE and Webhandlers.
- [OpenEdgeAnt](https://github.com/KiltedKanuck/OpenEdgeAnt) - OpenEdge ANT build demo project
- [OpenedgeGradle](https://github.com/KiltedKanuck/OpenEdgeGradle) - OpenEdge GRADLE build demo
- [SampleApp](https://github.com/KiltedKanuck/SampleApp) - Sample app for deploy
- [OEDoc-sample](https://github.com/clement-brodu/OEdoc-sample) - Sample Documentation Site generated with ABLDuck

## Openedge versions

| Version | Fixes | Known Issues |
|---------|------| ----- |
| [12.8 (LTS)](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.8.html)  | [12.8.1](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.8.1.html) [12.8](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.8.html) | [12.8.1](https://docs.progress.com/en-US/bundle/openedge-product-notes/page/Known-issues-in-OpenEdge-12.8.1.html) [12.8](https://docs.progress.com/en-US/bundle/openedge-product-notes/page/Known-issues-in-OpenEdge-12.8.html) |
| [12.7](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.7.html)  | [12.7](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.7.html) | [12.7](https://docs.progress.com/en-US/bundle/openedge-product-notes/page/Known-issues-in-OpenEdge-12.7.html) |
| [12.6](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.6.html)  | [12.6](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.6.html) | [12.6](https://docs.progress.com/en-US/bundle/openedge-product-notes/page/Known-issues-in-OpenEdge-12.6.html) |
| [12.5](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.5.html)  | [12.5](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.5.html) | [12.5](https://docs.progress.com/en-US/bundle/openedge-product-notes/page/Known-issues-in-OpenEdge-12.5.html) |
| [12.4](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.4.html)  | [12.4](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.4.html) | [12.4](https://docs.progress.com/en-US/bundle/openedge-product-notes/page/Known-issues-in-OpenEdge-12.4.html) |
| [12.3](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.3.html)  | [12.3](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.4.html) | |
| [12.2 (LTS)](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.2.html) | [12.2.11](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.11.html) [12.2.10](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.10.html) [12.2.9](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.9.html) [12.2.8](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.8.html) [12.2.7](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.7.html) [12.2.6](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.6.html) [12.2.5](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.5.html) [12.2.4](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.4.html) [12.2.3](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.3.html) [12.2.2](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.02.html) [12.2.1](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.1.html) [12.2.0](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.2.html) |  |
| [12.1](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.1.html) | [12.1](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.1.html) |  |
| [12.0](https://docs.progress.com/bundle/openedge-whats-new/page/Whats-New-in-OpenEdge-12.0.html) | [12.0](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-12.0.html) |  |
| 11.7 (LTS)  | [11.7.19](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.19.html) [11.7.18](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.18.html) [11.7.17](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.17.html) [11.7.16](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.16.html) [11.7.15](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.15.html) [11.7.14](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.14.html) [11.7.13](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.12.html) [11.7.12](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.13.html) [11.7.11](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.11.html) [11.7.10](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.10.html) [11.7.9](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.9.html) [11.7.8](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.8.html) [11.7.7](https://docs.progress.com/bundle/openedge-product-notes/page/Issues-fixed-in-OpenEdge-11.7.7.html) |  |


Startup Parameters : [https://docs.progress.com/bundle/openedge-startup-and-parameter-reference-122/page/Introduction.html](https://docs.progress.com/bundle/openedge-startup-and-parameter-reference-122/page/Introduction.html)

DotNet Compatibility : [https://knowledgebase.progress.com/articles/Article/000054406](https://knowledgebase.progress.com/articles/Article/000054406)
