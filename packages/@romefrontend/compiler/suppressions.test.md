# `suppressions.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/compiler/suppressions.test.ts --update-snapshots` to update.

## `duplicates`

```javascript
Object {
	diagnostics: Array [
		Object {
			description: Object {
				advice: Array []
				category: "suppressions/duplicate"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Duplicate suppression category <emphasis>dog</emphasis>"}
			}
			location: Object {
				filename: "unknown"
				end: Object {
					column: 22
					index: 22
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		Object {
			description: Object {
				advice: Array []
				category: "suppressions/duplicate"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Duplicate suppression category <emphasis>dog</emphasis>"}
			}
			location: Object {
				filename: "unknown"
				end: Object {
					column: 26
					index: 57
					line: 4
				}
				start: Object {
					column: 0
					index: 31
					line: 4
				}
			}
		}
	]
	suppressions: Array [
		Object {
			category: "dog"
			endLine: 2
			filename: "unknown"
			startLine: 2
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 22
					index: 22
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		Object {
			category: "dog"
			endLine: 5
			filename: "unknown"
			startLine: 5
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 26
					index: 57
					line: 4
				}
				start: Object {
					column: 0
					index: 31
					line: 4
				}
			}
		}
		Object {
			category: "cat"
			endLine: 5
			filename: "unknown"
			startLine: 5
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 26
					index: 57
					line: 4
				}
				start: Object {
					column: 0
					index: 31
					line: 4
				}
			}
		}
	]
}
```

## `multiple categories`

```javascript
Object {
	diagnostics: Array []
	suppressions: Array [
		Object {
			category: "foo"
			endLine: 2
			filename: "unknown"
			startLine: 2
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 22
					index: 22
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		Object {
			category: "dog"
			endLine: 2
			filename: "unknown"
			startLine: 2
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 22
					index: 22
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		Object {
			category: "bar"
			endLine: 5
			filename: "unknown"
			startLine: 5
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 26
					index: 57
					line: 4
				}
				start: Object {
					column: 0
					index: 31
					line: 4
				}
			}
		}
		Object {
			category: "cat"
			endLine: 5
			filename: "unknown"
			startLine: 5
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 26
					index: 57
					line: 4
				}
				start: Object {
					column: 0
					index: 31
					line: 4
				}
			}
		}
		Object {
			category: "yes"
			endLine: 10
			filename: "unknown"
			startLine: 10
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 3
					index: 97
					line: 9
				}
				start: Object {
					column: 0
					index: 66
					line: 7
				}
			}
		}
		Object {
			category: "frog"
			endLine: 10
			filename: "unknown"
			startLine: 10
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 3
					index: 97
					line: 9
				}
				start: Object {
					column: 0
					index: 66
					line: 7
				}
			}
		}
		Object {
			category: "wow"
			endLine: 16
			filename: "unknown"
			startLine: 16
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 3
					index: 146
					line: 15
				}
				start: Object {
					column: 0
					index: 106
					line: 12
				}
			}
		}
		Object {
			category: "fish"
			endLine: 16
			filename: "unknown"
			startLine: 16
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 3
					index: 146
					line: 15
				}
				start: Object {
					column: 0
					index: 106
					line: 12
				}
			}
		}
	]
}
```

## `single category`

```javascript
Object {
	diagnostics: Array []
	suppressions: Array [
		Object {
			category: "foo"
			endLine: 2
			filename: "unknown"
			startLine: 2
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 18
					index: 18
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		Object {
			category: "bar"
			endLine: 5
			filename: "unknown"
			startLine: 5
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 22
					index: 49
					line: 4
				}
				start: Object {
					column: 0
					index: 27
					line: 4
				}
			}
		}
		Object {
			category: "yes"
			endLine: 10
			filename: "unknown"
			startLine: 10
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 3
					index: 84
					line: 9
				}
				start: Object {
					column: 0
					index: 58
					line: 7
				}
			}
		}
		Object {
			category: "wow"
			endLine: 16
			filename: "unknown"
			startLine: 16
			commentLocation: Object {
				filename: "unknown"
				end: Object {
					column: 3
					index: 128
					line: 15
				}
				start: Object {
					column: 0
					index: 93
					line: 12
				}
			}
		}
	]
}
```