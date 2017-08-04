---
title: Schema Validation for TOML
short_name: TOML
long_name: Tom's Obvious, Minimal Language
highlighting_language: toml
example_json_file: example.toml.json
project_url: https://github.com/toml-lang/toml
description_blurb: is a minimal language with growing popularity that is largely compatible with JSON, though more restrictive.  There is a proposal for a TOML-specific schema language, which may be a viable option in the future.  However, until such a proposal gains traction and is implemented, JSON Schema remains the most available option for validating TOML files.
validators:
  - name: Polyglottal JSON Schema Validator
    project_url: https://www.npmjs.com/package/pajv
    language: JavaScript
    license: MIT
    description: Polyglottal JSON Schema Validator (pajv) is a command line utility that can be used to validate data in numerous formats against a JSON Schema.
alternatives:
  - name: Tom's Obvious Liuggio Scheme (TOLS)
    project_url: https://github.com/toml-lang/toml/pull/116
    notes:
      - Proposed specification without recent activity
      - No implementations are known to exist
---