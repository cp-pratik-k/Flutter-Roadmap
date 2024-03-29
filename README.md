<h1 align="center">Flutter Developer Roadmap 2023</h1>

![roadmap-image](https://github.com/Pratik-canopas/Flutter-Roadmap/blob/main/Flutter-developer-roadmap-header-image.jpg)

## What is Flutter?
Flutter is an SDK(Software Development Kit) developed by google that allows developer to build native cross-platform apps with just one programming langauage-Dart. From single codebase, it creates native app for ios, Android and web, that can be published to the stores later.
[view more](https://en.wikipedia.org/wiki/Flutter_(software))

# Table of Contents:
- [Flutter Setup](https://github.com/Pratik-canopas/Flutter-Roadmap#flutter-setup)
- [Sprint 1](https://github.com/Pratik-canopas/Flutter-Roadmap#sprint-1)
- [Sprint 2](https://github.com/Pratik-canopas/Flutter-Roadmap#sprint-2)
- [Sprint 3](https://github.com/Pratik-canopas/Flutter-Roadmap#sprint-3)
- [Sprint 4](https://github.com/Pratik-canopas/Flutter-Roadmap#sprint-4)
- [Sprint 5](https://github.com/Pratik-canopas/Flutter-Roadmap#sprint-5)
- [Sprint 6](https://github.com/Pratik-canopas/Flutter-Roadmap#sprint-6)
- [Key Topic](https://github.com/Pratik-canopas/Flutter-Roadmap#key-topic)


## Flutter Setup
* [Setup](https://docs.flutter.dev/get-started/install)

## Sprint 1:

### Dart basics:
* Introduction to [Dart](https://hackernoon.com/why-flutter-uses-dart-dd635a054ebf)
* [Dart](https://dart.dev/guides) programming langauage

### Practical 1.1
* Do all [Practicles](https://github.com/Pratik-canopas/Flutter-Roadmap/blob/main/practical-1.1) using [Dartpad](https://www.dartpad.dev/?).

### Practical 1.2
* Upload practical on gitlab or github.
    - You can create repository of practicals and upload practicals 1.1 on Gitlab.
    - You can create Gists from dartpad and upload practicals on github.

### Flutter basics:
* introduction to [Flutter](https://www.javtpoint.com/flutter)
* [Why flutter?](https://medium.com/flutter-community/reasons-why-flutter-is-setting-the-trend-in-mobile-app-development-4aa707532fb)
* Introduction to [Declarative UI](https://docs.flutter.dev/get-started/flutter-for/declarative)
* [What is widget in flutter?](https://www.geeksforgeeks.org/what-is-widgets-in-flutter/)
* Introduction to [Widgets](https://docs.flutter.dev/development/ui/widgets-intro)
* [Layouts in flutter](https://docs.flutter.dev/development/ui/layout)
* [Building Layout](https://docs.flutter.dev/development/ui/layout/tutorial)
* [View widget list](https://docs.flutter.dev/development/ui/widgets)

### Practical 1.3
* create an app with this [layout](https://github.com/Pratik-canopas/Flutter-Roadmap/blob/main/practical-1.3.jpg)

### Code style:
* [Best practices and tips](https://medium.com/flutter-community/flutter-best-practices-and-tips-7c2782c9ebb5)
* [Effective Dart](https://dart.dev/guides/language/effective-dart)
* [Flutter code formatting](https://docs.flutter.dev/development/tools/formatting)
 
 ### Flutter Tools:
* [Hot Reload](https://docs.flutter.dev/development/tools/hot-reload)
* [Punspec file](https://docs.flutter.dev/development/tools/pubspec)

## Sprint 2:

### Version control: 
* Introduction to version control: [What Is Version Control?](https://tutorials.codebar.io/version-control/introduction/tutorial.html)
* How to use git
    -  [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
    -  [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929402#overview)
    -  [When to commit in version control](https://softwareengineering.stackexchange.com/questions/74764/how-often-should-i-do-you-make-commits)

### Practical 2.1
* create repository of [practical 1.3](https://github.com/Pratik-canopas/Flutter-Roadmap#practical-13)

### Supporting different devices
* [Adaptive and Resposive](https://docs.flutter.dev/development/ui/layout/adaptive-responsive) apps

### Packages & Plugins
* [packages & Plugins](https://docs.flutter.dev/development/packages-and-plugins/using-packages) in fluttter
* [packages & plugins site](https://pub.dev/)

### DelightFul User experience
* Intorduction to [Material components](https://docs.flutter.dev/development/ui/widgets/material)
* How to Build Beautiful UIs with Flutter Widgets 
    -  Udemy Course 1 - Section 6


### Practical 2.2
* Create given [Responsive UI](https://user-images.githubusercontent.com/92501869/202130578-6c42048a-ce47-4833-bdc2-9e700cc6a489.png)
   - You can use alternative images.
   
### Navigation:
* [Navigation](https://docs.flutter.dev/cookbook/navigation) in Flutter
* [Navigation and Routing](https://docs.flutter.dev/development/ui/navigation)
* Introduction to [Navigator 2.0](https://blog.codemagic.io/flutter-navigator2/)
* Introduction to [Go_Router](https://pub.dev/packages/go_router)

### Practical 2.3
* Implement an app with a bottom bar that has 4 screens (home, setting, like, search).
   - Implement a route between screens.
   - Implement go_router for bottombar navigation or you can use indexedStack for bottombar navigation.
   
## Sprint 3:

### Json serialization:
* [Json and serialization](https://docs.flutter.dev/development/data-and-backend/json)
   - [Parsing Json](https://medium.com/@abhishekdoshi26/parsing-json-in-flutter-7519293f5168) in flutter
* [Auto generate](https://medium.flutterdevs.com/automatic-generate-json-serializable-in-flutter-4c9d2d23ed88) json serializable in flutter

### Networking:
* [Networking in flutter](https://docs.flutter.dev/development/data-and-backend/networking)
* [Retrofit](https://medium.com/mindful-engineering/retrofit-the-easiest-way-to-call-rest-apis-is-flutter-fe55d1e7c5c2)
* [Dio](https://pub.dev/packages/dio)-  powerful HTTP client of dart
* [Chopper](https://pub.dev/packages/chopper)- HTTP client generator for Dart and Flutter using source_gen and inspired by Retrofit.

### Practical 3.1
* Implement Food Application with following functionality 
* Fetch food feeds from API 
* User should be navigate to its detail page by clicking reciepe
* Add log click delete functionality on food click to delete food from local storage
* Implement [pull to refresh](https://pub.dev/packages/pull_to_refresh) functionality to refresh cached feeds in local storage.

    API - GET request - 'https://spoonacular-recipe-food-nutrition-v1.p.rapidapi.com/food/ingredient
    
    headers: {
    'X-RapidAPI-Key': '6991e41207mshaaf1e8dd61f03fdp17fbe9jsn3c96953146c7',
    'X-RapidAPI-Host': 'spoonacular-recipe-food-nutrition-v1.p.rapidapi.com'
  }
  * Note:
    - Use http package for networking
  
 ### Reference:
 * [Networking like a pro](https://medium.com/swlh/how-to-do-networking-like-a-pro-in-flutter-7e2612103cb5)
 * Flutter networking [tutorial](https://www.kodeco.com/5896601-flutter-networking-tutorial-getting-started)
 
 ### Work in background
 * [Concurrency](https://dart.dev/guides/language/concurrency) in Dart
 * [Asynchronous programming](https://dart.dev/codelabs/async-await)
 #### Reference:
 * [Asynchronous](https://medium.flutterdevs.com/concurrency-in-dart-b9171278af31) in Dart
 * [WorkManager](https://pub.dev/packages/workmanager)
 * [Thread and Isolate](https://medium.com/flutter-community/thread-and-isolate-with-flutter-30b9631137f3)
 
 ## Sprint 4:
 
 ### App Architecture:
 * [Archtectural overview](https://docs.flutter.dev/resources/architectural-overview)
 * [Flutter MVVM Architecture](https://medium.com/flutterworld/flutter-mvvm-architecture-f8bed2521958)
 * [MVVM](https://medium.flutterdevs.com/design-patterns-in-flutter-part-3-mvvm-a310de4eb83) design pattern
 
 ### State management:
 * [Interoduction](https://docs.flutter.dev/development/data-and-backend/state-mgmt/intro) to state management
 * [Conceptual types of state](https://docs.flutter.dev/development/data-and-backend/state-mgmt/ephemeral-vs-app)
 * State management [approaches](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options)
 * Udemy Course 1: Section 16

### Local storage:
* [Store key-vaue pair](https://docs.flutter.dev/cookbook/persistence/key-value)
* [Read and wirte files](https://docs.flutter.dev/cookbook/persistence/reading-writing-files)
* [Sqlite database](https://docs.flutter.dev/cookbook/persistence/sqlite)

### Practical 4.1
* Create simple TODO app with CRUD operation with SQLite.
* Home screen should have list of task with add new task fab button.
* On the click of task it should be redirect to task status screen where it can be edit.
* On the cell swipe it shows delete option and on it's click that particular task should delete.
* Add option to active and inactive task.
  - Note
    - Use flutter bloc for state management
    - Use provider for state management
   
   
 ### Reference:
* [Database concepts](https://www.tutorialspoint.com/flutter/flutter_database_concepts.htm) in flutter
* [Provider](https://medium.com/codechai/provider-state-management-in-flutter-d453e73537c5)state management in flutter
* [BLoC](https://blog.logrocket.com/state-management-flutter-bloc-pattern/) state management in flutter

## Sprint 5

### Testing:
* [Intruduction](https://docs.flutter.dev/testing) to testing flutter apps
* [Unit testing](https://docs.flutter.dev/cookbook/testing/unit/introduction)
* [Widget testing](https://docs.flutter.dev/cookbook/testing/widget/introduction)
* [Integration testing](https://docs.flutter.dev/cookbook/testing/integration/introduction)
* Mock dependencies using [Mockito](https://docs.flutter.dev/cookbook/testing/unit/mocking)
* Introduction to [TDD](https://medium.com/upday-devs/flutter-test-driven-development-e57f2defff43)

### Package
* [Test](https://pub.dev/packages/test)

### Practical 5.1:
* Add Unit,widget and integration test in practical 4.1

### Depenedecy Injection
* [Introduction](https://www.geekyants.com/blog/understanding-dependency-injection-in-flutter-using-provider-143/) to dependency injection
* [DI in flutter](https://medium.com/flutter-community/flutters-dependency-injection-c4f053e4408)
* Package:
   -  [injectable](https://pub.dev/packages/injectable)
   -  [getIt](https://pub.dev/packages/get_it)

### Reactive programming
* [RxDart](https://pub.dev/packages/rxdart)
* Introduction to [RxDart](https://medium.com/flutter-community/why-use-rxdart-and-how-we-can-use-with-bloc-pattern-in-flutter-a64ca2c7c52d)

### Dev Tools:
* [Flutter Inspector](https://docs.flutter.dev/development/tools/devtools/inspector)
* [Memory allocation](https://docs.flutter.dev/development/tools/devtools/memory)
* Flutter performance [best practices](https://docs.flutter.dev/perf/best-practices)

## Sprint 6:

### Final Practocal:
1 Implement a shopping application 
      
  Screen one - Home screen 
   -  On main screen show list of products - [API](https://fakestoreapi.com/products)
      
   -  Open product detail on it’s click - [API](https://fakestoreapi.com/products/1)
      
   -  Add option to search products by categories - [API](https://fakestoreapi.com/products/categories)
      
   -  Add option to check out all product in cart
 
  Screen two - Detail screen
   -  Show full detail with images and description 
   -  Add option to add/remove the product from the cart ( Add/delete an item in local database)  

  Screen three - Show products from cart
     
   -   Fetch and show all cart item from local database
   -   Add option checkout and show total price of products
   -   Add option to remove from cart
                  

  Screen four - Login 
   -   User must have to login before adding any item into cart - API
   -   Add option to logout 
      

  Use navigation 2.0 for routing.
  Add unit test for all viewmodel and helper classes

 2  Make a calculator application. Save calculation history in the database. Users can view history and clear history.
 
## Key Topic:

### Advance UI:
* [slivers](https://docs.flutter.dev/development/ui/advanced/slivers)
* [Animation in flutter](https://docs.flutter.dev/development/ui/animations)

### Localization:
* add multi language support in flutter using [localization](https://docs.flutter.dev/development/accessibility-and-localization/internationalization)

### State Management:
* [Provider](https://pub.dev/packages/provider)
* [BLoc](https://bloclibrary.dev/#/gettingstarted)
* [Getx](https://pub.dev/packages/get) 
    - You can do state management, dependency injection and navigation using getx
* [riverpod](https://riverpod.dev/docs/getting_started)
* [Redux](https://pub.dev/packages/flutter_redux)
* [rxDart](https://pub.dev/packages/rxdart)
    - [how to use rxdart with bloc pattern](https://medium.com/flutter-community/why-use-rxdart-and-how-we-can-use-with-bloc-pattern-in-flutter-a64ca2c7c52d)

### Navigation:
* [Using Navigator key](https://docs.flutter.dev/cookbook/navigation)
* Navigator 2.0
    - [navigation 2.0 with deep linking](https://www.kodeco.com/19457817-flutter-navigator-2-0-and-deep-links)
    - [navigation 2.0 with nested routes(bottombar routes)](https://lucasdelsol01.medium.com/flutter-navigator-2-0-for-mobile-dev-nested-navigators-basics-2dab6c55010e)
* [Go_Router](https://pub.dev/packages/go_router)

### Networking:
* [Http](https://pub.dev/packages/http)
* [Dio](https://pub.dev/packages/dio)

### Databases:
* #### Local Database:
    - [Shared Preferences](https://pub.dev/packages/shared_preferences)
    - [Sqflite](https://docs.flutter.dev/cookbook/persistence/sqlite)
    - [Hive](https://pub.dev/packages/hive)
* #### Online Database:
    - [Firebase](https://firebase.flutter.dev/docs/overview/)
    - [google sheet using app script](https://medium.flutterdevs.com/integrate-google-sheet-to-flutter-app-75e8bf19a075)
    - or any online database using API [networking](https://github.com/Pratik-canopas/Flutter-Roadmap/blob/main/README.md#networking-1).

### Dependency Injection:
* [GetIt](https://pub.dev/packages/get_it)
* [Injectable](https://pub.dev/packages/injectable)

### Others:
* how to create [web app](https://docs.flutter.dev/get-started/web) using flutter
* [how to develop an package or plugins in flutter](https://docs.flutter.dev/development/packages-and-plugins/developing-packages)
* [CI/CD in gitlab](https://docs.gitlab.com/ee/ci/quick_start/)




