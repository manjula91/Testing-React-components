 ### Tests says "I am Important" but the developer says "I do not want lot of dependencies"
 
 
# Do we really test? 
  #### Stop Lying
 
#### We started with,  Jasmine-based stack, we’ve adopted a testing stack consisting of Mocha as our test runner, Chai for assertions, and Enzyme for asserting on component output. But than it created like too much dependency. lot of effort. Then we tried Jest and it very cool and works with less effort & writing more of test cases.
 
#### One day We just gave a shot to what it would take to migrate all of out test cases to jest. And yes the transition was very simple. And we had removed several dependencies from our code base.
 
#### But most importantly it mean set that everytime we hire someone new, they wouldn’t have to thunk about these dependencies, but they will just be thinking about these single dependencies.
That means it reduces a lot of overhead that comes whenever we are hiring someone new.
 
#### After we migrated to jest running a single test case took almost from 5 seconds to instant run, which means our feed back loop was very tighted which means we ended up writing more test cases.


