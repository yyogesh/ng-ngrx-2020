#Ngrx Installation

npm install @ngrx/{store,effects,entity,store-devtools} --save

## Ngrx Schematics

npm i @ngrx/schematics -g

ng add @ngrx/schematics

ng generate store State --root --module app.module.ts

ng generate effect App --root --module app.module.ts

ng g action <action name>

ng g reducer <reducer name>

ng g reducer User --reducers reducers/index.ts

ng g selector user

ng g effect user --root -m app.module.ts
