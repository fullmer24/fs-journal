# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
In Vue.js, we do not have to write a lot of lines to have two-way data binding, unlike other frameworks. One-way data binding means that the variable is just bound to the DOM. On the other hand, two-way means that the variable is also bound from the DOM.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```

```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is a hook registration function. These lifecycle hook registration functions can only be used synchronously during setup (), since they rely on internal global state to locate the current active instance (the component instance whose setup () is being called right now)
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model attribute is a way of creating a mutual binding between the user input and the vue.js component. This will automatically pick up changes and store this value in the data properties of the component. This will be commonly used on form input to record the user input.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
In Vue, the v-on directive is how you run JavaScript in response to DOM events. If you want to run some code when the user clicks a button, you should use v-on.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-show
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
It's for keeping track of items within an array
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
Slots are reserved space offered by vue.js to display content passed down from one component to another. There are two types of slot in vue.js: named slot and unnamed (default) slot
```