# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > template-literal-invalid-escapes-tagged > 9`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
		end: Object {
			column: 14
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
				end: Object {
					column: 14
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSTaggedTemplateExpression {
				typeArguments: undefined
				loc: Object {
					filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				tag: JSReferenceIdentifier {
					name: "sampleTag"
					loc: Object {
						filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
						identifierName: "sampleTag"
						end: Object {
							column: 9
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				quasi: JSTemplateLiteral {
					expressions: Array []
					loc: Object {
						filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
						end: Object {
							column: 14
							line: 1
						}
						start: Object {
							column: 9
							line: 1
						}
					}
					quasis: Array [
						JSTemplateElement {
							cooked: "\\xg"
							raw: "\\xg"
							tail: true
							loc: Object {
								filename: "experimental/template-literal-invalid-escapes-tagged/9/input.js"
								end: Object {
									column: 13
									line: 1
								}
								start: Object {
									column: 10
									line: 1
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
