# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > selector5`

```javascript
CSSRoot {
	body: [
		CSSRule {
			prelude: [
				CSSSelector {
					patterns: [
						CSSTypeSelector {
							value: "a"
							loc: SourceLocation invalid/selector5/input.css 1:0-1:1
						}
					]
					loc: SourceLocation invalid/selector5/input.css 1:0-1:11
				}
				CSSSelector {
					patterns: []
					loc: SourceLocation invalid/selector5/input.css 1:11-1:19
				}
				CSSSelector {
					patterns: [
						CSSTypeSelector {
							value: "i"
							loc: SourceLocation invalid/selector5/input.css 1:20-1:21
						}
					]
					loc: SourceLocation invalid/selector5/input.css 1:19-1:22
				}
				CSSSelector {
					patterns: []
					loc: SourceLocation invalid/selector5/input.css 1:22-1:23
				}
				CSSSelector {
					patterns: []
					loc: SourceLocation invalid/selector5/input.css 1:23-1:24
				}
			]
			block: CSSBlock {
				value: [
					CSSDeclaration {
						name: "color"
						value: [
							CSSIdentifier {
								value: "purple"
								loc: SourceLocation invalid/selector5/input.css 2:9-2:15
							}
						]
						important: false
						loc: SourceLocation invalid/selector5/input.css 2:2-2:15
					}
				]
				startingTokenValue: "{"
				loc: SourceLocation invalid/selector5/input.css 1:24-3:1
			}
			loc: SourceLocation invalid/selector5/input.css 1:0-3:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<css>"}]
			description: {
				advice: [
					log {category: "info", text: [RAW_MARKUP {value: "Did you mean <emphasis>"}, "~=", RAW_MARKUP {value: "</emphasis>?"}]}
					diff {diff: [[0, "*"], [2, "~="]], language: "unknown"}
					log {
						category: "info"
						text: RAW_MARKUP {value: "Or one of these?"}
					}
					list {list: ["|=", "^=", "$=", "*=", "="], truncate: true}
				]
				category: ["parse"]
				categoryValue: "css"
				message: RAW_MARKUP {value: "Unknown attribute matcher."}
			}
			location: {
				language: "css"
				path: RelativePath<invalid/selector5/input.css>
				end: Position 1:10
				start: Position 1:9
			}
		}
	]
	path: RelativePath<invalid/selector5/input.css>
	loc: SourceLocation invalid/selector5/input.css 1:0-3:1
}
```
