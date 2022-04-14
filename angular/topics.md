### How DI is used in Angular

DI is a coding pattern in which a class asks for dependencies from external sources rather than creating them itself.

The main reason why is important, because it helps avoid hight coupling between classes. 

Decouple object creation from using this object get you ability to replace objects, without any changes in our class that use than object.

@Optional - if dependency not found, we didn't get any error

@Self - it will not asking parent, check only it's own injector

@SkipSelf - skip self, skip injector where it was declared, starting resolving dependencies with parent

@Host - host element should be the last stop when it is searching for providers. Boundaries are only for view scope (html)

### Change Detection mechanism in Angular NgZone

[Angular Change Detection - How Does It Really Work?](https://blog.angular-university.io/how-does-angular-2-change-detection-really-work/)

[zone.js от А до Я](https://medium.com/@overthesanity/zone-js-%D0%BE%D1%82-%D0%B0-%D0%B4%D0%BE-%D1%8F-fdb995917968)

### RxJS pros/cons, NgRX

[RxJS's Pros And Cons: Is It A Holy Grail Or A Nuisance? - K&C](https://kruschecompany.com/rxjs-pros-and-cons/)

[Angular: понятное введение в NGRX](https://habr.com/ru/post/489674/)

### Compare with React

[Angular vs. React: Which is Better and Why?](https://www.cleveroad.com/blog/angular-vs-react)

### How to migrate from Angular 1 to Angular 8

[Angular](https://angular.io/guide/upgrade)

### Benefits/drawbacks of Angular 8 in comparison with 1 (how to convince Client to migrate)

[Angular vs AngularJS - A Complete Comparison Guide 2019](https://www.techaheadcorp.com/blog/angular-vs-angularjs/)

### Angular performance optimizations techniques

[Angular Performance Optimization Techniques](https://medium.com/swlh/angular-performance-optimization-techniques-5b7ca0808f8b)

### Angular memory leaks prevention

[](https://www.twilio.com/blog/prevent-memory-leaks-angular-observable-ngondestroy)

### Angular tools

[Angular](https://angular.io/guide/devtools)

### Lifecycle hooks

[Angular](https://angular.io/guide/lifecycle-hooks)