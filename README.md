# Rich Edit for Blazor - How to check whether the document is empty

This example demonstrates how you can check whether a document opened in the [Rich Text Editor](https://docs.devexpress.com/Blazor/401891/rich-text-editor) is empty.

![Blazor DxRichEdit check whether the document is empty](/images/document-is-empty.png)

An empty document meets the following conditions:

* It has one [section](https://docs.devexpress.com/Blazor/DevExpress.Blazor.RichEdit.Section).
* This section's length is equal to 0.
* This section does not have a [header or footer](https://docs.devexpress.com/Blazor/DevExpress.Blazor.RichEdit.Section#section-headers-and-footers).

## Files to Look At

- [Index.razor](./CS/CheckIfDocumentEmpty/Pages/Index.razor)

## Documentation

- [Rich Text Editor Examples](https://docs.devexpress.com/Blazor/403343/rich-edit/examples)

## More Examples

- [Rich Edit for Blazor - How to export a document to the HTML](https://github.com/DevExpress-Examples/blazor-dxrichedit-export-to-html)
