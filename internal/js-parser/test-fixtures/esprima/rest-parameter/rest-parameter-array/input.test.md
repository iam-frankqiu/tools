# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > rest-parameter > rest-parameter-array`

### `ast`

```javascript
JSRoot {
	body: [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "f"
				loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:9-1:10 (f)
			}
			body: JSBlockStatement {
				body: []
				directives: []
				loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:19-1:21
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: []
				rest: JSBindingArrayPattern {
					elements: [
						JSBindingIdentifier {
							name: "a"
							meta: JSPatternMeta {
								loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:15-1:16
							}
							loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:15-1:16 (a)
						}
					]
					meta: JSPatternMeta {
						loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:14-1:17
					}
					loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:14-1:17
				}
				loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:10-1:18
			}
			loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:0-1:21
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/rest-parameter/rest-parameter-array/input.js>
	loc: SourceLocation esprima/rest-parameter/rest-parameter-array/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
