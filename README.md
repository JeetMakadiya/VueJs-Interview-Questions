# VueJs-Interview-Questions

### 1.What are Directives in Vue.js, List some of them you used?

 The concept of directive in Vue js is drastically simpler than that in Angular. Vue.js directives provides a way to extend HTML with new attributes and tags. Vue.js has a set of built-in directives which offers extended functionality to your applications.You can also write your custom directives in Vue.js 

- Below are list of commonly used directives in Vue.js

- v-show
- v-if
- v-model
- v-else
- v-on

### 2.What is Filters in VueJs?
A Filter is a simple JavaScript function which is used to apply formatting on output of a data to the browser. 
we can use filters in two different ways i.e. Global filter and Local filter.
Filters are usable in two places: mustache interpolations and v-bind expressions

### 3.What is Vue-loader in Vue.js?
The Vue-loader is a loader module for webpack in Vue.js that is used to write single file components using the .vue file format.

### 4.Why is it recommended not to use v-if and v-for directives together on the same element in Vue.js?
Because the v-for directive has a higher priority than v-if directive. If you use both directives together then v-if will be run on each iteration of the loop separately. This can be useful when you want to render nodes for only some items.
If your intent is to conditionally skip execution of the loop, you can place the v-if on a wrapper element (or <template>).
