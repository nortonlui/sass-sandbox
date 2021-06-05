# SASS Sandbox

Mini projeto para estudo do SASS. Faz uso de variáveis, nesting, functions e mixins.

```
@import 'variables';
@import 'functions';
@import 'mixins';

* {
  margin: 0;
  padding: 0;
}

body {
  background: $light-color;
  /* Example function */
  color: set-text-color($light-color);
  font-family: $font-stack;
  line-height: 1.5;
}
```
