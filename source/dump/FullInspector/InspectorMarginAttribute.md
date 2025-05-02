# InspectorMarginAttribute

**Namespace:** `FullInspector`


## Fields

- `Int32 Margin`

- `Double Order`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class InspectorMarginAttribute : Attribute, IInspectorAttributeOrder
{
	public Int32 Margin; // 0x10
	public Double Order; // 0x18

	private Double FullInspector.IInspectorAttributeOrder.Order { get; }

	// RVA: 0x34d4638 VA: 0x7595aec638
	public Void .ctor(Int32 margin) { }
	// RVA: 0x34d4660 VA: 0x7595aec660
	private Double FullInspector.IInspectorAttributeOrder.get_Order() { }
}
```