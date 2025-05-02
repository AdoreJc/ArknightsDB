# ItemDB

**Namespace:** `Torappu`


## Methods

- `Boolean TryGetPotentionItemId(Int32, ProfessionCategory, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ItemDB : ConstTable`2
{
	private List`1 m_specialTypesInItemRepo; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_get_specialTypesInItemRepo; // 0x8
	private static DelegateBridge __Hotfix0_TryGetPotentionItemId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 specialTypesInItemRepo { get; }

	// RVA: 0x31f2d64 VA: 0x759580ad64
	protected override Void OnInit() { }
	// RVA: 0x31f2df4 VA: 0x759580adf4
	public List`1 get_specialTypesInItemRepo() { }
	// RVA: 0x31f3028 VA: 0x759580b028
	public Boolean TryGetPotentionItemId(Int32 rarity, ProfessionCategory profession, out String itemId) { }
	// RVA: 0x31f31b0 VA: 0x759580b1b0
	public Void .ctor() { }
}
```