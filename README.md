<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/523621286/21.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1108629)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Blazor Rich Text Editor - How to determine whether a document is empty

This example demonstrates how you can check whether a document displayed in our Blazor [Rich Text Editor](https://docs.devexpress.com/Blazor/401891/rich-text-editor) is empty.

![Blazor DxRichEdit check whether the document is empty](/images/document-is-empty.png)

An empty document must meet the following conditions:

* It has one [section](https://docs.devexpress.com/Blazor/DevExpress.Blazor.RichEdit.Section).
* Section length is equal to 0.
* This section does not have a [header or footer](https://docs.devexpress.com/Blazor/DevExpress.Blazor.RichEdit.Section#section-headers-and-footers).

## Files to Look At

- [Index.razor](./CS/CheckIfDocumentEmpty/Pages/Index.razor)

## Documentation

- [Rich Text Editor Examples](https://docs.devexpress.com/Blazor/403343/rich-edit/examples)

## More Examples

- [Blazor Rich Text Editor - How to export a document to a file (HTML format)](https://github.com/DevExpress-Examples/blazor-dxrichedit-export-to-html)
