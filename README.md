# Vue-Snippet
Vuejs snippet to single file component, based in vuejs documentation
## Vscode
- Ctrl + P
- Type: Configure user snippets
- Select vue.json
- Paste

```
{
	"Vue Snippet": {
		"prefix": ["vueSnippet"],
		"body": [
			"<template>",
				"  <div>",
				"    Hello world",
				"  </div>",
			"</template>",
			"",
			"<script>",
			"export default {",
				"  name: 'ComponentName',",
				"  components: {},",
				"  directives: {},",
				"  mixins: [],",
				"  provide: {},",
				"  inject: [],",
				"  props: {",
				"    myProp: {",
				"      type: String,",
				"      default: ''",
				"    }",
				"  },",
				"  emits: [],",
				"  data: () => ({}),",
				"  computed: {},",
				"  watch: {},",
				"  created() {},",
				"  mounted() {},",
				"  deactivated() {},",
				"  methods: {}",
			"}",
			"</script>",
			"",
			"<style lang=\"scss\"></style>",
			""
		],
		"description": "Vuejs snippet to single file component, based in vuejs documentation: https://vuejs.org/style-guide/rules-recommended.html#component-instance-options-order"
	},
}
