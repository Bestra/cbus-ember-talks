# (de)Composing Components

---

# Components are the future

* Routes
* Services
* Components
* Templates

---
# The past was clear-cut

> Use a component when you want to make a widget that looks the same everywhere but has different application-level behavior in different places.

-- Me paraphrasing the Ember docs when components were first added

---
# The future is less so

> You're gonna have to use  a component because there's nothing else.

-- Me again

---
## Components are great for breaking up pages

https://www.mutuallyhuman.com/blog/2016/01/22/component-integration-testing-in-ember/

^^This post would've been way cooler if I'd have finished it 8 months ago.

---
## Components are also great for breaking up other components

---
# Components can have many roles

* Presentation
* Formatting
* Data Sources
* Coordinating other components(!)

---
## Your components could probably do less


---
# Bold Statement

If a component does multiple kinds of things you should break that component into smaller components that do each of those things.

* Fires off a promise _and_ renders the result or an error
* Shows a list of items _and_ saves an item
* Displays a *translated* list of items

---
## Everything I know about components I learned from React

(Okay maybe not everything)

[But they've lived in component land longer than us](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0#.ew55qvkge)

---
# Components don't have to display anything

`tagName: ""`

---
#  Single-purpose components are awesome

* Small (maybe)
* Reusable
* Testable
* Trustable

---
## Composition via template

* hbs is great for asynchrony
* hbs is declarative
* you're gonna have to use it anyways.
* composition != business logic


