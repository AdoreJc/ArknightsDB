# SandboxV2FoodData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 duration`

- `Int32 sortId`


## Methods

- `Boolean ShouldSerializerecipes()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2FoodData
{
	public String id; // 0x10
	public List`1 attributes; // 0x18
	public List`1 recipes; // 0x20
	public List`1 variants; // 0x28
	public Int32 duration; // 0x30
	public Int32 sortId; // 0x34


	// RVA: 0x34f1ec0 VA: 0x7595b09ec0
	public Boolean ShouldSerializerecipes() { }
	// RVA: 0x34f1f14 VA: 0x7595b09f14
	public Void .ctor() { }
}
```