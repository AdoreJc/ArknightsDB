# InspectorHeaderAttribute

**Namespace:** `FullInspector`


## Fields

- `Double Order`

- `String Header`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class InspectorHeaderAttribute : Attribute, IInspectorAttributeOrder
{
	public Double Order; // 0x10
	public String Header; // 0x18

	private Double FullInspector.IInspectorAttributeOrder.Order { get; }

	// RVA: 0x34d45b0 VA: 0x7595aec5b0
	public Void .ctor(String header) { }
	// RVA: 0x34d45ec VA: 0x7595aec5ec
	private Double FullInspector.IInspectorAttributeOrder.get_Order() { }
}
```