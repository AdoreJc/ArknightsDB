# DetailInfo

**Namespace:** ` `


## Fields

- `String scene`

- `Int32 subTypeId`

- `String name`

- `String description`

- `String iconId`


## Methods

- `Boolean CheckAbleToClick()`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DetailInfo : IHotfixable
{
	public String scene; // 0x10
	public List`1 battleShop; // 0x18
	public List`1 battleList; // 0x20
	public List`1 wishList; // 0x28
	public Int32 subTypeId; // 0x30
	public String name; // 0x38
	public String description; // 0x40
	public String iconId; // 0x48
	private static DelegateBridge __Hotfix0_CheckAbleToClick; // 0x0
	private static DelegateBridge __Hotfix0_Clear; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2a1a118 VA: 0x7595032118
	public Boolean CheckAbleToClick() { }
	// RVA: 0x2a19f38 VA: 0x7595031f38
	public Void Clear() { }
	// RVA: 0x2a1a0a8 VA: 0x75950320a8
	public Void .ctor() { }
}
```