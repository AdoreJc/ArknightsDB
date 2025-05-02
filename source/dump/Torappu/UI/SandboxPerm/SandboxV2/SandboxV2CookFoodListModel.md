# SandboxV2CookFoodListModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `Void LoadData(String, SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadMaterialItems(SandboxV2Data, PlayerSandboxV2, String, Int32)`

- `Void _LoadFoodItems(String, SandboxV2Data, PlayerSandboxV2, String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookFoodListModel : IHotfixable
{
	private readonly Dictionary`2 m_itemDict; // 0x10
	private readonly List`1 m_materialList; // 0x18
	private readonly List`1 m_itemList; // 0x20
	private readonly List`1 m_canCookItemList; // 0x28
	private readonly Dictionary`2 m_matConsumeCache; // 0x30
	private static DelegateBridge __Hotfix0_get_materials; // 0x0
	private static DelegateBridge __Hotfix0_get_allItems; // 0x8
	private static DelegateBridge __Hotfix0_get_canCookItems; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__LoadMaterialItems; // 0x20
	private static DelegateBridge __Hotfix0__LoadFoodItems; // 0x28
	private static DelegateBridge __Hotfix0__GenerateMaterials; // 0x30
	private static DelegateBridge __Hotfix0__MatComparison; // 0x38
	private static DelegateBridge __Hotfix0__ItemComparison; // 0x40
	private static DelegateBridge __Hotfix0__CanCookItemComparison; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 materials { get; }
	public List`1 allItems { get; }
	public List`1 canCookItems { get; }

	// RVA: 0x24bcf74 VA: 0x7594ad4f74
	public List`1 get_materials() { }
	// RVA: 0x24bcfdc VA: 0x7594ad4fdc
	public List`1 get_allItems() { }
	// RVA: 0x24bd044 VA: 0x7594ad5044
	public List`1 get_canCookItems() { }
	// RVA: 0x24bd0ac VA: 0x7594ad50ac
	public Void LoadData(String topicId, SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24bd1bc VA: 0x7594ad51bc
	private Void _LoadMaterialItems(SandboxV2Data gameData, PlayerSandboxV2 playerData, String waterId, Int32 waterCount) { }
	// RVA: 0x24bd5f0 VA: 0x7594ad55f0
	private Void _LoadFoodItems(String topicId, SandboxV2Data gameData, PlayerSandboxV2 playerData, String waterId, Int32 waterCount) { }
	// RVA: 0x24bddec VA: 0x7594ad5dec
	private List`1 _GenerateMaterials(PlayerSandboxV2 playerData, List`1 mats, String waterId, Int32 waterCount) { }
	// RVA: 0x24be1e0 VA: 0x7594ad61e0
	private static Int32 _MatComparison(SandboxV2AdminMainMaterialModel x, SandboxV2AdminMainMaterialModel y) { }
	// RVA: 0x24be2b4 VA: 0x7594ad62b4
	private static Int32 _ItemComparison(SandboxV2CookFoodListItemModel x, SandboxV2CookFoodListItemModel y) { }
	// RVA: 0x24be36c VA: 0x7594ad636c
	private static Int32 _CanCookItemComparison(SandboxV2CookFoodListItemModel x, SandboxV2CookFoodListItemModel y) { }
	// RVA: 0x24be4a8 VA: 0x7594ad64a8
	public Void .ctor() { }
}
```