# Vue Collapse [![apm](https://img.shields.io/apm/dm/vue-collapse.svg)](https://atom.io/packages/vue-collapse) [![apm](https://img.shields.io/apm/l/vue-collapse.svg?)](https://atom.io/packages/vue-collapse) [![apm](https://img.shields.io/apm/v/vue-collapse.svg?)](https://atom.io/packages/vue-collapse)

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
