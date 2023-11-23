# fl-common-lint

This package contains a strict and opinionated set of lints common for vanyasem's projects.

Focused on having as many non-conflicting rules enabled as possible.

## Usage

1. Depend on this package as a **dev_dependency**
   
   `pubspec.yaml`:

   ```yaml
   dev_dependencies:
     fl_common_lint: 1.2.0
   ```

   or

   ```yaml
   dev_dependencies:
     fl_common_lint:
       git:
         url: git@github.com:productlabteam/fl-common-lint.git
         ref: 1.2.0
   ```

2. Create an `analysis_options.yaml` file at the root of the package (alongside
the `pubspec.yaml` file)

   `analysis_options.yaml`:

   ```yaml
   include: package:fl_common_lint/analysis_options.yaml
   ```
