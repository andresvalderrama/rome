# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > regression > issue-2114`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "jsx/regression/issue-2114/input.jsx"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array ["jsx"]
	loc: Object {
		filename: "jsx/regression/issue-2114/input.jsx"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "jsx/regression/issue-2114/input.jsx"
				end: Object {
					column: 51
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSXElement {
				name: JSXIdentifier {
					name: "div"
					loc: Object {
						filename: "jsx/regression/issue-2114/input.jsx"
						end: Object {
							column: 4
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
				}
				children: Array []
				selfClosing: false
				typeArguments: undefined
				loc: Object {
					filename: "jsx/regression/issue-2114/input.jsx"
					end: Object {
						column: 50
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				attributes: Array [
					JSXAttribute {
						name: JSXIdentifier {
							name: "pattern"
							loc: Object {
								filename: "jsx/regression/issue-2114/input.jsx"
								end: Object {
									column: 12
									line: 1
								}
								start: Object {
									column: 5
									line: 1
								}
							}
						}
						value: JSStringLiteral {
							value: "^([\\w\\.\\-]+\\s)*[\\w\\.\\-]+\\s?$"
							loc: Object {
								filename: "jsx/regression/issue-2114/input.jsx"
								end: Object {
									column: 43
									line: 1
								}
								start: Object {
									column: 13
									line: 1
								}
							}
						}
						loc: Object {
							filename: "jsx/regression/issue-2114/input.jsx"
							end: Object {
								column: 43
								line: 1
							}
							start: Object {
								column: 5
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
