# CommentAttribute

**Namespace:** `FullInspector`


## Fields

- `String Comment`

- `CommentType Type`

- `Double Order`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class CommentAttribute : Attribute, IInspectorAttributeOrder
{
	public String Comment; // 0x10
	public CommentType Type; // 0x18
	public Double Order; // 0x20

	private Double FullInspector.IInspectorAttributeOrder.Order { get; }

	// RVA: 0x34d4434 VA: 0x7595aec434
	public Void .ctor(String comment) { }
	// RVA: 0x34d4474 VA: 0x7595aec474
	public Void .ctor(CommentType type, String comment) { }
	// RVA: 0x34d44b4 VA: 0x7595aec4b4
	private Double FullInspector.IInspectorAttributeOrder.get_Order() { }
}
```