# SplitResultDocument
Represents split result document,

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | **string** | The &quot;href&quot; attribute contains the link&#39;s IRI. atom:link elements MUST have an href attribute, whose value MUST be a IRI reference | [optional] [default to null]
**Rel** | **string** | atom:link elements MAY have a &quot;rel&quot; attribute that indicates the link relation type.  If the &quot;rel&quot; attribute is not present, the link element MUST be interpreted as if the link relation type is &quot;alternate&quot;. | [optional] [default to null]
**Type_** | **string** | On the link element, the &quot;type&quot; attribute&#39;s value is an advisory media type: it is a hint about the type of the representation that is expected to be returned when the value of the href attribute is dereferenced.  Note that the type attribute does not override the actual media type returned with the representation. | [optional] [default to null]
**Title** | **string** | The &quot;title&quot; attribute conveys human-readable information about the link.  The content of the &quot;title&quot; attribute is Language-Sensitive. | [optional] [default to null]
**Id** | **int32** | Gets or sets the page number. | [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)[[View Source]](../split_result_document.go)


