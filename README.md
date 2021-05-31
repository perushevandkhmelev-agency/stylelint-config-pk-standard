# stylelint-config-pk-standard

## Install

```sh
yarn add stylelint-config-recommended stylelint-order stylelint-config-pk-standard --dev
```

## Usage

```javascript
// .stylelintrc
{
  "extends": ["stylelint-config-pk-standard"]
}
```

## Rules

| rule                                      | option                                                         |
| :---------------------------------------- | :------------------------------------------------------------- |
| declaration-block-no-duplicate-properties | true                                                           |
| block-no-empty                            | true                                                           |
| font-weight-notation                      | named-where-possible                                           |
| selector-pseudo-class-no-unknown          | true                                                           |
| selector-pseudo-element-no-unknown        | true                                                           |
| selector-type-no-unknown                  | [true, { "ignore": ["custom-elements", "default-namespace"] }] |
| no-extra-semicolons                       | true                                                           |
| shorthand-property-no-redundant-values    | true                                                           |
| declaration-no-important                  | true                                                           |
| function-comma-space-after                | always                                                         |
| function-comma-space-before               | never                                                          |
| function-max-empty-lines                  | 0                                                              |
| function-name-case                        | lower                                                          |
| function-parentheses-space-inside         | never                                                          |
| function-url-quotes                       | always                                                         |
| number-leading-zero                       | always                                                         |
| number-no-trailing-zeros                  | true                                                           |
| unit-case                                 | lower                                                          |
| value-list-comma-space-after              | always-single-line                                             |
| value-list-comma-space-before             | never                                                          |
| value-list-max-empty-lines                | 0                                                              |
| custom-property-empty-line-before         | never                                                          |
| property-case                             | lower                                                          |
| declaration-bang-space-after              | never                                                          |
| declaration-bang-space-before             | always                                                         |
| declaration-colon-space-after             | always                                                         |
| declaration-colon-space-before            | never                                                          |
| declaration-block-semicolon-newline-after | always                                                         |
| declaration-block-semicolon-space-before  | never                                                          |
| declaration-block-trailing-semicolon      | always                                                         |
| block-closing-brace-empty-line-before     | never                                                          |
| block-closing-brace-newline-after         | always                                                         |
| block-closing-brace-newline-before        | always                                                         |
| block-opening-brace-space-before          | always                                                         |
| selector-list-comma-newline-after         | always                                                         |
| selector-list-comma-newline-before        | never-multi-line                                               |
| rule-empty-line-before                    | ["always", { "except": "first-nested" }]                       |
| at-rule-empty-line-before                 | ["always", { "except": "first-nested" }]                       |
| at-rule-name-case                         | lower                                                          |
| at-rule-name-space-after                  | always                                                         |
| at-rule-semicolon-newline-after           | always                                                         |
| at-rule-semicolon-space-before            | never                                                          |
| comment-whitespace-inside                 | always                                                         |
| indentation                               | 2                                                              |
| max-empty-lines                           | 1                                                              |
| no-eol-whitespace                         | true                                                           |
| no-empty-first-line                       | true                                                           |
| no-descending-specificity                 | null                                                           |
| property-no-vendor-prefix                 | null                                                           |
| properties-order                          | yandex                                                         |
