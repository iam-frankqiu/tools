# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > for-of > brackets-var`

### `ast`

```javascript
JSRoot {
	body: [
		JSForOfStatement {
			await: false
			body: JSBlockStatement {
				body: []
				directives: []
				loc: SourceLocation es2015/for-of/brackets-var/input.js 1:21-1:23
			}
			left: JSVariableDeclaration {
				kind: "var"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingObjectPattern {
							properties: [
								JSBindingObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "a"
											loc: SourceLocation es2015/for-of/brackets-var/input.js 1:10-1:11 (a)
										}
										loc: SourceLocation es2015/for-of/brackets-var/input.js 1:10-1:11
									}
									value: JSBindingIdentifier {
										name: "a"
										loc: SourceLocation es2015/for-of/brackets-var/input.js 1:10-1:11 (a)
									}
									loc: SourceLocation es2015/for-of/brackets-var/input.js 1:10-1:11
								}
							]
							loc: SourceLocation es2015/for-of/brackets-var/input.js 1:9-1:12
						}
						loc: SourceLocation es2015/for-of/brackets-var/input.js 1:9-1:12
					}
				]
				loc: SourceLocation es2015/for-of/brackets-var/input.js 1:5-1:12
			}
			right: JSRegExpLiteral {
				global: false
				insensitive: false
				multiline: false
				noDotNewline: false
				sticky: false
				unicode: false
				expression: JSRegExpSubExpression {
					body: [
						JSRegExpCharacter {
							value: "b"
							loc: SourceLocation es2015/for-of/brackets-var/input.js 1:17-1:18
						}
					]
					loc: SourceLocation es2015/for-of/brackets-var/input.js 1:17-1:18
				}
				loc: SourceLocation es2015/for-of/brackets-var/input.js 1:16-1:19
			}
			loc: SourceLocation es2015/for-of/brackets-var/input.js 1:0-1:23
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: true
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/for-of/brackets-var/input.js>
	loc: SourceLocation es2015/for-of/brackets-var/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
