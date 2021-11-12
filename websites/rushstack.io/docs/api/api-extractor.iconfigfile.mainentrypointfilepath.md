---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor](./api-extractor.md) &gt; [IConfigFile](./api-extractor.iconfigfile.md) &gt; [mainEntryPointFilePath](./api-extractor.iconfigfile.mainentrypointfilepath.md)

## IConfigFile.mainEntryPointFilePath property

Specifies the .d.ts file to be used as the starting point for analysis. API Extractor analyzes the symbols exported by this module.

<b>Signature:</b>

```typescript
mainEntryPointFilePath: string;
```

## Remarks

The file extension must be ".d.ts" and not ".ts". The path is resolved relative to the "projectFolder" location.
