
ng new nyaanmaster
cd nyaanmaster
ng --version
ng -v
git status
git config user.name 'hyoushke'
git config user.email 'hyoushke@gmail.com'

npm install @angular/material --save
npm install @angular/animations --save
npm install @angular/cdk --save
npm install hammerjs --save

npm install @ngrx/store --save
npm install @ngrx/effects --save
npm install @ngrx/entity --save



mkdir app/components
mkdir app/models
mkdir app/services
mkdir app/store


mkdir app/components/todo
ng g component components/todo/todo-container
ng g component components/todo/todo-navigation
ng g component components/todo/todo-form
ng g component components/todo/todo-item
ng g component components/todo/todo-list


ng serve --port 9090 --poll 1000
