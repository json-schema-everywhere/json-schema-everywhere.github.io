---
title: Schema Validation for YAML
short_name: YAML
long_name: YAML Ain't Markup Language
project_url: http://yaml.org/
logo: yaml.svg
description_blurb: is a powerful data serialization language that aims to be human friendly.  Most JSON is syntactically valid YAML, but idiomatic YAML follows very different conventions.  While YAML has advanced features that cannot directly mapped to JSON, most YAML files use features that can be validated by JSON Schema making JSON Schema the best choice for validation.
editors:
validators:
alternatives:
  - name: Kwalify
    project_url: http://www.kuwata-lab.com/kwalify/
    notes:
      - Portability concerns with only Ruby and Python implementations
      - Only Python has recent development activity
      - No tooling support
  - name: Rx
    project_url: http://rx.codesimply.com/
    notes:
      - Supports JavaScript, Perl, PHP, Ruby, Python
      - Low development activity
      - No tooling support
  - name: yaml-validator
    project_url: https://github.com/paazmaya/yaml-validator
    notes:
      - JavaScript only
      - Only structural validation
  - name: simple-yaml-validator
    project_url: https://github.com/saibotsivad/simple-yaml-validator
    notes:
      - JavaScript only
      - Only structural validation
      - Little adoption. npm shows low download count.
---