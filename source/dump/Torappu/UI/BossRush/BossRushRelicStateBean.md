# BossRushRelicStateBean

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushRelicViewProperty viewProperty`

- `String <actId>k__BackingField`


## Properties

- `String actId`

- `String tokenName`

- `Int32 tokenCurCount`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_tokenName()`

- `Int32 get_tokenCurCount()`

- `Void LoadData(String)`

- `Void UpdateChange(Boolean)`

- `Void SwitchRelic(String)`

- `BossRushRelicNodeModel GetSelectingRelicNodeModel()`

- `String GetSelectingRelicId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicStateBean : IStateBean, IHotfixable
{
	public BossRushRelicViewProperty viewProperty; // 0x10
	private String <actId>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_tokenName; // 0x10
	private static DelegateBridge __Hotfix0_get_tokenCurCount; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateChange; // 0x28
	private static DelegateBridge __Hotfix0_SwitchRelic; // 0x30
	private static DelegateBridge __Hotfix0_GetSelectingRelicNodeModel; // 0x38
	private static DelegateBridge __Hotfix0_GetSelectingRelicId; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String actId { get; set; }
	public String tokenName { get; }
	public Int32 tokenCurCount { get; }

	// RVA: 0x2e5cb04 VA: 0x7595474b04
	public String get_actId() { }
	// RVA: 0x2e5d744 VA: 0x7595475744
	private Void set_actId(String value) { }
	// RVA: 0x2e5d080 VA: 0x7595475080
	public String get_tokenName() { }
	// RVA: 0x2e5d12c VA: 0x759547512c
	public Int32 get_tokenCurCount() { }
	// RVA: 0x2e5c384 VA: 0x7595474384
	public Void LoadData(String aId) { }
	// RVA: 0x2e5c528 VA: 0x7595474528
	public Void UpdateChange(Boolean refreshSelect) { }
	// RVA: 0x2e5d270 VA: 0x7595475270
	public Void SwitchRelic(String relicId) { }
	// RVA: 0x2e5cfe8 VA: 0x7595474fe8
	public BossRushRelicNodeModel GetSelectingRelicNodeModel() { }
	// RVA: 0x2e5cb6c VA: 0x7595474b6c
	public String GetSelectingRelicId() { }
	// RVA: 0x2e5d634 VA: 0x7595475634
	public Void .ctor() { }
}
```