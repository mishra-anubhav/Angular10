Key-Points(Just The basics)
* Angular is a platform and framework for building single-page client applications using HTML and TypeScript. Angular is written in TypeScript. It implements core and optional functionality as a set of TypeScript libraries that you import into your apps.

* The architcture of an Angular relies on cerrain fumdamental concepts. The basic building blocks are Ngmodules. NgModules collect related code into functional sets; an Angular app is defined by a set of NgModules. An app always has at least a root module that enables bootstrapping, and typically has many more feature modules.

* Components define views, which are sets of screen elements that Angular can choose among and modify according to your program logic and data.

* Components use services, which provide specific functionality not directly related to views. Service providers can be injected into components as dependencies, making your code modular, reusable, and efficient.

* A template combines HTML with Angular markup that can modify HTML elements before they are displayed. Template directives provide program logic, and binding markup connects your application data and the DOM. There are two types of data binding:

* Event binding lets your app respond to user input in the target environment by updating your application data.

* Property binding lets you interpolate values that are computed from your application data into the HTML.

* templates can use pipes to improve the user experience by transforming values for display. For example, use pipes to display dates and currency values that are appropriate for a user's locale. Angular provides predefined pipes for common transformations, and you can also define your own pipes.

* For data or logic that isn't associated with a specific view, and that you want to share across components, you create a service class. A service class definition is immediately preceded by the @Injectable() decorator. The decorator provides the metadata that allows other providers to be injected as dependencies into your class.

* The Angular Router NgModule provides a service that lets you define a navigation path among the different application states and view hierarchies in your app. It is modeled on the familiar browser navigation conventions:

    * Enter a URL in the address bar and the browser navigates to a corresponding page.

    * Click links on the page and the browser navigates to a new page.

    * Click the browser's back and forward buttons and the browser navigates backward and forward through the history of pages you've seen.

* Angular loads as a collection of JavaScript modules. You can think of them as library modules. Each Angular library name begins with the @angular prefix. Install them with the node package manager npm and import parts of them with JavaScript import statements.

* Angular libraries are NgModules, such as FormsModule, HttpClientModule, and RouterModule. Many third-party libraries are available as NgModules such as Material Design, Ionic, and AngularFire2