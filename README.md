# Vue Collapse [![npm](https://img.shields.io/npm/dt/vue-collapse.svg)](https://www.npmjs.com/package/vue-collapse)[![npm](https://img.shields.io/npm/v/vue-collapse.svg)](https://www.npmjs.com/package/vue-collapse)[![npm](https://img.shields.io/npm/l/vue-collapse.svg)](https://www.npmjs.com/package/vue-collapse)[![GitHub stars](https://img.shields.io/github/stars/cezardasilva/vue-collapse.svg?style=social&label=Star)]()


> A simple collapse component for vue.js

# Instalation
```bash
npm install vue-collapse --save-dev
```

# Usage
```Vue
<template>
    <div>
        <collapse :selected="true">
			<div slot="collapse-header">

			</div>
			<div slot="collapse-body">

			</div>
		</collapse>
    </div>
</template>

<script>

import Collapse from 'vue-collapse'
export default {
	name: "YourComponent",
	components: {
	    Collapse
	}
}
</script>
```
