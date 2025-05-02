# SandboxV2AdminMainShopViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean hasGoldItem`

- `String goldItemId`

- `Int32 goldCount`

- `Boolean hasDimensionCoinItem`

- `String dimensionCoinItemId`

- `Int32 dimensionCoinCount`

- `Int32 refreshRemain`

- `String npcName`

- `String dialogDesc`

- `String topicId`

- `SandboxV2ShopDialogData m_dialogData`

- `Boolean m_isAllSoldOut`


## Methods

- `Void LoadData(String)`

- `Void RefreshDialogDesc(Boolean)`

- `SandboxV2AdminMainShopItemViewModel GetItemModel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopViewModel : IHotfixable
{
	public List`1 itemList; // 0x10
	public Boolean hasGoldItem; // 0x18
	public String goldItemId; // 0x20
	public Int32 goldCount; // 0x28
	public Boolean hasDimensionCoinItem; // 0x2c
	public String dimensionCoinItemId; // 0x30
	public Int32 dimensionCoinCount; // 0x38
	public Int32 refreshRemain; // 0x3c
	public String npcName; // 0x40
	public String dialogDesc; // 0x48
	public String topicId; // 0x50
	private SandboxV2ShopDialogData m_dialogData; // 0x58
	private Boolean m_isAllSoldOut; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshDialogDesc; // 0x8
	private static DelegateBridge __Hotfix0_GetItemModel; // 0x10
	private static DelegateBridge __Hotfix0_CheckShopActive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24e9ff0 VA: 0x7594b01ff0
	public Void LoadData(String topicId) { }
	// RVA: 0x24e9b1c VA: 0x7594b01b1c
	public Void RefreshDialogDesc(Boolean isAfterBuy) { }
	// RVA: 0x24ea854 VA: 0x7594b02854
	public SandboxV2AdminMainShopItemViewModel GetItemModel(Int32 index) { }
	// RVA: 0x24ebb2c VA: 0x7594b03b2c
	public static Boolean CheckShopActive(String topicId) { }
	// RVA: 0x24ebc40 VA: 0x7594b03c40
	public Void .ctor() { }
}
```