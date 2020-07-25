# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > declare > var`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/declare/var/input.ts"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/declare/var/input.ts"
		end: Object {
			column: 0
			index: 35
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			declare: true
			loc: Object {
				filename: "typescript/declare/var/input.ts"
				end: Object {
					column: 14
					index: 14
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "typescript/declare/var/input.ts"
					end: Object {
						column: 14
						index: 14
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
								filename: "typescript/declare/var/input.ts"
								identifierName: "x"
								end: Object {
									column: 13
									index: 13
									line: 1
								}
								start: Object {
									column: 12
									index: 12
									line: 1
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/declare/var/input.ts"
							end: Object {
								column: 13
								index: 13
								line: 1
							}
							start: Object {
								column: 12
								index: 12
								line: 1
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			declare: true
			loc: Object {
				filename: "typescript/declare/var/input.ts"
				end: Object {
					column: 19
					index: 34
					line: 2
				}
				start: Object {
					column: 0
					index: 15
					line: 2
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "typescript/declare/var/input.ts"
					end: Object {
						column: 19
						index: 34
						line: 2
					}
					start: Object {
						column: 0
						index: 15
						line: 2
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "typescript/declare/var/input.ts"
								end: Object {
									column: 18
									index: 33
									line: 2
								}
								start: Object {
									column: 12
									index: 27
									line: 2
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/declare/var/input.ts"
									end: Object {
										column: 18
										index: 33
										line: 2
									}
									start: Object {
										column: 12
										index: 27
										line: 2
									}
								}
								typeAnnotation: TSAnyKeywordTypeAnnotation {
									loc: Object {
										filename: "typescript/declare/var/input.ts"
										end: Object {
											column: 18
											index: 33
											line: 2
										}
										start: Object {
											column: 15
											index: 30
											line: 2
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/declare/var/input.ts"
							end: Object {
								column: 18
								index: 33
								line: 2
							}
							start: Object {
								column: 12
								index: 27
								line: 2
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