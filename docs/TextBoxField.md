# TextBoxField
Provides TextBoxField.

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | [**[]Link**](Link.md) | Link to the document. | [optional] [default to null]
**PartialName** | **string** | Field name. | [optional] [default to null]
**FullName** | **string** | Full Field name. | [optional] [default to null]
**Rect** | [***Rectangle**](Rectangle.md) | Field rectangle. | [optional] [default to null]
**Value** | **string** | Field value. | [optional] [default to null]
**PageIndex** | **int32** | Page index. | [default to null]
**Height** | **float64** | Gets or sets height of the field. | [optional] [default to null]
**Width** | **float64** | Gets or sets width of the field. | [optional] [default to null]
**ZIndex** | **int32** | Z index. | [optional] [default to null]
**IsGroup** | **bool** | Is group. | [optional] [default to null]
**Parent** | [***FormField**](FormField.md) | Gets field parent. | [optional] [default to null]
**IsSharedField** | **bool** | Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it&#39;s appearance will be visible on all pages of the document. If false, separated field will be created for every document page. | [optional] [default to null]
**Flags** | [**[]AnnotationFlags**](AnnotationFlags.md) | Gets Flags of the field. | [optional] [default to null]
**Color** | [***Color**](Color.md) | Color of the annotation. | [optional] [default to null]
**Contents** | **string** | Get the field content. | [optional] [default to null]
**Margin** | [***MarginInfo**](MarginInfo.md) | Gets or sets a outer margin for paragraph (for pdf generation) | [optional] [default to null]
**Highlighting** | [***LinkHighlightingMode**](LinkHighlightingMode.md) | Field highlighting mode. | [optional] [default to null]
**HorizontalAlignment** | [***HorizontalAlignment**](HorizontalAlignment.md) | Gets HorizontalAlignment of the field. | [optional] [default to null]
**VerticalAlignment** | [***VerticalAlignment**](VerticalAlignment.md) | Gets VerticalAlignment of the field. | [optional] [default to null]
**Border** | [***Border**](Border.md) | Gets or sets annotation border characteristics. | [optional] [default to null]
**Multiline** | **bool** | Gets or sets multiline flag of the field. If Multiline is true field can contain multiple lines of text. | [optional] [default to null]
**SpellCheck** | **bool** | Gets or sets spellcheck flag for field. If true field shall be spell checked. | [optional] [default to null]
**Scrollable** | **bool** | Gets or sets scrollable flag of field. If true field can be scrolled. | [optional] [default to null]
**ForceCombs** | **bool** | Gets or sets flag which indicates is field divided into spaced positions. | [optional] [default to null]
**MaxLen** | **int32** | Gets or sets maximum length of text in the field. | [optional] [default to null]
**Barcode** | **string** | Adds barcode 128 into the field. Field value will be changed onto the code and field become read only. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)[[View Source]](../text_box_field.go)


