# moodle_tool_vue

Tool plugin to deliver vue and vue-router for Moodle plugins

This plugins helps to deliver Vue and Vue-router as AMD modules in Moodle.

## Installing
extract the files in `admin/tool/vue` folder and run the Moodle upgrade

```sh
php admin/cli/upgrade.php
```

## Using the modules

The modules will be available for use in other modules by importing them. 

> You can find example of uses  in https://github.com/davisonajr/moodle_local_vue.

### using ES2015 syntax

* Vue 2.7.14 - `import Vue from 'tool_vue/vue2';`
* Vue 3.3.4 - `import { createApp } from 'tool_vue/vue3';`
* Vue Router for Vue 2.7.14 - `import VueRouter from 'tool_vue/vue2-router';`
* Vue Router for Vue 3.3.4 - `import VueRouter from 'tool_vue/vue3-router';`