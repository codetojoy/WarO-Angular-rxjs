### Setup

* in parent dir: `ng new sandbox`

```
ng generate component players
ng generate component player
ng serve
npm install --save bootstrap@3
    - edit angular.json and add `node_modules/bootstrap/dist/css/bootstrap.css`
```

### TODO

* error handling
* review constants 
* clear player stats on new game
* CRUD ops for players in config area
* proper tests
* CSS treatment
    - esp. test for small devices
* revisit architecture / code seams
* revisit loop idioms etc with functional style
* revisit RxJS
* remote api strategy 

* X canary tests
* X audit round/game: closed system of points
    X - user hand is not being handled properly 
* X - config area
    * X - add routing from course
