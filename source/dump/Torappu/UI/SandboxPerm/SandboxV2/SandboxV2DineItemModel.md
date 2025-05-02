# SandboxV2DineItemModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String id`

- `UIItemViewModel item`

- `String name`

- `String usage`

- `Int32 duration`

- `Int32 stock`

- `Boolean isLast`

- `SandboxV2FoodVariantType variantType`

- `SandboxV2FoodData data`

- `Int32 priorRecipeIndex`

- `Boolean selected`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DineItemModel
{
	public String id; // 0x10
	public UIItemViewModel item; // 0x18
	public String name; // 0x20
	public String usage; // 0x28
	public Int32 duration; // 0x30
	public List`1 attributes; // 0x38
	public Int32 stock; // 0x40
	public Boolean isLast; // 0x44
	public SandboxV2FoodVariantType variantType; // 0x48
	public List`1 subMatItems; // 0x50
	public SandboxV2FoodData data; // 0x58
	public Int32 priorRecipeIndex; // 0x60
	public List`1 subMatIds; // 0x68
	public Boolean selected; // 0x70


	// RVA: 0x2505914 VA: 0x7594b1d914
	public Void .ctor() { }
}
```