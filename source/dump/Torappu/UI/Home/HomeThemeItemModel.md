# HomeThemeItemModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeThemeDisplayData <data>k__BackingField`

- `Boolean <isUnlocked>k__BackingField`

- `Boolean <limitObtainFlag>k__BackingField`

- `String <limitObtainDesc>k__BackingField`

- `Boolean isTempSelected`

- `Boolean <isPlayerSelected>k__BackingField`

- `Boolean <hideFlag>k__BackingField`


## Properties

- `HomeThemeDisplayData data`

- `Boolean isUnlocked`

- `Boolean limitObtainFlag`

- `String limitObtainDesc`

- `Boolean isPlayerSelected`

- `Boolean hideFlag`


## Methods

- `HomeThemeDisplayData get_data()`

- `Void set_data(HomeThemeDisplayData)`

- `Boolean get_isUnlocked()`

- `Void set_isUnlocked(Boolean)`

- `Boolean get_limitObtainFlag()`

- `Void set_limitObtainFlag(Boolean)`

- `String get_limitObtainDesc()`

- `Void set_limitObtainDesc(String)`

- `Boolean get_isPlayerSelected()`

- `Void set_isPlayerSelected(Boolean)`

- `Boolean get_hideFlag()`

- `Void set_hideFlag(Boolean)`

- `Void RefreshStatus(String)`

- `PlayerHomeConditionProgress GetConditionProgress(Int32)`

- `Boolean _CheckCanLimitObtain()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeThemeItemModel : IHotfixable
{
	private HomeThemeDisplayData <data>k__BackingField; // 0x10
	private Boolean <isUnlocked>k__BackingField; // 0x18
	private Boolean <limitObtainFlag>k__BackingField; // 0x19
	private String <limitObtainDesc>k__BackingField; // 0x20
	public Boolean isTempSelected; // 0x28
	private Boolean <isPlayerSelected>k__BackingField; // 0x29
	private Boolean <hideFlag>k__BackingField; // 0x2a
	private Dictionary`2 _conditions; // 0x30
	private List`1 m_limitInfoModels; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_data; // 0x8
	private static DelegateBridge __Hotfix0_set_data; // 0x10
	private static DelegateBridge __Hotfix0_get_isUnlocked; // 0x18
	private static DelegateBridge __Hotfix0_set_isUnlocked; // 0x20
	private static DelegateBridge __Hotfix0_get_limitObtainFlag; // 0x28
	private static DelegateBridge __Hotfix0_set_limitObtainFlag; // 0x30
	private static DelegateBridge __Hotfix0_get_limitObtainDesc; // 0x38
	private static DelegateBridge __Hotfix0_set_limitObtainDesc; // 0x40
	private static DelegateBridge __Hotfix0_get_isPlayerSelected; // 0x48
	private static DelegateBridge __Hotfix0_set_isPlayerSelected; // 0x50
	private static DelegateBridge __Hotfix0_get_hideFlag; // 0x58
	private static DelegateBridge __Hotfix0_set_hideFlag; // 0x60
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x68
	private static DelegateBridge __Hotfix0_GetConditionProgress; // 0x70
	private static DelegateBridge __Hotfix0__CheckCanLimitObtain; // 0x78

	public HomeThemeDisplayData data { get; set; }
	public Boolean isUnlocked { get; set; }
	public Boolean limitObtainFlag { get; set; }
	public String limitObtainDesc { get; set; }
	public Boolean isPlayerSelected { get; set; }
	public Boolean hideFlag { get; set; }

	// RVA: 0x2840a84 VA: 0x7594e58a84
	public Void .ctor(HomeThemeDisplayData themeData, HomeThemeLimitData limitData) { }
	// RVA: 0x283fed8 VA: 0x7594e57ed8
	public HomeThemeDisplayData get_data() { }
	// RVA: 0x2840d18 VA: 0x7594e58d18
	private Void set_data(HomeThemeDisplayData value) { }
	// RVA: 0x283ff40 VA: 0x7594e57f40
	public Boolean get_isUnlocked() { }
	// RVA: 0x2840d9c VA: 0x7594e58d9c
	private Void set_isUnlocked(Boolean value) { }
	// RVA: 0x28402a4 VA: 0x7594e582a4
	public Boolean get_limitObtainFlag() { }
	// RVA: 0x2840e1c VA: 0x7594e58e1c
	private Void set_limitObtainFlag(Boolean value) { }
	// RVA: 0x284030c VA: 0x7594e5830c
	public String get_limitObtainDesc() { }
	// RVA: 0x2840e9c VA: 0x7594e58e9c
	private Void set_limitObtainDesc(String value) { }
	// RVA: 0x2840f20 VA: 0x7594e58f20
	public Boolean get_isPlayerSelected() { }
	// RVA: 0x2840f88 VA: 0x7594e58f88
	private Void set_isPlayerSelected(Boolean value) { }
	// RVA: 0x2841008 VA: 0x7594e59008
	public Boolean get_hideFlag() { }
	// RVA: 0x2841070 VA: 0x7594e59070
	private Void set_hideFlag(Boolean value) { }
	// RVA: 0x28410f0 VA: 0x7594e590f0
	public Void RefreshStatus(String presetThemeId) { }
	// RVA: 0x2840374 VA: 0x7594e58374
	public PlayerHomeConditionProgress GetConditionProgress(Int32 index) { }
	// RVA: 0x284132c VA: 0x7594e5932c
	private Boolean _CheckCanLimitObtain() { }
}
```