# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 280`

### `ast`

```javascript
JSRoot {
	body: [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "x"
				loc: SourceLocation es2015/uncategorised/280/input.js 1:23-1:24 (x)
			}
			body: JSBlockStatement {
				body: []
				directives: []
				loc: SourceLocation es2015/uncategorised/280/input.js 1:34-1:36
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: [
					JSBindingIdentifier {
						name: "a"
						meta: JSPatternMeta {
							loc: SourceLocation es2015/uncategorised/280/input.js 1:25-1:26
						}
						loc: SourceLocation es2015/uncategorised/280/input.js 1:25-1:26 (a)
					}
					JSBindingObjectPattern {
						properties: [
							JSBindingObjectPatternProperty {
								key: JSStaticPropertyKey {
									value: JSIdentifier {
										name: "a"
										loc: SourceLocation es2015/uncategorised/280/input.js 1:30-1:31 (a)
									}
									loc: SourceLocation es2015/uncategorised/280/input.js 1:30-1:31
								}
								value: JSBindingIdentifier {
									name: "a"
									loc: SourceLocation es2015/uncategorised/280/input.js 1:30-1:31 (a)
								}
								loc: SourceLocation es2015/uncategorised/280/input.js 1:30-1:31
							}
						]
						meta: JSPatternMeta {
							loc: SourceLocation es2015/uncategorised/280/input.js 1:28-1:33
						}
						loc: SourceLocation es2015/uncategorised/280/input.js 1:28-1:33
					}
				]
				loc: SourceLocation es2015/uncategorised/280/input.js 1:24-1:34
			}
			loc: SourceLocation es2015/uncategorised/280/input.js 1:14-1:36
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: [
					log {
						category: "info"
						text: RAW_MARKUP {value: "Defined already here"}
					}
					frame {
						location: SourceLocation es2015/uncategorised/280/input.js 1:30-1:31 (a)
					}
				]
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "Argument <emphasis>"}, "a", RAW_MARKUP {value: "</emphasis> name clash in strict mode"}]
			}
			location: {
				language: "js"
				path: UIDPath<es2015/uncategorised/280/input.js>
				end: Position 1:31
				start: Position 1:30
			}
		}
	]
	directives: [
		JSDirective {
			value: "use strict"
			loc: SourceLocation es2015/uncategorised/280/input.js 1:0-1:13
		}
	]
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/uncategorised/280/input.js>
	loc: SourceLocation es2015/uncategorised/280/input.js 1:0-1:36
}
```

### `diagnostics`

```

 es2015/uncategorised/280/input.js:1:30 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Argument a name clash in strict mode

  ℹ Defined already here

    "use strict"; function x(a, { a }){}
                                  ^


```
