# Modules

#### formerly known as layouts

Modules are components that can control logic, layout and access for descendent components.

Components are written as `_module.svelte`.

```html
<!-- _module.svelte -->

<slot>
  <!-- pages in this folder and subfolders
   will be rendered here -->
</slot>
<p>Copyright my website 2020</p>
```