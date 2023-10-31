## 0.4.4

- Add:
  - Core: (Added together with Dart `3.1.0`)
    - `no_self_assignments`
    - `no_wildcard_variable_uses`

## 0.4.3

- Update licence bearer and links.

## 0.4.2

- Remove:
  - Core:
    - `avoid_equals_and_hash_code_on_mutable_classes`: Requires the `meta`
      package, which not everybody wants to use.

## 0.4.1

- Remove:
  - Analysis:
    - `strict-raw-types`: Generics end up looking extremely ugly when `dynamic`
      is required, where simply omitting the type would work just fine.

## 0.4.0

- Add:
  - Core: (Added together with Dart `3.0.0` in linter version `1.35.0`)
    - `implicit_reopen`
    - `unnecessary_breaks`
    - `type_literal_in_constant_pattern`
    - `invalid_case_patterns`
  - Core: (Missing)
    - `unawaited_futures`
- Remove:
  - Core: (Removed in linter version `1.35.0`)
    - `enable_null_safety`
    - `invariant_booleans`
  - Core: (Annoying)
    - `avoid_catching_errors` (There are valid reasons to catch `TypeError`, for
      example)
    - `directives_ordering` (Some people may arrange their imports differently)

## 0.3.2

- Relicense package as `MIT` from `AGPL-3.0`.

## 0.3.1

- Fix wrong option being defined in `core.yaml` (`strong-mode` instead of
  `language`).

## 0.3.0

- Added: (Added together with Dart `2.19.0` in linter version `1.31.0`)
  - Core:
    - `collection_methods_unrelated_type`
    - `combinators_ordering`
    - `dangling_library_doc_comments`
    - `enable_null_safety`
    - `implicit_call_tearoffs`
    - `library_annotations`
    - `unnecessary_library_directive`
    - `unreachable_from_main`
    - `use_string_in_part_of_directives`

## 0.2.0

- Added: (Added together with Dart `2.18.0` in linter version `1.25.0`)
  - Core:
    - `discarded_futures`
    - `unnecessary_null_aware_operator_on_extension_on_nullable`
    - `unnecessary_to_list_in_spreads`

## 0.1.1

- Added: (Added together with Dart `2.17.0` in linter version `1.22.0`)
  - Core:
    - `use_enums`
    - `use_super_parameters`
  - Flutter:
    - `use_colored_box`

## 0.1.0+1

- Removed: (These were added in linter version `1.22.0`, which isn't yet
  featured in the stable Dart SDK channel)
  - `use_enums`
  - `use_super_parameters`

## 0.1.0

- Added: (Added together with Dart `2.16.0` in linter version `1.18.0`)
  - Core:
    - `avoid_final_parameters`
    - `conditional_uri_does_not_exist`
    - `no_leading_underscores_for_library_prefixes`
    - `no_leading_underscores_for_local_identifiers`
    - `require_trailing_commas`
    - `unnecessary_late`
    - `secure_pubspec_urls`
  - Flutter:
    - `sized_box_shrink_expand`
    - `use_decorated_box`

## 0.0.2+2

- Added:
  - `use_enums`
  - `use_super_parameters`

## 0.0.2+1

- Edited package description.

## 0.0.2

- Added:
  - `eol_at_end_of_file`
  - `library_private_types_in_public_api`
  - `noop_primitive_operations`
  - `prefer_null_aware_method_calls`
  - `use_test_throws_matchers`
  - `depend_on_referenced_packages`
- Removed:
  - `constant_identifier_names` ~ Enumerator values should be in PascalCase, and
    not in camelCase. Thus, the `constant_identifier_names` rule was tedious to
    work with and disable.

## 0.0.1+2

- Enabled stricter type checks through `analyzer` options.

## 0.0.1+1

- Added EXAMPLE.md.

## 0.0.1

- Initial release.
