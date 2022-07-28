# [Getting started with iOS Application Modularization by Amisha I](https://medium.com/canopas/getting-started-with-ios-application-modularization-98fa0e68da0b)

<blockquote>

## Benefits 
Creating modularization has many advantages. For example,

* It clearly improves our code architecture.
* As we have separated our app into different parts, they can have their own unit test target and UI test target so that we can test our code in a better way.
* Only that framework will be rebuilt at the next compilation in which we have made changes. This is where our precious time will be saved. Basically, it speeds up build time.
* It also provides Encapsulation if you don’t want to share some class to any separate module.
* We can use this separate framework in another project.

## Drawbacks
Here are some reasons why you should not modularise your code.

* By following the modularization your code can be a bit more complex to understand for beginners.
* Some feature developments might require changes in multiple modules. This may increase the cost of development for some features.
* Having too many dynamic frameworks can slow down the launch time of your app.
</blockquote>
