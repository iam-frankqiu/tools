# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > template-literal-invalid-escapes-tagged > 41`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSTaggedTemplateExpression {
				quasi: JSTemplateLiteral {
					expressions: []
					quasis: [
						JSTemplateElement {
							cooked: "\\u{g}"
							raw: "\\u{g}"
							tail: true
							loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/41/input.js 1:10-1:15
						}
					]
					loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/41/input.js 1:9-1:16
				}
				tag: JSReferenceIdentifier {
					name: "sampleTag"
					loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/41/input.js 1:0-1:9 (sampleTag)
				}
				loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/41/input.js 1:0-1:16
			}
			loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/41/input.js 1:0-1:16
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/template-literal-invalid-escapes-tagged/41/input.js>
	loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/41/input.js 1:0-1:16
}
```

### `diagnostics`

```

```
