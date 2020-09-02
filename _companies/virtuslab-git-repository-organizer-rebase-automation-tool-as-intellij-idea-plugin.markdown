---
layout: project
permalink: 
company: VirtusLab
company_img:
company_desc: |
    [VirtusLab](https://www.virtuslab.com "VirtusLab Homepage"), dynamically developing since 2010, 
    currently cooperates with the largest brands in the e-commerce, retail, finance and investment industries. 
    They also work with interesting start-ups that are trying to introduce a lot of new products and innovations to the market. 
    They see the need to increase the efficiency of IT systems implementation, 
    hence their investments in this direction and cooperation with partners such as Lightbend, JetBrains or Confluent.
project: |
    Git repository organizer & rebase automation tool as IntelliJ IDEA plugin
project_img:
technological_stack: |
    IntelliJ Platform, git; implementacja: Java/Scala/Kotlin - TBD; ew. IronPython (git-machete jest napisany w Pythonie)
methodology: |
    zwinna
shipment_method:
training:
    Tak
tools_provided: |
    Tak
mentor: |
    Paweł Lipski
worktime: |
    Od ⅗ etatu - do pełnego etatu, czas trwania stażu 3 miesiące.
location: |
    W biurze
money: |
    4000 brutto miesięcznie
later_employment: |
    Tak
team_size: |
    1-3 developerów
requirements: |
    Znajomość gita oraz Pythona lub dowolnego języka działającego na JVM będzie sporym atutem

project_roles: |
    Software Developer
copyrights: |
    - Prawa do projektu: MIT License (Open source)
    - Sposób udostępnienia danych; opis i weryfikacja działania projektu na potrzeby pracy licencjackiej: Dane są ogólnodostępne
---

## Git Machete CLI

[git machete](https://github.com/VirtusLab/git-machete#git-machete) 
is command-line tool for organizing branches in git repository in a tree-like hierarchies, 
allowing to significantly reduce the effort traditionally associated 
with maintaining multiple branches in the repository at the same time, especially wrt. rebase. 
The project main objective would be to provide an IDE plugin with similar functionality. 
Part of the task is to assess how each CLI feature can be intuitively represented in a GUI plugin.

## Git Machete IntelliJ Plugin

This plugin adds an extra tab in the Git tool window that gives the instant answer to the questions: 
- what are the branches in this repository? 
- what needs be merged/rebased/pushed/pulled?
 
 ---

![Git Machete Tab](../assets/images/virtuslab_gitmachete-sample_workflow.gif)

 ---

The bird's eye view provided by Git Machete makes rebases/push/pulls hassle-free even when multiple branches 
are present in the repository: master/develop, your topic branches, teammate's branches checked out for review etc.

Along these lines, Git Machete helps in creating and maintaining small, focused, easy-to-review PRs.

You can read more at the [plugin's GitHub repository](https://github.com/VirtusLab/git-machete-intellij-plugin#git-machete-intellij-plugin).

The plugin can be downloaded from the IDE and via its [marketplace page](https://plugins.jetbrains.com/plugin/14221-git-machete).
