# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > scope > export-enum-before`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "input.ts"
		end: Object {
			column: 12
			index: 40
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
				filename: "input.ts"
				end: Object {
					column: 26
					index: 26
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
						filename: "input.ts"
						end: Object {
							column: 24
							index: 24
							line: 1
						}
						start: Object {
							column: 9
							index: 9
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "default"
						loc: Object {
							filename: "input.ts"
							identifierName: "default"
							end: Object {
								column: 24
								index: 24
								line: 1
							}
							start: Object {
								column: 17
								index: 17
								line: 1
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "Test"
						loc: Object {
							filename: "input.ts"
							identifierName: "Test"
							end: Object {
								column: 13
								index: 13
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
		TSEnumDeclaration {
			id: JSBindingIdentifier {
				name: "Test"
				loc: Object {
					filename: "input.ts"
					identifierName: "Test"
					end: Object {
						column: 9
						index: 37
						line: 3
					}
					start: Object {
						column: 5
						index: 33
						line: 3
					}
				}
			}
			const: false
			members: Array []
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 12
					index: 40
					line: 3
				}
				start: Object {
					column: 0
					index: 28
					line: 3
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