# SandboxV2AdminMainCookPanelModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `SandboxV2AdminMainCookInitParam <initParam>k__BackingField`

- `SandboxV2AdminMainCookType <currCookType>k__BackingField`

- `Boolean <initShow>k__BackingField`

- `Boolean m_drinkActive`

- `Boolean m_drinkDirty`

- `Boolean m_foodListActive`

- `Boolean m_foodListDirty`

- `Boolean m_freeCookActive`

- `Boolean m_freeCookDirty`


## Properties

- `String topicId`

- `SandboxV2AdminMainCookInitParam initParam`

- `SandboxV2AdminMainCookType currCookType`

- `Boolean initShow`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `SandboxV2AdminMainCookInitParam get_initParam()`

- `Void set_initParam(SandboxV2AdminMainCookInitParam)`

- `SandboxV2AdminMainCookType get_currCookType()`

- `Void set_currCookType(SandboxV2AdminMainCookType)`

- `Boolean get_initShow()`

- `Void set_initShow(Boolean)`

- `Void LoadData(String, SandboxV2AdminMainCookInitParam)`

- `Void RefreshPlayerData()`

- `Boolean CheckTypeActive(SandboxV2AdminMainCookType)`

- `Boolean SetCookType(SandboxV2AdminMainCookType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainCookPanelModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private SandboxV2AdminMainCookInitParam <initParam>k__BackingField; // 0x18
	private SandboxV2AdminMainCookType <currCookType>k__BackingField; // 0x20
	private Boolean <initShow>k__BackingField; // 0x24
	public readonly SandboxV2CookDrinkModel drinkModel; // 0x28
	public readonly SandboxV2CookFoodListModel foodListModel; // 0x30
	public readonly SandboxV2CookFreeCookModel freeCookModel; // 0x38
	private Boolean m_drinkActive; // 0x40
	private Boolean m_drinkDirty; // 0x41
	private Boolean m_foodListActive; // 0x42
	private Boolean m_foodListDirty; // 0x43
	private Boolean m_freeCookActive; // 0x44
	private Boolean m_freeCookDirty; // 0x45
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_initParam; // 0x10
	private static DelegateBridge __Hotfix0_set_initParam; // 0x18
	private static DelegateBridge __Hotfix0_get_currCookType; // 0x20
	private static DelegateBridge __Hotfix0_set_currCookType; // 0x28
	private static DelegateBridge __Hotfix0_get_initShow; // 0x30
	private static DelegateBridge __Hotfix0_set_initShow; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x48
	private static DelegateBridge __Hotfix0_CheckTypeActive; // 0x50
	private static DelegateBridge __Hotfix0_SetCookType; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String topicId { get; set; }
	public SandboxV2AdminMainCookInitParam initParam { get; set; }
	public SandboxV2AdminMainCookType currCookType { get; set; }
	public Boolean initShow { get; set; }

	// RVA: 0x24c8260 VA: 0x7594ae0260
	public String get_topicId() { }
	// RVA: 0x24cd5a0 VA: 0x7594ae55a0
	private Void set_topicId(String value) { }
	// RVA: 0x24cd624 VA: 0x7594ae5624
	public SandboxV2AdminMainCookInitParam get_initParam() { }
	// RVA: 0x24cd68c VA: 0x7594ae568c
	private Void set_initParam(SandboxV2AdminMainCookInitParam value) { }
	// RVA: 0x24c5850 VA: 0x7594add850
	public SandboxV2AdminMainCookType get_currCookType() { }
	// RVA: 0x24cd710 VA: 0x7594ae5710
	private Void set_currCookType(SandboxV2AdminMainCookType value) { }
	// RVA: 0x24c58b8 VA: 0x7594add8b8
	public Boolean get_initShow() { }
	// RVA: 0x24cd78c VA: 0x7594ae578c
	private Void set_initShow(Boolean value) { }
	// RVA: 0x24caf7c VA: 0x7594ae2f7c
	public Void LoadData(String topicId, SandboxV2AdminMainCookInitParam initParam) { }
	// RVA: 0x24ca640 VA: 0x7594ae2640
	public Void RefreshPlayerData() { }
	// RVA: 0x24cd80c VA: 0x7594ae580c
	public Boolean CheckTypeActive(SandboxV2AdminMainCookType type) { }
	// RVA: 0x24cd8c0 VA: 0x7594ae58c0
	public Boolean SetCookType(SandboxV2AdminMainCookType cookType, Boolean init) { }
	// RVA: 0x24cdb70 VA: 0x7594ae5b70
	public Void .ctor() { }
}
```