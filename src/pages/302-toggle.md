---

title: Toggle
name: toggle
category: modules
subcategory: General modules
layout: q+tq
id: toggle-page

---

<p class="lead">General class for using a _button_ to toggle a _class_ on a _container_.</p>

### Use

```javascript
var t = new TOGGLE({
  container: $('.toggle-container'),
  button: $('.toggle-button'),
  class: 'is-toggled'
})
```


### Options

  Pass an _options_ object with the following keys:

  * **container** - the element on which to toggle the class (required)
  * **button** - the element to listen for a click (required)
  * **class** - the class to toggle (optional - defaults to `is-open`)