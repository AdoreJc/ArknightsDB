# BossRushRelicUpgradeViewModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String <actId>k__BackingField`

- `BossRushRelicNodeModel relicData`

- `String <upgradeItemName>k__BackingField`

- `Int32 <upgradeItemCurCount>k__BackingField`


## Properties

- `String actId`

- `String upgradeItemName`

- `Int32 upgradeItemCurCount`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_upgradeItemName()`

- `Void set_upgradeItemName(String)`

- `Int32 get_upgradeItemCurCount()`

- `Void set_upgradeItemCurCount(Int32)`

- `Void LoadDataList(String, BossRushRelicNodeModel, String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicUpgradeViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	public BossRushRelicNodeModel relicData; // 0x18
	private String <upgradeItemName>k__BackingField; // 0x20
	private Int32 <upgradeItemCurCount>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_upgradeItemName; // 0x10
	private static DelegateBridge __Hotfix0_set_upgradeItemName; // 0x18
	private static DelegateBridge __Hotfix0_get_upgradeItemCurCount; // 0x20
	private static DelegateBridge __Hotfix0_set_upgradeItemCurCount; // 0x28
	private static DelegateBridge __Hotfix0_LoadDataList; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String actId { get; set; }
	public String upgradeItemName { get; set; }
	public Int32 upgradeItemCurCount { get; set; }

	// RVA: 0x2e5fc58 VA: 0x7595477c58
	public String get_actId() { }
	// RVA: 0x2e5fe00 VA: 0x7595477e00
	private Void set_actId(String value) { }
	// RVA: 0x2e5fb88 VA: 0x7595477b88
	public String get_upgradeItemName() { }
	// RVA: 0x2e5fe84 VA: 0x7595477e84
	private Void set_upgradeItemName(String value) { }
	// RVA: 0x2e5fbf0 VA: 0x7595477bf0
	public Int32 get_upgradeItemCurCount() { }
	// RVA: 0x2e5ff08 VA: 0x7595477f08
	private Void set_upgradeItemCurCount(Int32 value) { }
	// RVA: 0x2e5f3f8 VA: 0x75954773f8
	public Void LoadDataList(String aId, BossRushRelicNodeModel data, String tokenName, Int32 curTokenCount) { }
	// RVA: 0x2e5f388 VA: 0x7595477388
	public Void .ctor() { }
}
```