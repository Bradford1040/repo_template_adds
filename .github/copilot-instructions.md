# GitHub Copilot Instructions for repo_template_adds

This repository contains template files and configurations that are commonly added to other repositories. Here's what you need to know to work effectively with this codebase:

## Project Purpose
This repository serves as a collection of template files that Bradford A. Adams (Bradford1040) adds to most repositories. These include license files, editor configurations, and git-related settings.

## Critical Files and Their Purposes

### License and Legal Files
- `LICENSE.md`: Custom license with specific terms prohibiting Google entities from using or accessing the repository
- `Developer Certificate of Origin.md`: Standard DCO v1.1 for contributor certification
- Various Creative Commons licenses (v4.0) with different permissions:
  - BY: Attribution only
  - BY-SA: Attribution + Share-Alike
  - BY-ND: Attribution + No-Derivatives
  - BY-NC: Attribution + Non-Commercial
  - BY-NC-SA: Attribution + Non-Commercial + Share-Alike
  - BY-NC-ND: Attribution + Non-Commercial + No-Derivatives
  - Public Domain Zero v1.0

### Configuration Files
- `.editorconfig`: Defines consistent coding styles
  - Uses tabs with size 2 for general files
  - Uses 4 spaces for Python
  - Specific rules for different file types (js, json, xml, etc.)
  - Line ending controls (LF/CRLF) based on file type

- `.gitattributes`: Git file handling configuration
  - Line ending normalization (LF by default)
  - Binary/text file handling
  - Diff settings for various file types

- `.gitignore`: Common ignore patterns
  - Environment and secret files
  - Package manager directories
  - OS-specific files
  - IDE files
  - Build artifacts
  - Temporary files

- `.shellcheckrc`: Shell script checking configuration
  - Enables checking of sourced files

## Important Conventions

### File Encodings and Line Endings
1. Use UTF-8 encoding for all text files
2. Follow the .gitattributes rules for line endings:
  - Use LF for most files
  - Use CRLF for .cmd, .bat, .ps1 files
  - Use CRLF for XML files

### Indentation Standards
1. Default: Use tabs with size 2
2. Python: Use 4 spaces
3. Package files (package.json, .travis.yml): Use 2 spaces
4. Shell scripts (.sh, .yml, .yaml, .json): Use 2 spaces
5. XML files: Use 4 spaces

## Security and Legal Requirements

### License Compliance
- All contributions must comply with the custom LICENSE.md terms
- No Google entities may access, use, or store repository contents
- Vulnerability disclosures must be made directly to Bradford1040
- Changes must be certified under the Developer Certificate of Origin

### File Handling
- Maintain strict binary/text file separation as defined in .gitattributes
- Preserve file permissions and line endings as specified
- Do not commit files matching patterns in .gitignore

## Best Practices

1. **File Creation:**
  - Use appropriate line endings based on file type
  - Set correct file permissions
  - Include proper file headers/copyright notices

2. **Code Style:**
  - Follow .editorconfig settings
  - Maintain consistent indentation per file type
  - Preserve empty final lines where specified

3. **Git Operations:**
  - Use proper commit message format
  - Respect binary file handling in .gitattributes
  - Follow the Developer Certificate of Origin process

These instructions will help ensure consistent and compliant contributions to the repository while maintaining its integrity and purpose as a template source.
