# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 109`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 57
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 20
          index: 20
          line: 1
        }
        start: Object {
          column: 19
          index: 19
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 32
          index: 32
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 32
            index: 32
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'a'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 32
                  index: 32
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
              meta: PatternMeta {
                definite: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 32
                    index: 32
                    line: 1
                  }
                  start: Object {
                    column: 4
                    index: 4
                    line: 1
                  }
                }
                typeAnnotation: FlowObjectTypeAnnotation {
                  exact: false
                  inexact: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 32
                      index: 32
                      line: 1
                    }
                    start: Object {
                      column: 8
                      index: 8
                      line: 1
                    }
                  }
                  properties: Array [
                    FlowObjectTypeProperty {
                      kind: 'init'
                      key: Identifier {
                        name: 'x'
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 11
                            index: 11
                            line: 1
                          }
                          start: Object {
                            column: 10
                            index: 10
                            line: 1
                          }
                        }
                      }
                      value: NumberKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 19
                            index: 19
                            line: 1
                          }
                          start: Object {
                            column: 13
                            index: 13
                            line: 1
                          }
                        }
                      }
                      optional: false
                      proto: false
                      static: false
                      variance: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 19
                          index: 19
                          line: 1
                        }
                        start: Object {
                          column: 10
                          index: 10
                          line: 1
                        }
                      }
                    }
                    FlowObjectTypeProperty {
                      kind: 'init'
                      key: Identifier {
                        name: ''
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 20
                            index: 20
                            line: 1
                          }
                          start: Object {
                            column: 19
                            index: 19
                            line: 1
                          }
                        }
                      }
                      value: FlowGenericTypeAnnotation {
                        id: ReferenceIdentifier {
                          name: 'y'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 22
                              index: 22
                              line: 1
                            }
                            start: Object {
                              column: 21
                              index: 21
                              line: 1
                            }
                          }
                        }
                        typeParameters: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 22
                            index: 22
                            line: 1
                          }
                          start: Object {
                            column: 21
                            index: 21
                            line: 1
                          }
                        }
                      }
                      optional: false
                      proto: false
                      static: false
                      variance: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 22
                          index: 22
                          line: 1
                        }
                        start: Object {
                          column: 19
                          index: 19
                          line: 1
                        }
                      }
                    }
                    FlowObjectTypeProperty {
                      kind: 'init'
                      key: Identifier {
                        name: ''
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 23
                            index: 23
                            line: 1
                          }
                          start: Object {
                            column: 22
                            index: 22
                            line: 1
                          }
                        }
                      }
                      value: StringKeywordTypeAnnotation {
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 30
                            index: 30
                            line: 1
                          }
                          start: Object {
                            column: 24
                            index: 24
                            line: 1
                          }
                        }
                      }
                      optional: false
                      proto: false
                      static: false
                      variance: undefined
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 30
                          index: 30
                          line: 1
                        }
                        start: Object {
                          column: 22
                          index: 22
                          line: 1
                        }
                      }
                    }
                  ]
                }
              }
            }
            init: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 32
                index: 32
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
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 56
          index: 56
          line: 1
        }
        start: Object {
          column: 33
          index: 33
          line: 1
        }
      }
      expression: AssignmentExpression {
        operator: '='
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 55
            index: 55
            line: 1
          }
          start: Object {
            column: 33
            index: 33
            line: 1
          }
        }
        left: AssignmentIdentifier {
          name: 'INVALID_PLACEHOLDER'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 34
              index: 34
              line: 1
            }
            start: Object {
              column: 33
              index: 33
              line: 1
            }
          }
        }
        right: ObjectExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 55
              index: 55
              line: 1
            }
            start: Object {
              column: 37
              index: 37
              line: 1
            }
          }
          properties: Array [
            ObjectProperty {
              key: StaticPropertyKey {
                value: Identifier {
                  name: 'x'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 40
                      index: 40
                      line: 1
                    }
                    start: Object {
                      column: 39
                      index: 39
                      line: 1
                    }
                  }
                }
                variance: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 40
                    index: 40
                    line: 1
                  }
                  start: Object {
                    column: 39
                    index: 39
                    line: 1
                  }
                }
              }
              value: NumericLiteral {
                value: 0
                format: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 43
                    index: 43
                    line: 1
                  }
                  start: Object {
                    column: 42
                    index: 42
                    line: 1
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 43
                  index: 43
                  line: 1
                }
                start: Object {
                  column: 39
                  index: 39
                  line: 1
                }
              }
            }
            ObjectProperty {
              key: StaticPropertyKey {
                value: Identifier {
                  name: 'y'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 46
                      index: 46
                      line: 1
                    }
                    start: Object {
                      column: 45
                      index: 45
                      line: 1
                    }
                  }
                }
                variance: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 46
                    index: 46
                    line: 1
                  }
                  start: Object {
                    column: 45
                    index: 45
                    line: 1
                  }
                }
              }
              value: StringLiteral {
                value: 'foo'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 53
                    index: 53
                    line: 1
                  }
                  start: Object {
                    column: 48
                    index: 48
                    line: 1
                  }
                }
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 53
                  index: 53
                  line: 1
                }
                start: Object {
                  column: 45
                  index: 45
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
