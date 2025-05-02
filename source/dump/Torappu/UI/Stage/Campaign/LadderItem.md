# LadderItem

**Namespace:** `Torappu.UI.Stage.Campaign`


## Fields

- `Type m_type`


## Properties

- `Type type`


## Methods

- `Type get_type()`

- `Void AddData(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Campaign
public class LadderItem
{
	private Type m_type; // 0x10
	private List`1 m_dataList; // 0x18

	public List`1 dataList { get; }
	public Type type { get; }

	// RVA: 0x2fe1f0c VA: 0x75955f9f0c
	public List`1 get_dataList() { }
	// RVA: 0x2fe1f14 VA: 0x75955f9f14
	public Type get_type() { }
	// RVA: 0x2fe1f1c VA: 0x75955f9f1c
	public Void .ctor(Type type) { }
	// RVA: 0x2fe1fb4 VA: 0x75955f9fb4
	public Void AddData(Int32 val) { }
}
```