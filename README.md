![logo_almis](wiki/images/logo_almis.png)
# **Almis Web Engine**

## Table of Contents

* **[Introduction](wiki/introduction.md)**
* **[Installation](wiki/installation.md)**
* **[Guides](wiki/guides.md)**
  * [Configuration guide](wiki/configuration-guide.md)
  * [Basic application developer guide](wiki/basic-developer-guide.md)
  * [Advanced application developer guide](wiki/advanced-developer-guide.md)
  * [Developer tools](wiki/developer-tools.md)
  * [Selenium tests guide](wiki/selenium-tests-guide.md)
  * [Printing engine guide](wiki/print-guide.md)
  * [Debugging guide](wiki/debugging-guide.md)
* **AWE Changelog**
  * [AWE 4.0.0](https://git.almis.com/awe-team/awe/issues?milestone_title=awe+v4.0.0&state=closed) - **[Impacts](https://git.almis.com/awe-team/awe/issues?scope=all&utf8=%E2%9C%93&state=closed&milestone_title=awe%20v4.0.0&label_name[]=Impact)**
* **Migration guides**
  * [AWE 4.0.0](wiki/awe-4.0-migration-guide.md)
  
<details> 
<summary></summary>
custom_mark13 @startuml; actor User; participant "First Class" as A; participant "Second Class" as B; participant "Last Class" as C; User -> A: DoWork; activate A; A -> B: Create Request; activate B; B -> C: DoWork; activate C; C -> B: WorkDone; destroy C; B -> A: Request Created; deactivate B; A -> User: Done; deactivate A; @enduml custom_mark13
