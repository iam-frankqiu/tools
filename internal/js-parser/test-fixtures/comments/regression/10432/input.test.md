# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `comments > regression > 10432`

### `ast`

```javascript
JSRoot {
	body: [
		JSVariableDeclarationStatement {
			trailingComments: ["0"]
			declaration: JSVariableDeclaration {
				kind: "const"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "socket"
							loc: SourceLocation comments/regression/10432/input.js 1:6-1:12 (socket)
						}
						init: JSCallExpression {
							arguments: [
								JSReferenceIdentifier {
									name: "address"
									loc: SourceLocation comments/regression/10432/input.js 1:28-1:35 (address)
								}
							]
							callee: JSReferenceIdentifier {
								name: "socketClient"
								loc: SourceLocation comments/regression/10432/input.js 1:15-1:27 (socketClient)
							}
							loc: SourceLocation comments/regression/10432/input.js 1:15-1:36
						}
						loc: SourceLocation comments/regression/10432/input.js 1:6-1:36
					}
				]
				loc: SourceLocation comments/regression/10432/input.js 1:0-1:36
			}
			loc: SourceLocation comments/regression/10432/input.js 1:0-1:36
		}
		JSExpressionStatement {
			leadingComments: ["0"]
			expression: JSCallExpression {
				arguments: [
					JSStringLiteral {
						value: "connect"
						loc: SourceLocation comments/regression/10432/input.js 3:10-3:19
					}
					JSFunctionExpression {
						body: JSBlockStatement {
							body: [
								JSExpressionStatement {
									expression: JSCallExpression {
										arguments: [
											JSBinaryExpression {
												operator: "+"
												left: JSStringLiteral {
													value: "Connected to "
													loc: SourceLocation comments/regression/10432/input.js 4:8-4:23
												}
												right: JSReferenceIdentifier {
													name: "address"
													loc: SourceLocation comments/regression/10432/input.js 4:26-4:33 (address)
												}
												loc: SourceLocation comments/regression/10432/input.js 4:8-4:33
											}
										]
										callee: JSReferenceIdentifier {
											name: "debug"
											loc: SourceLocation comments/regression/10432/input.js 4:2-4:7 (debug)
										}
										loc: SourceLocation comments/regression/10432/input.js 4:2-4:34
									}
									loc: SourceLocation comments/regression/10432/input.js 4:2-4:34
								}
							]
							directives: []
							loc: SourceLocation comments/regression/10432/input.js 3:33-5:1
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation comments/regression/10432/input.js 3:30-3:32
						}
						loc: SourceLocation comments/regression/10432/input.js 3:21-5:1
					}
				]
				callee: JSMemberExpression {
					object: JSReferenceIdentifier {
						name: "socket"
						loc: SourceLocation comments/regression/10432/input.js 3:0-3:6 (socket)
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "on"
							loc: SourceLocation comments/regression/10432/input.js 3:7-3:9 (on)
						}
						loc: SourceLocation comments/regression/10432/input.js 3:7-3:9 (on)
					}
					loc: SourceLocation comments/regression/10432/input.js 3:0-3:9
				}
				loc: SourceLocation comments/regression/10432/input.js 3:0-5:2
			}
			loc: SourceLocation comments/regression/10432/input.js 3:0-5:2
		}
	]
	comments: [
		CommentBlock {
			id: "0"
			value: " istanbul ignore next "
			loc: SourceLocation comments/regression/10432/input.js 2:0-2:26
		}
	]
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<comments/regression/10432/input.js>
	loc: SourceLocation comments/regression/10432/input.js 1:0-6:0
}
```

### `diagnostics`

```

```
