**Git Flow Minu BB**

A nossa estrutura de branching está organizada da seguinte forma:


**Master (protegida)**

A branch master contém todo o código que ira para produção.

**Main (protegida)**

A branch main contém todo o código que ira para homologação, após homolagado o código abrir um pr para a master.

**Hotfix**

A branch hotfix corrige os bugs encontrados em produção, deve ser criada a partir da master com a nomenclatura _hotfix/{nome-do-hotfix}_, após concluída abrir um pr para a master.

**Bugfix**

A branch bugfix corrige os bugs encontrados em homologação, deve ser criada a partir da main com a nomenclatura _bugfix/{nome-do-bugfix}_, após concluída abrir um pr para a main.

**Feature**

A branch feature contém todo o código referente a feature que será desenvolvida, deve ser criada a partir da main com a nomenclatura _feature/{nome-da-feature}_, após concluída abrir um pr para a main.

**Task**

A branch task contém todo o código referente a uma das tasks pertencentes à feature, deve ser criada a partir da feature com a nomenclatura _{seu-nome}/{nome-da-feature}/{nome-da-task}_, após concluída abrir um pr para a feature.

![git_flow](https://user-images.githubusercontent.com/84921883/180483782-5f6476b1-3832-4a2d-a71e-d4e64a896ed1.png)
