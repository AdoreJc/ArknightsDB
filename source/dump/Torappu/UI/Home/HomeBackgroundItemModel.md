# HomeBackgroundItemModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeBackgroundSingleData <data>k__BackingField`

- `Boolean <isUnlocked>k__BackingField`

- `Boolean isTempSelected`

- `Boolean <isPlayerSelected>k__BackingField`

- `Boolean <showLimitDesc>k__BackingField`

- `String <limitDesc>k__BackingField`


## Properties

- `HomeBackgroundSingleData data`

- `Boolean isUnlocked`

- `Boolean isPlayerSelected`

- `Boolean showLimitDesc`

- `String limitDesc`


## Methods

- `HomeBackgroundSingleData get_data()`

- `Void set_data(HomeBackgroundSingleData)`

- `Boolean get_isUnlocked()`

- `Void set_isUnlocked(Boolean)`

- `Boolean get_isPlayerSelected()`

- `Void set_isPlayerSelected(Boolean)`

- `Boolean get_showLimitDesc()`

- `Void set_showLimitDesc(Boolean)`

- `String get_limitDesc()`

- `Void set_limitDesc(String)`

- `Void RefreshStatus(String)`

- `PlayerHomeConditionProgress GetConditionProgress(Int32)`

- `Boolean CheckDisplay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundItemModel : IHotfixable
{
	private HomeBackgroundSingleData <data>k__BackingField; // 0x10
	private Boolean <isUnlocked>k__BackingField; // 0x18
	public Boolean isTempSelected; // 0x19
	private Boolean <isPlayerSelected>k__BackingField; // 0x1a
	private Boolean <showLimitDesc>k__BackingField; // 0x1b
	private String <limitDesc>k__BackingField; // 0x20
	private Dictionary`2 _conditions; // 0x28
	private List`1 m_limitInfoModels; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_data; // 0x8
	private static DelegateBridge __Hotfix0_set_data; // 0x10
	private static DelegateBridge __Hotfix0_get_isUnlocked; // 0x18
	private static DelegateBridge __Hotfix0_set_isUnlocked; // 0x20
	private static DelegateBridge __Hotfix0_get_isPlayerSelected; // 0x28
	private static DelegateBridge __Hotfix0_set_isPlayerSelected; // 0x30
	private static DelegateBridge __Hotfix0_get_showLimitDesc; // 0x38
	private static DelegateBridge __Hotfix0_set_showLimitDesc; // 0x40
	private static DelegateBridge __Hotfix0_get_limitDesc; // 0x48
	private static DelegateBridge __Hotfix0_set_limitDesc; // 0x50
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x58
	private static DelegateBridge __Hotfix0_GetConditionProgress; // 0x60
	private static DelegateBridge __Hotfix0_CheckDisplay; // 0x68

	public HomeBackgroundSingleData data { get; set; }
	public Boolean isUnlocked { get; set; }
	public Boolean isPlayerSelected { get; set; }
	public Boolean showLimitDesc { get; set; }
	public String limitDesc { get; set; }

	// RVA: 0x2834e7c VA: 0x7594e4ce7c
	public Void .ctor(HomeBackgroundSingleData bgData, HomeBackgroundLimitData limitData) { }
	// RVA: 0x2834a7c VA: 0x7594e4ca7c
	public HomeBackgroundSingleData get_data() { }
	// RVA: 0x2835108 VA: 0x7594e4d108
	private Void set_data(HomeBackgroundSingleData value) { }
	// RVA: 0x2834ae4 VA: 0x7594e4cae4
	public Boolean get_isUnlocked() { }
	// RVA: 0x283518c VA: 0x7594e4d18c
	private Void set_isUnlocked(Boolean value) { }
	// RVA: 0x283520c VA: 0x7594e4d20c
	public Boolean get_isPlayerSelected() { }
	// RVA: 0x2835274 VA: 0x7594e4d274
	private Void set_isPlayerSelected(Boolean value) { }
	// RVA: 0x28352f4 VA: 0x7594e4d2f4
	public Boolean get_showLimitDesc() { }
	// RVA: 0x283535c VA: 0x7594e4d35c
	private Void set_showLimitDesc(Boolean value) { }
	// RVA: 0x28353dc VA: 0x7594e4d3dc
	public String get_limitDesc() { }
	// RVA: 0x2835444 VA: 0x7594e4d444
	private Void set_limitDesc(String value) { }
	// RVA: 0x28354c8 VA: 0x7594e4d4c8
	public Void RefreshStatus(String presetBackgroundId) { }
	// RVA: 0x2835674 VA: 0x7594e4d674
	public PlayerHomeConditionProgress GetConditionProgress(Int32 index) { }
	// RVA: 0x28357a4 VA: 0x7594e4d7a4
	public Boolean CheckDisplay() { }
}
```