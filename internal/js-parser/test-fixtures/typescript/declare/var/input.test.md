# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > declare > var`

### `ast`

```javascript
JSRoot {
	body: [
		JSVariableDeclarationStatement {
			declare: true
			declaration: JSVariableDeclaration {
				kind: "var"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: SourceLocation typescript/declare/var/input.ts 1:12-1:13 (x)
						}
						loc: SourceLocation typescript/declare/var/input.ts 1:12-1:13
					}
				]
				loc: SourceLocation typescript/declare/var/input.ts 1:0-1:14
			}
			loc: SourceLocation typescript/declare/var/input.ts 1:0-1:14
		}
		JSVariableDeclarationStatement {
			declare: true
			declaration: JSVariableDeclaration {
				kind: "var"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							meta: JSPatternMeta {
								typeAnnotation: TSAnyKeywordTypeAnnotation {
									loc: SourceLocation typescript/declare/var/input.ts 2:15-2:18
								}
								loc: SourceLocation typescript/declare/var/input.ts 2:12-2:18
							}
							loc: SourceLocation typescript/declare/var/input.ts 2:12-2:18
						}
						loc: SourceLocation typescript/declare/var/input.ts 2:12-2:18
					}
				]
				loc: SourceLocation typescript/declare/var/input.ts 2:0-2:19
			}
			loc: SourceLocation typescript/declare/var/input.ts 2:0-2:19
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: true
	sourceType: "module"
	syntax: ["ts"]
	path: UIDPath<typescript/declare/var/input.ts>
	loc: SourceLocation typescript/declare/var/input.ts 1:0-3:0
}
```

### `diagnostics`

```

```
