# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > tuple-rest`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/types/tuple-rest/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/types/tuple-rest/input.ts"
		end: Object {
			column: 0
			index: 29
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/tuple-rest/input.ts"
				end: Object {
					column: 28
					index: 28
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/tuple-rest/input.ts"
					end: Object {
						column: 28
						index: 28
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "typescript/types/tuple-rest/input.ts"
								end: Object {
									column: 28
									index: 28
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/tuple-rest/input.ts"
									end: Object {
										column: 28
										index: 28
										line: 1
									}
									start: Object {
										column: 4
										index: 4
										line: 1
									}
								}
								typeAnnotation: TSTupleType {
									loc: Object {
										filename: "typescript/types/tuple-rest/input.ts"
										end: Object {
											column: 28
											index: 28
											line: 1
										}
										start: Object {
											column: 7
											index: 7
											line: 1
										}
									}
									elementTypes: Array [
										TSTupleElement {
											name: undefined
											optional: false
											loc: Object {
												filename: "typescript/types/tuple-rest/input.ts"
												end: Object {
													column: 14
													index: 14
													line: 1
												}
												start: Object {
													column: 8
													index: 8
													line: 1
												}
											}
											typeAnnotation: TSStringKeywordTypeAnnotation {
												loc: Object {
													filename: "typescript/types/tuple-rest/input.ts"
													end: Object {
														column: 14
														index: 14
														line: 1
													}
													start: Object {
														column: 8
														index: 8
														line: 1
													}
												}
											}
										}
									]
									rest: TSTupleElement {
										name: undefined
										optional: false
										loc: Object {
											filename: "typescript/types/tuple-rest/input.ts"
											end: Object {
												column: 27
												index: 27
												line: 1
											}
											start: Object {
												column: 16
												index: 16
												line: 1
											}
										}
										typeAnnotation: TSArrayType {
											loc: Object {
												filename: "typescript/types/tuple-rest/input.ts"
												end: Object {
													column: 27
													index: 27
													line: 1
												}
												start: Object {
													column: 19
													index: 19
													line: 1
												}
											}
											elementType: TSNumberKeywordTypeAnnotation {
												loc: Object {
													filename: "typescript/types/tuple-rest/input.ts"
													end: Object {
														column: 25
														index: 25
														line: 1
													}
													start: Object {
														column: 19
														index: 19
														line: 1
													}
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/tuple-rest/input.ts"
							end: Object {
								column: 28
								index: 28
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```