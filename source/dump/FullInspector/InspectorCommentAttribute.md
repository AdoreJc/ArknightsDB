# InspectorCommentAttribute

**Namespace:** `FullInspector`


## Fields

- `String Comment`

- `CommentType Type`

- `Double Order`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class InspectorCommentAttribute : Attribute, IInspectorAttributeOrder
{
	public String Comment; // 0x10
	public CommentType Type; // 0x18
	public Double Order; // 0x20

	private Double FullInspector.IInspectorAttributeOrder.Order { get; }

	// RVA: 0x34d44bc VA: 0x7595aec4bc
	public Void .ctor(String comment) { }
	// RVA: 0x34d4548 VA: 0x7595aec548
	public Void .ctor(CommentType type, String comment) { }
	// RVA: 0x34d4588 VA: 0x7595aec588
	private Double FullInspector.IInspectorAttributeOrder.get_Order() { }
}
```