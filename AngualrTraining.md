# Angular Training
[`Angular Playground`](https://stackblitz.com/fork/angular)

## Index
1. [Typescript Basic](#1-typescript-basic)
2. [Data Types, Functions and Variables](#2-data-types-functions-and-variables)
3. [Angular Architecture](#3-angular-architecture)
4. [Directives, Pipes and Templates](#4-directives-pipes-and-templates)
5. [Data Binding](#5-data-binding)
6. [Styles Binding In Components](#6-styles-binding-in-components)
7. [Advanced Components Features](#7-advanced-components-features)
8. [Template Driven Forms](#8-template-driven-forms)
9. [Model Driven Forms](#9-model-driven-forms)
10. [Working with Pipes](#10-working-with-pipes)
11. [Custom Attribute and Validators](#11-custom-attribute-and-validators)
12. [Dependency Injection](#12-dependency-injection)
13. [Services](#13-services)
14. [Routing](#14-routing)
15. [Module](#15-module)
16. [Crud Operations Using Http Service](#16-crud-operations-using-http-service)
17. [RxJs](#17-rxjs)
18. [NgRx State Managemcnt](#18-ngrx-state-managemcnt)
19. [Unit Testing](#19-unit-testing)

## 1. Typescript Basic
In order to enter into the world of Angular application development, typescript is necessary and it is the primary language here. Typescript is a superset of JavaScript. It comes with design-time support which is useful for type safety and tooling. Since, browsers cannot execute the TypeScript directly, it will be ‘Transpiled’ into JavaScript using the tsc compiler.<br/>
* What is Typescript?
* Benefits of Typescript.
* Setup the Environment.<br/>

[`Typescript a Beginners Guide`](https://www.typescriptlang.org/docs/handbook/2/basic-types.html)<br/>
[`TypeScript Playground`](https://www.typescriptlang.org/play)

[`🔼 Go To Index`](#index)

## 2. Data Types, Functions and Variables
In this module, we will learn whet the datatypes that are used in typescript are, and wewill introduce into a new data type let.
* Basic Data Types (string, number, boolean)
* Arrays and Arrays Functions  `🚩Create list for Array functions`
* Any and void
* null and undefined
* Type Inference
* Type Casting
* Difference between let, var and const
* Optional and Default Parameters
* Rest Parameters
* Function Overloading
* Function Types
* Exporting and Importing of Modules
* Re-Export of Modules
* Default Exports

## 3. Angular Architecture
In this module, you will learn how angular and angular work and flow of the angularapplication in depth.
- Basic Building Blocks of Angular Applications
- Angular commands to Create
  - Application
  - Module
  - Component
  - Service
  - Directive
  - Pipe
  - Interceptor

## 4. Directives, Pipes and Templates
In this module, you will learn about directives, directives are the classes that can change the behavior or appearance of the components by using CSS Classes, CSS Styles and events Here you will find how to use directives in our application.
- Adding Properties to Components and Interpolation
- Creating a class for data (Model object)
- Template Expressions
- Working with Arrays and Build-in Directives
- Repeating Directive (NgFor) o Conditional Directives (Nglf, NgSwitch)
- •vs <tcmplate>
- External HTML Template File
- Pure and Impure pipes

## 5. Data Binding
In this module, you will learn how many kinds of databinding and we will discuss each ofthem in this chapter
- Binding properties and Interpolation
- One-way Binding / Property Binding
- Event Binding
- Two-way Binding
- Two-way binding with NL'Model
- Attribute Binding
- Banana Syntax

## 6. Styles Binding In Components
In this module, Angular applications are styled with regular CSS. That means we can apply everything we know about CSS stylesheets, selectors, rules, and media queriesto our Angular applications directly, this module will help you to how to apply css to our page.
- Style and Class Bindings
- Built-In Directives - NgStyle& NgCIass
- Using Component Styles
- Special sele«ors
- Loading Styles into Components

## 7. Advanced Components Features
In this module we Will learn one Of the major concept in angular4 i.e., components and wecan learn how to create dynamic component using ncComponent0utlet.
- What are Components?
- Understanding Components life cycle hooks
- Creating and using components
- Dynamic components using ngComponentOutlet

## 8. Template Driven Forms
In this module. you will learn in most of the frontend applications we use HTML forms for grouping HTML elements and we provlde validations using HTMLS attributes like required. mlnlength, maxlength, pattern etc.
- Two-way data binding with ngModel
- Add Custom CSS for Visual Feedback.
- Show and Hide Validation Error messages
- Resetting the form,
- Resettjng form state
- Submit the form with ngSubmit

## 9. Model Driven Forms
Model driven forms are more powerful and easy to do functionalities, which are complexwhen using template driven forms.
- Model Driven / Reactive Forms
- Form with @ViewChild
- Validations
- Custom
- Validators Submitting and Resetting form

## 10. Working with Pipes
In this module, you will learn about pipe, a pipe takes in data as input and transforms it to adesired output
- Built-in Pipes
- Using parameters
- Chaining Pipes
- Custom Pipes
- Pipes and Change Detection
- Pure and Impure pipes

## 11. Custom Attribute and Validators
In this module, you will learn about attribute and validators, Using custom attribute directive, we can change the color, back-ground, font-size etc., of the HTML host element byusing ElementRef
- Custom Attribute Directives
- Using HostListener
- Using HostBinding
- Example2: Custom Validators

## 12. Dependency Injection
In this module, we will learn Dependency Injection (DI) is the software design pattern in which a class receives its dependencies from external sources rather than creating them itself. In addition, we will learn about very interesting topic Dependency Injection in angular.
- Understanding Dependency Injection
- Understanding DI in Angular Framework
- Reflective Injector
- Exploring Provider
- Types of Tokens
- Types of Dependencies
- Configuring DI using Providers
- Implementing DI in Antular

## 13. Services
In this module, you will learn about services, In angular services are reusable classes whichcan be injected in components when it's needed. Using a separate service keeps components lean and focused on supporting the view, and makes it easy to unit test components with a mock service
- Services
- Service Using a Service
- http Services
- Get, Post, Put and Delete Requests

## 14. Routing
In this module we will learn the introduction for routing in angular and how to navigatebetween views, how to do parameterized routing.
- Introduction
- Configuring and Navigating
- Parameterized routes

## 15. Module
In this module, you will learn module, An NgModute dass is adorned with @NgModule decorator function this will tell the angular application hou to compile and run the moduiecode.
- Root App module
- Compilation
- Feature modules
- Lazy Loading a Module
- Shared Module

## 16. Crud Operations Using Http Service
In this module, we will create an application with end-to-end start from server to client. Getting response and requests using HTTP service.
- About Http Services
- Step 1: Setup Web Application project
- Step 2: Configuring Angular Module to use HTTP and Ecn Servtces,
- Step 3: Fetch data with http.€et
- Step 4: Sending data to Server/ Adding Employee details using http.post

## 17. RxJs
- About RxJS
- Observables
- Promise
- Subject
- BchaviorSubject
- of, map, forkJoin and other functions

## 18. NgRx State managemcnt
- About NcRÄ
- Manage state in Route, Global and Module level

## 19. Unit Testing
- Jasmine and Karma test cases writing
