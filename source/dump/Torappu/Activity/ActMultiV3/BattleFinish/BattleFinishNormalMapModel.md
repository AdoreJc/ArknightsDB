# BattleFinishNormalMapModel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `String <title>k__BackingField`

- `String <desc>k__BackingField`

- `Boolean <hasStarPenalty>k__BackingField`

- `Boolean <isNewStar>k__BackingField`


## Properties

- `String title`

- `String desc`

- `Boolean hasStarPenalty`

- `Boolean isNewStar`


## Methods

- `String get_title()`

- `Void set_title(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `Boolean get_hasStarPenalty()`

- `Void set_hasStarPenalty(Boolean)`

- `Boolean get_isNewStar()`

- `Void set_isNewStar(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class BattleFinishNormalMapModel : ActMultiV3BattleFinishMapModel
{
	private List`1 m_targetList; // 0x10
	private String <title>k__BackingField; // 0x18
	private String <desc>k__BackingField; // 0x20
	private Boolean <hasStarPenalty>k__BackingField; // 0x28
	private Boolean <isNewStar>k__BackingField; // 0x29
	private static DelegateBridge __Hotfix0_get_title; // 0x0
	private static DelegateBridge __Hotfix0_set_title; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_set_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_hasStarPenalty; // 0x20
	private static DelegateBridge __Hotfix0_set_hasStarPenalty; // 0x28
	private static DelegateBridge __Hotfix0_get_isNewStar; // 0x30
	private static DelegateBridge __Hotfix0_set_isNewStar; // 0x38
	private static DelegateBridge __Hotfix0_get_targetList; // 0x40
	private static DelegateBridge __Hotfix0_get_modeType; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String title { get; set; }
	public String desc { get; set; }
	public Boolean hasStarPenalty { get; set; }
	public Boolean isNewStar { get; set; }
	public List`1 targetList { get; }
	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x317eca4 VA: 0x7595796ca4
	public String get_title() { }
	// RVA: 0x318a524 VA: 0x75957a2524
	private Void set_title(String value) { }
	// RVA: 0x317ed0c VA: 0x7595796d0c
	public String get_desc() { }
	// RVA: 0x318a5a8 VA: 0x75957a25a8
	private Void set_desc(String value) { }
	// RVA: 0x317ec3c VA: 0x7595796c3c
	public Boolean get_hasStarPenalty() { }
	// RVA: 0x318a62c VA: 0x75957a262c
	private Void set_hasStarPenalty(Boolean value) { }
	// RVA: 0x317ebd4 VA: 0x7595796bd4
	public Boolean get_isNewStar() { }
	// RVA: 0x318a6ac VA: 0x75957a26ac
	private Void set_isNewStar(Boolean value) { }
	// RVA: 0x317e644 VA: 0x7595796644
	public List`1 get_targetList() { }
	// RVA: 0x318a72c VA: 0x75957a272c
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x318a794 VA: 0x75957a2794
	public override Void LoadData(Input input) { }
	// RVA: 0x3189bdc VA: 0x75957a1bdc
	public Void .ctor() { }
}
```