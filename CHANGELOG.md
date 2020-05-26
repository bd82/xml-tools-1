# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [5.0.0](https://github.com/bd82/xml-tools-1/compare/v0.3.0...v5.0.0) (2020-05-26)

### Bug Fixes

- add npmignore file to each package ([5bbf209](https://github.com/bd82/xml-tools-1/commit/5bbf209))
- api type definitions ([46d6c2c](https://github.com/bd82/xml-tools-1/commit/46d6c2c))
- **simple-schema:** duplicate element error ([f434af8](https://github.com/bd82/xml-tools-1/commit/f434af8))
- content Assist - ElementContents bug fixes ([1eba20a](https://github.com/bd82/xml-tools-1/commit/1eba20a)), closes [#15](https://github.com/bd82/xml-tools-1/issues/15) [#16](https://github.com/bd82/xml-tools-1/issues/16)
- cST Visitor method's Params Type fix ([a0a0e2d](https://github.com/bd82/xml-tools-1/commit/a0a0e2d))
- fix README.md ([472301d](https://github.com/bd82/xml-tools-1/commit/472301d))
- missing import ([2a51ab9](https://github.com/bd82/xml-tools-1/commit/2a51ab9))
- more CST Visitor API fixes ([89d1cef](https://github.com/bd82/xml-tools-1/commit/89d1cef))
- new property added to ast interface ([#35](https://github.com/bd82/xml-tools-1/issues/35)) ([d7fd672](https://github.com/bd82/xml-tools-1/commit/d7fd672))
- remove extraneous prefix completion items ([#98](https://github.com/bd82/xml-tools-1/issues/98)) ([9b52e70](https://github.com/bd82/xml-tools-1/commit/9b52e70))
- simple schema with xml namespaces ([#52](https://github.com/bd82/xml-tools-1/issues/52)) ([bb0163e](https://github.com/bd82/xml-tools-1/commit/bb0163e))
- **parser:** parsing for multi-line comments ([#46](https://github.com/bd82/xml-tools-1/issues/46)) ([4970e9a](https://github.com/bd82/xml-tools-1/commit/4970e9a))
- update yarn.lock ([#180](https://github.com/bd82/xml-tools-1/issues/180)) ([0b08831](https://github.com/bd82/xml-tools-1/commit/0b08831))
- **content-assist:** avoid breaking changes with new `context` arg ([c7bbdc2](https://github.com/bd82/xml-tools-1/commit/c7bbdc2))
- **content-assist:** crash with invalid xml ([#57](https://github.com/bd82/xml-tools-1/issues/57)) ([774c623](https://github.com/bd82/xml-tools-1/commit/774c623))
- **parser:** allow CData nodes to be multi-line ([#89](https://github.com/bd82/xml-tools-1/issues/89)) ([2b2fbfb](https://github.com/bd82/xml-tools-1/commit/2b2fbfb))
- **parser:** fix Lexing of XML processing instructions ([2c503b4](https://github.com/bd82/xml-tools-1/commit/2c503b4))
- **parser:** names may start with an underscore '\_' ([#103](https://github.com/bd82/xml-tools-1/issues/103)) ([63dfd8f](https://github.com/bd82/xml-tools-1/commit/63dfd8f))
- **simple-schema:** fix Simple-Schema API for enumValue ([0e4fdd8](https://github.com/bd82/xml-tools-1/commit/0e4fdd8))
- **xml-for-vscode:** incorrect vscode engine version ([88adfa3](https://github.com/bd82/xml-tools-1/commit/88adfa3))

### chore

- **xml-toolkit:** first major version ([9e1f5a9](https://github.com/bd82/xml-tools-1/commit/9e1f5a9))
- **xml-toolkit:** some other dummy change ([8e6cfc4](https://github.com/bd82/xml-tools-1/commit/8e6cfc4))

### Features

- better Handling of Open/Close Body ranges ([0751a7e](https://github.com/bd82/xml-tools-1/commit/0751a7e))
- lsp-server package ([#107](https://github.com/bd82/xml-tools-1/issues/107)) ([2b6b896](https://github.com/bd82/xml-tools-1/commit/2b6b896))
- **content-assist:** support optional `context` arg in `getSuggestions` ([6e5a228](https://github.com/bd82/xml-tools-1/commit/6e5a228))
- open tag body range added ([#34](https://github.com/bd82/xml-tools-1/issues/34)) ([5414111](https://github.com/bd82/xml-tools-1/commit/5414111))
- **ast:** added `.syntax.isSelfClosing` property on an XMLElement node ([#164](https://github.com/bd82/xml-tools-1/issues/164)) ([bfc448b](https://github.com/bd82/xml-tools-1/commit/bfc448b))
- **ast:** attributesRange and guessedAttributeRange support ([8ce840d](https://github.com/bd82/xml-tools-1/commit/8ce840d)), closes [#51](https://github.com/bd82/xml-tools-1/issues/51)
- **ast:** element Namespaces are now represented as Records in a Map ([f9f6fdc](https://github.com/bd82/xml-tools-1/commit/f9f6fdc))
- **ast-position:** add AST position visitor ([#175](https://github.com/bd82/xml-tools-1/issues/175)) ([9eb1253](https://github.com/bd82/xml-tools-1/commit/9eb1253))
- **ast-position:** rename `getAstNodeInPosition` -> astPositionAtOffset ([585253f](https://github.com/bd82/xml-tools-1/commit/585253f))
- **common:** add utility functions for xmlns attributes ([#173](https://github.com/bd82/xml-tools-1/issues/173)) ([20d6c09](https://github.com/bd82/xml-tools-1/commit/20d6c09))
- **content assist:** improved attributes keys content assist ([3d3b7c2](https://github.com/bd82/xml-tools-1/commit/3d3b7c2)), closes [#42](https://github.com/bd82/xml-tools-1/issues/42)
- **content-assist:** decouple content assist from parsing ([#58](https://github.com/bd82/xml-tools-1/issues/58)) ([3688da8](https://github.com/bd82/xml-tools-1/commit/3688da8))
- **language-server:** dummy change 1 ([32a1a38](https://github.com/bd82/xml-tools-1/commit/32a1a38))
- **parser:** expose The Token Vector on the parse result ([31d50f3](https://github.com/bd82/xml-tools-1/commit/31d50f3))
- **parser:** support Basic DocType Declarations ([5b4db21](https://github.com/bd82/xml-tools-1/commit/5b4db21))

### BREAKING CHANGES

- **xml-toolkit:** blah
- **xml-toolkit:** First Major Version
- **ast-position:** rename `getAstNodeInPosition` -> astPositionAtOffset
- **ast:** The `namespaces` property of an XMLElement is now a Map/Dictionary not an Array.
- **parser:** Implementing XmlCstVisitor now requires implementing two additional methods:
  (docTypeDecl and externalID)
- **content-assist:** getSuggestions now uses ast, cst and tokenVector instead of text
- **ast:** buildAst now requires a tokenVector argument
