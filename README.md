# pylint-errors

A list of pylint-errors with reasoning and examples of erroneous and
correct code.

## Table of contents

- [List of errors](#list-of-errors)

## List of errors

Error codes with **[+]** mean they've got examples of bad and good code.
Rationalisation provided for all entries.

### Async Checker Messages

- [E1700 (yield-inside-async-function)](https://aidenmitchell.github.io/pylint-errors/plerr/E1700) **[+]**
- [E1701 (not-async-context-manager)](https://aidenmitchell.github.io/pylint-errors/plerr/E1701) **[+]**

### Basic Checker Messages

- [C0102 (blacklisted-name)](https://aidenmitchell.github.io/pylint-errors/plerr/C0102) **[+]**
- [C0103 (invalid-name)](https://aidenmitchell.github.io/pylint-errors/plerr/C0103) **[+]**
- [C0112 (empty-docstring)](https://aidenmitchell.github.io/pylint-errors/plerr/C0112) **[+]**
- [C0114 (missing-module-docstring)](https://aidenmitchell.github.io/pylint-errors/plerr/C0114) **[+]**
- [C0115 (missing-class-docstring)](https://aidenmitchell.github.io/pylint-errors/plerr/C0115) **[+]**
- [C0116 (missing-function-docstring)](https://aidenmitchell.github.io/pylint-errors/plerr/C0116) **[+]**
- [C0121 (singleton-comparison)](https://aidenmitchell.github.io/pylint-errors/plerr/C0121) **[+]**
- [C0122 (misplaced-comparison-constant)](https://aidenmitchell.github.io/pylint-errors/plerr/C0122) **[+]**
- [C0123 (unidiomatic-typecheck)](https://aidenmitchell.github.io/pylint-errors/plerr/C0123) **[+]**
- [E0100 (init-is-generator)](https://aidenmitchell.github.io/pylint-errors/plerr/E0100) **[+]**
- [E0101 (return-in-init)](https://aidenmitchell.github.io/pylint-errors/plerr/E0101) **[+]**
- [E0102 (function-redefined)](https://aidenmitchell.github.io/pylint-errors/plerr/E0102) **[+]**
- [E0103 (not-in-loop)](https://aidenmitchell.github.io/pylint-errors/plerr/E0103) **[+]**
- [E0104 (return-outside-function)](https://aidenmitchell.github.io/pylint-errors/plerr/E0104) **[+]**
- [E0105 (yield-outside-function)](https://aidenmitchell.github.io/pylint-errors/plerr/E0105) **[+]**
- [E0106 (return-arg-in-generator)](https://aidenmitchell.github.io/pylint-errors/plerr/E0106)
- [E0107 (nonexistent-operator)](https://aidenmitchell.github.io/pylint-errors/plerr/E0107) **[+]**
- [E0108 (duplicate-argument-name)](https://aidenmitchell.github.io/pylint-errors/plerr/E0108) **[+]**
- [E0110 (abstract-class-instantiated)](https://aidenmitchell.github.io/pylint-errors/plerr/E0110) **[+]**
- [E0111 (bad-reversed-sequence)](https://aidenmitchell.github.io/pylint-errors/plerr/E0111) **[+]**
- [E0112 (too-many-star-expressions)](https://aidenmitchell.github.io/pylint-errors/plerr/E0112) **[+]**
- [E0113 (invalid-star-assignment-target)](https://aidenmitchell.github.io/pylint-errors/plerr/E0113) **[+]**
- [E0114 (star-needs-assignment-target)](https://aidenmitchell.github.io/pylint-errors/plerr/E0114) **[+]**
- [E0115 (nonlocal-and-global)](https://aidenmitchell.github.io/pylint-errors/plerr/E0115) **[+]**
- [E0116 (continue-in-finally)](https://aidenmitchell.github.io/pylint-errors/plerr/E0116) **[+]**
- [E0117 (nonlocal-without-binding)](https://aidenmitchell.github.io/pylint-errors/plerr/E0117) **[+]**
- [E0118 (used-prior-global-declaration)](https://aidenmitchell.github.io/pylint-errors/plerr/E0118) **[+]**
- [E0119 (misplaced-format-function)](https://aidenmitchell.github.io/pylint-errors/plerr/E0119) **[+]**
- [R0123 (literal-comparison)](https://aidenmitchell.github.io/pylint-errors/plerr/R0123) **[+]**
- [R0124 (comparison-with-itself)](https://aidenmitchell.github.io/pylint-errors/plerr/R0124) **[+]**
- [W0101 (unreachable)](https://aidenmitchell.github.io/pylint-errors/plerr/W0101) **[+]**
- [W0102 (dangerous-default-value)](https://aidenmitchell.github.io/pylint-errors/plerr/W0102) **[+]**
- [W0104 (pointless-statement)](https://aidenmitchell.github.io/pylint-errors/plerr/W0104) **[+]**
- [W0105 (pointless-string-statement)](https://aidenmitchell.github.io/pylint-errors/plerr/W0105) **[+]**
- [W0106 (expression-not-assigned)](https://aidenmitchell.github.io/pylint-errors/plerr/W0106) **[+]**
- [W0107 (unnecessary-pass)](https://aidenmitchell.github.io/pylint-errors/plerr/W0107) **[+]**
- [W0108 (unnecessary-lambda)](https://aidenmitchell.github.io/pylint-errors/plerr/W0108) **[+]**
- [W0109 (duplicate-key)](https://aidenmitchell.github.io/pylint-errors/plerr/W0109) **[+]**
- [W0111 (assign-to-new-keyword)](https://aidenmitchell.github.io/pylint-errors/plerr/W0111) **[+]**
- [W0120 (useless-else-on-loop)](https://aidenmitchell.github.io/pylint-errors/plerr/W0120) **[+]**
- [W0122 (exec-used)](https://aidenmitchell.github.io/pylint-errors/plerr/W0122) **[+]**
- [W0123 (eval-used)](https://aidenmitchell.github.io/pylint-errors/plerr/W0123) **[+]**
- [W0124 (confusing-with-statement)](https://aidenmitchell.github.io/pylint-errors/plerr/W0124) **[+]**
- [W0125 (using-constant-test)](https://aidenmitchell.github.io/pylint-errors/plerr/W0125)
- [W0126 (missing-parentheses-for-call-in-test)](https://aidenmitchell.github.io/pylint-errors/plerr/W0126)
- [W0127 (self-assigning-variable)](https://aidenmitchell.github.io/pylint-errors/plerr/W0127) **[+]**
- [W0128 (redeclared-assigned-name)](https://aidenmitchell.github.io/pylint-errors/plerr/W0128)
- [W0143 (comparison-with-callable)](https://aidenmitchell.github.io/pylint-errors/plerr/W0143) **[+]**
- [W0150 (lost-exception)](https://aidenmitchell.github.io/pylint-errors/plerr/W0150) **[+]**
- [W0199 (assert-on-tuple)](https://aidenmitchell.github.io/pylint-errors/plerr/W0199) **[+]**

### Broad Try Clause Checker Messages

- [W0717 (too-many-try-statements)](https://aidenmitchell.github.io/pylint-errors/plerr/W0717)

### Classes Checker Messages

- [C0202 (bad-classmethod-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/C0202) **[+]**
- [C0203 (bad-mcs-method-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/C0203) **[+]**
- [C0204 (bad-mcs-classmethod-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/C0204) **[+]**
- [C0205 (single-string-used-for-slots)](https://aidenmitchell.github.io/pylint-errors/plerr/C0205) **[+]**
- [E0202 (method-hidden)](https://aidenmitchell.github.io/pylint-errors/plerr/E0202) **[+]**
- [E0203 (access-member-before-definition)](https://aidenmitchell.github.io/pylint-errors/plerr/E0203) **[+]**
- [E0211 (no-method-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/E0211) **[+]**
- [E0213 (no-self-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/E0213) **[+]**
- [E0236 (invalid-slots-object)](https://aidenmitchell.github.io/pylint-errors/plerr/E0236) **[+]**
- [E0237 (assigning-non-slot)](https://aidenmitchell.github.io/pylint-errors/plerr/E0237) **[+]**
- [E0238 (invalid-slots)](https://aidenmitchell.github.io/pylint-errors/plerr/E0238) **[+]**
- [E0239 (inherit-non-class)](https://aidenmitchell.github.io/pylint-errors/plerr/E0239) **[+]**
- [E0240 (inconsistent-mro)](https://aidenmitchell.github.io/pylint-errors/plerr/E0240) **[+]**
- [E0241 (duplicate-bases)](https://aidenmitchell.github.io/pylint-errors/plerr/E0241) **[+]**
- [E0242 (class-variable-slots-conflict)](https://aidenmitchell.github.io/pylint-errors/plerr/E0242) **[+]**
- [E0301 (non-iterator-returned)](https://aidenmitchell.github.io/pylint-errors/plerr/E0301) **[+]**
- [E0302 (unexpected-special-method-signature)](https://aidenmitchell.github.io/pylint-errors/plerr/E0302) **[+]**
- [E0303 (invalid-length-returned)](https://aidenmitchell.github.io/pylint-errors/plerr/E0303) **[+]**
- [F0202 (method-check-failed)](https://aidenmitchell.github.io/pylint-errors/plerr/F0202)
- [R0201 (no-self-use)](https://aidenmitchell.github.io/pylint-errors/plerr/R0201)  **[+]**
- [R0202 (no-classmethod-decorator)](https://aidenmitchell.github.io/pylint-errors/plerr/R0202) **[+]**
- [R0203 (no-staticmethod-decorator)](https://aidenmitchell.github.io/pylint-errors/plerr/R0203) **[+]**
- [R0205 (useless-object-inheritance)](https://aidenmitchell.github.io/pylint-errors/plerr/R0205) **[+]**
- [R0206 (property-with-parameters)](https://aidenmitchell.github.io/pylint-errors/plerr/R0206) **[+]**
- [W0201 (attribute-defined-outside-init)](https://aidenmitchell.github.io/pylint-errors/plerr/W0201) **[+]**
- [W0211 (bad-staticmethod-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/W0211) **[+]**
- [W0212 (protected-access)](https://aidenmitchell.github.io/pylint-errors/plerr/W0212) **[+]**
- [W0221 (arguments-differ)](https://aidenmitchell.github.io/pylint-errors/plerr/W0221) **[+]**
- [W0222 (signature-differs)](https://aidenmitchell.github.io/pylint-errors/plerr/W0222)
- [W0223 (abstract-method)](https://aidenmitchell.github.io/pylint-errors/plerr/W0223) **[+]**
- [W0231 (super-init-not-called)](https://aidenmitchell.github.io/pylint-errors/plerr/W0231) **[+]**
- [W0232 (no-init)](https://aidenmitchell.github.io/pylint-errors/plerr/W0232) **[+]**
- [W0233 (non-parent-init-called)](https://aidenmitchell.github.io/pylint-errors/plerr/W0233) **[+]**
- [W0235 (useless-super-delegation)](https://aidenmitchell.github.io/pylint-errors/plerr/W0235) **[+]**
- [W0236 (invalid-overridden-method)](https://aidenmitchell.github.io/pylint-errors/plerr/W0236) **[+]**

### Compare-To-Empty-String Checker Messages

- [C1901 (compare-to-empty-string)](https://aidenmitchell.github.io/pylint-errors/plerr/C1901) **[+]**

### Compare-To-Zero Checker Messages

- [C2001 (compare-to-zero)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/compare-to-zero/C2001) **[+]**

### Deprecated Builtins Checker Messages

- [W0141 (bad-builtin)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/deprecated-builtins/W0141) **[+]**

### Design Checker Messages

- [R0901 (too-many-ancestors)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0901) **[+]**
- [R0902 (too-many-instance-attributes)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0902) **[+]**
- [R0903 (too-few-public-methods)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0903) **[+]**
- [R0904 (too-many-public-methods)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0904) **[+]**
- [R0911 (too-many-return-statements)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0911) **[+]**
- [R0912 (too-many-branches)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0912) **[+]**
- [R0913 (too-many-arguments)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0913) **[+]**
- [R0914 (too-many-locals)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0914) **[+]**
- [R0915 (too-many-statements)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0915) **[+]**
- [R0916 (too-many-boolean-expressions)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R0916) **[+]**
- [R1260 (too-complex)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/design/R1260) **[+]**

### Docstyle Checker Messages

- [C0198 (bad-docstring-quotes)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/docstyle/C0198) **[+]**
- [C0199 (docstring-first-line-empty)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/docstyle/C0199) **[+]**

### Else If Used Checker Messages

- [R5501 (else-if-used)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/else-if-used/R5501) **[+]**

### Exceptions Checker Messages

- [E0701 (bad-except-order)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0701) **[+]**
- [E0702 (raising-bad-type)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0702) **[+]**
- [E0703 (bad-exception-context)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0703) **[+]**
- [E0704 (misplaced-bare-raise)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0704) **[+]**
- [E0710 (raising-non-exception)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0710) **[+]**
- [E0711 (notimplemented-raised)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0711) **[+]**
- [E0712 (catching-non-exception)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/E0712) **[+]**
- [W0702 (bare-except)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0702) **[+]**
- [W0703 (broad-except)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0703) **[+]**
- [W0705 (duplicate-except)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0705) **[+]**
- [W0706 (try-except-raise)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0706) **[+]**
- [W0711 (binary-op-exception)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0711) **[+]**
- [W0715 (raising-format-tuple)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0715)
- [W0716 (wrong-exception-operation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/exceptions/W0716) **[+]**

### Format Checker Messages

- [C0301 (line-too-long)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0301) **[+]**
- [C0302 (too-many-lines)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0302)
- [C0303 (trailing-whitespace)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0303) **[+]**
- [C0304 (missing-final-newline)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0304)
- [C0305 (trailing-newlines)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0305)
- [C0321 (multiple-statements)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0321) **[+]**
- [C0325 (superfluous-parens)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0325) **[+]**
- [C0326 (bad-whitespace)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0326) **[+]**
- [C0327 (mixed-line-endings)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0327)
- [C0328 (unexpected-line-ending-format)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0328)
- [C0330 (bad-continuation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/C0330)
- [W0301 (unnecessary-semicolon)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/W0301) **[+]**
- [W0311 (bad-indentation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/W0311) **[+]**
- [W0312 (mixed-indentation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/format/W0312)

### Imports Checker Messages

- [C0410 (multiple-imports)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/C0410) **[+]**
- [C0411 (wrong-import-order)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/C0411) **[+]**
- [C0412 (ungrouped-imports)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/C0412) **[+]**
- [C0413 (wrong-import-position)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/C0413) **[+]**
- [C0414 (useless-import-alias)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/C0414) **[+]**
- [C0415 (import-outside-toplevel)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/C0415) **[+]**
- [E0401 (import-error)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/E0401) **[+]**
- [E0402 (relative-beyond-top-level)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/E0402) **[+]**
- [R0401 (cyclic-import)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/R0401) **[+]**
- [W0401 (wildcard-import)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/W0401) **[+]**
- [W0402 (deprecated-module)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/W0402) **[+]**
- [W0404 (reimported)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/W0404) **[+]**
- [W0406 (import-self)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/W0406) **[+]**
- [W0407 (preferred-module)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/W0407) **[+]**
- [W0410 (misplaced-future)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/imports/W0410) **[+]**

### Logging Checker Messages

- [E1200 (logging-unsupported-format)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/logging/E1200)
- [E1201 (logging-format-truncated)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/logging/E1201)
- [E1205 (logging-too-many-args)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/logging/E1205)
- [E1206 (logging-too-few-args)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/logging/E1206)
- [W1201 (logging-not-lazy)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/logging/W1201) **[+]**
- [W1202 (logging-format-interpolation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/logging/W1202) **[+]**

### Miscellaneous Checker Messages

- [I0023 (use-symbolic-message-instead)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/miscellaneous/I0023)
- [W0511 (fixme)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/miscellaneous/W0511) **[+]**

### Multiple Types Checker Messages

- [R0204 (redefined-variable-type)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/multiple-types/R0204)

### Newstyle Checker Messages

- [E1003 (bad-super-call)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/newstyle/E1003) **[+]**

### Overlap-Except Checker Messages

- [W0714 (overlapping-except)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/overlap-except/W0714)

### Parameter Documentation Checker Messages

- [W9005 (multiple-constructor-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9005) **[+]**
- [W9006 (missing-raises-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9006) **[+]**
- [W9008 (redundant-returns-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9008)
- [W9010 (redundant-yields-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9010)
- [W9011 (missing-return-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9011) **[+]**
- [W9012 (missing-return-type-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9012) **[+]**
- [W9013 (missing-yield-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9013)
- [W9014 (missing-yield-type-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9014)
- [W9015 (missing-param-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9015) **[+]**
- [W9016 (missing-type-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9016) **[+]**
- [W9017 (differing-param-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9017) **[+]**
- [W9018 (differing-type-doc)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/parameter-documentation/W9018) **[+]**

### Refactoring Checker Messages

- [C0113 (unneeded-not)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/C0113) **[+]**
- [C0200 (consider-using-enumerate)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/C0200) **[+]**
- [C0201 (consider-iterating-dictionary)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/C0201) **[+]**
- [C1801 (len-as-condition)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/C1801) **[+]**
- [R1701 (consider-merging-isinstance)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1701)
- [R1702 (too-many-nested-blocks)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1702)
- [R1703 (simplifiable-if-statement)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1703)
- [R1704 (redefined-argument-from-local)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1704)
- [R1705 (no-else-return)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1705) **[+]**
- [R1706 (consider-using-ternary)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1706)
- [R1707 (trailing-comma-tuple)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1707) **[+]**
- [R1708 (stop-iteration-return)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1708) **[+]**
- [R1709 (simplify-boolean-expression)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1709)
- [R1710 (inconsistent-return-statements)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1710) **[+]**
- [R1711 (useless-return)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1711) **[+]**
- [R1712 (consider-swap-variables)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1712) **[+]**
- [R1713 (consider-using-join)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1713) **[+]**
- [R1714 (consider-using-in)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1714) **[+]**
- [R1715 (consider-using-get)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1715)
- [R1716 (chained-comparison)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1716) **[+]**
- [R1717 (consider-using-dict-comprehension)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1717)
- [R1718 (consider-using-set-comprehension)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1718)
- [R1719 (simplifiable-if-expression)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1719) **[+]**
- [R1720 (no-else-raise)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1720) **[+]**
- [R1721 (unnecessary-comprehension)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1721)
- [R1722 (consider-using-sys-exit)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1722) **[+]**
- [R1723 (no-else-break)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1723) **[+]**
- [R1724 (no-else-continue)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/refactoring/R1724) **[+]**

### Similarities Checker Messages

- [R0801 (duplicate-code)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/similarities/R0801)

### Spelling Checker Messages

- [C0401 (wrong-spelling-in-comment)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/spelling/C0401)
- [C0402 (wrong-spelling-in-docstring)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/spelling/C0402)
- [C0403 (invalid-characters-in-docstring)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/spelling/C0403)

### Stdlib Checker Messages

- [E1507 (invalid-envvar-value)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/E1507) **[+]**
- [W1501 (bad-open-mode)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1501) **[+]**
- [W1502 (boolean-datetime)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1502)
- [W1503 (redundant-unittest-assert)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1503) **[+]**
- [W1505 (deprecated-method)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1505)
- [W1506 (bad-thread-instantiation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1506) **[+]**
- [W1507 (shallow-copy-environ)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1507) **[+]**
- [W1508 (invalid-envvar-default)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1508) **[+]**
- [W1509 (subprocess-popen-preexec-fn)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1509) **[+]**
- [W1510 (subprocess-run-check)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/stdlib/W1510) **[+]**

### String Checker Messages

- [E1300 (bad-format-character)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1300) **[+]**
- [E1301 (truncated-format-string)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1301)
- [E1302 (mixed-format-string)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1302) **[+]**
- [E1303 (format-needs-mapping)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1303)
- [E1304 (missing-format-string-key)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1304) **[+]**
- [E1305 (too-many-format-args)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1305) **[+]**
- [E1306 (too-few-format-args)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1306) **[+]**
- [E1307 (bad-string-format-type)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1307) **[+]**
- [E1310 (bad-str-strip-call)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/E1310)
- [W1300 (bad-format-string-key)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1300)
- [W1301 (unused-format-string-key)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1301)
- [W1302 (bad-format-string)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1302) **[+]**
- [W1303 (missing-format-argument-key)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1303) **[+]**
- [W1304 (unused-format-string-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1304) **[+]**
- [W1305 (format-combined-specification)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1305) **[+]**
- [W1306 (missing-format-attribute)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1306) **[+]**
- [W1307 (invalid-format-index)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1307) **[+]**
- [W1308 (duplicate-string-formatting-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1308)
- [W1401 (anomalous-backslash-in-string)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1401)
- [W1402 (anomalous-unicode-escape-in-string)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1402) **[+]**
- [W1403 (implicit-str-concat-in-sequence)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/string/W1403)

### Typecheck Checker Messages

- [E1101 (no-member)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1101) **[+]**
- [E1102 (not-callable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1102) **[+]**
- [E1111 (assignment-from-no-return)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1111) **[+]**
- [E1120 (no-value-for-parameter)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1120) **[+]**
- [E1121 (too-many-function-args)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1121) **[+]**
- [E1123 (unexpected-keyword-arg)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1123) **[+]**
- [E1124 (redundant-keyword-arg)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1124) **[+]**
- [E1125 (missing-kwoa)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1125)
- [E1126 (invalid-sequence-index)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1126) **[+]**
- [E1127 (invalid-slice-index)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1127) **[+]**
- [E1128 (assignment-from-none)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1128) **[+]**
- [E1129 (not-context-manager)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1129) **[+]**
- [E1130 (invalid-unary-operand-type)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1130) **[+]**
- [E1131 (unsupported-binary-operation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1131) **[+]**
- [E1132 (repeated-keyword)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1132)
- [E1133 (not-an-iterable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1133) **[+]**
- [E1134 (not-a-mapping)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1134)
- [E1135 (unsupported-membership-test)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1135) **[+]**
- [E1136 (unsubscriptable-object)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1136) **[+]**
- [E1137 (unsupported-assignment-operation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1137) **[+]**
- [E1138 (unsupported-delete-operation)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1138) **[+]**
- [E1139 (invalid-metaclass)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1139)
- [E1140 (unhashable-dict-key)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1140) **[+]**
- [E1141 (dict-iter-missing-items)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/E1141) **[+]**
- [I1101 (c-extension-no-member)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/I1101)
- [W1113 (keyword-arg-before-vararg)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/W1113) **[+]**
- [W1114 (arguments-out-of-order)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/typecheck/W1114)

### Variables Checker Messages

- [E0601 (used-before-assignment)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/E0601) **[+]**
- [E0602 (undefined-variable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/E0602)
- [E0603 (undefined-all-variable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/E0603) **[+]**
- [E0604 (invalid-all-object)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/E0604) **[+]**
- [E0611 (no-name-in-module)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/E0611) **[+]**
- [E0633 (unpacking-non-sequence)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/E0633) **[+]**
- [W0601 (global-variable-undefined)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0601) **[+]**
- [W0602 (global-variable-not-assigned)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0602) **[+]**
- [W0603 (global-statement)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0603) **[+]**
- [W0604 (global-at-module-level)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0604) **[+]**
- [W0611 (unused-import)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0611) **[+]**
- [W0612 (unused-variable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0612) **[+]**
- [W0613 (unused-argument)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0613) **[+]**
- [W0614 (unused-wildcard-import)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0614) **[+]**
- [W0621 (redefined-outer-name)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0621) **[+]**
- [W0622 (redefined-builtin)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0622) **[+]**
- [W0623 (redefine-in-handler)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0623)
- [W0631 (undefined-loop-variable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0631) **[+]**
- [W0632 (unbalanced-tuple-unpacking)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0632) **[+]**
- [W0640 (cell-var-from-loop)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0640) **[+]**
- [W0641 (possibly-unused-variable)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0641)
- [W0642 (self-cls-assignment)](https://aidenmitchell.github.io/pylint-errors/plerr/errors/variables/W0642)
