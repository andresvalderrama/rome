# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > scope > undecl-export-as`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 53
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 30
					index: 30
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 27
							index: 27
							line: 1
						}
						start: Object {
							column: 9
							index: 9
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "decrypt"
						loc: Object {
							filename: "input.js"
							identifierName: "decrypt"
							end: Object {
								column: 27
								index: 27
								line: 1
							}
							start: Object {
								column: 20
								index: 20
								line: 1
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "encrypt"
						loc: Object {
							filename: "input.js"
							identifierName: "encrypt"
							end: Object {
								column: 16
								index: 16
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
					}
				}
			]
		}
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "decrypt"
				loc: Object {
					filename: "input.js"
					identifierName: "decrypt"
					end: Object {
						column: 16
						index: 47
						line: 2
					}
					start: Object {
						column: 9
						index: 40
						line: 2
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 21
					index: 52
					line: 2
				}
				start: Object {
					column: 0
					index: 31
					line: 2
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 21
						index: 52
						line: 2
					}
					start: Object {
						column: 19
						index: 50
						line: 2
					}
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 18
						index: 49
						line: 2
					}
					start: Object {
						column: 16
						index: 47
						line: 2
					}
				}
			}
		}
	]
}
```
