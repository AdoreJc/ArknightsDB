# CarvingMainChallengeInfoViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Boolean <isAutoPop>k__BackingField`

- `String <title>k__BackingField`

- `String <desc>k__BackingField`

- `String <actId>k__BackingField`


## Properties

- `Boolean isAutoPop`

- `String title`

- `String desc`

- `String actId`


## Methods

- `Boolean get_isAutoPop()`

- `Void set_isAutoPop(Boolean)`

- `String get_title()`

- `Void set_title(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `Void set_roundItemList(List`1)`

- `String get_actId()`

- `Void set_actId(String)`

- `Void LoadData(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeInfoViewModel : IHotfixable
{
	private Boolean <isAutoPop>k__BackingField; // 0x10
	private String <title>k__BackingField; // 0x18
	private String <desc>k__BackingField; // 0x20
	private List`1 <roundItemList>k__BackingField; // 0x28
	private String <actId>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_isAutoPop; // 0x0
	private static DelegateBridge __Hotfix0_set_isAutoPop; // 0x8
	private static DelegateBridge __Hotfix0_get_title; // 0x10
	private static DelegateBridge __Hotfix0_set_title; // 0x18
	private static DelegateBridge __Hotfix0_get_desc; // 0x20
	private static DelegateBridge __Hotfix0_set_desc; // 0x28
	private static DelegateBridge __Hotfix0_get_roundItemList; // 0x30
	private static DelegateBridge __Hotfix0_set_roundItemList; // 0x38
	private static DelegateBridge __Hotfix0_get_actId; // 0x40
	private static DelegateBridge __Hotfix0_set_actId; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isAutoPop { get; set; }
	public String title { get; set; }
	public String desc { get; set; }
	public List`1 roundItemList { get; set; }
	public String actId { get; set; }

	// RVA: 0x2dacf48 VA: 0x75953c4f48
	public Boolean get_isAutoPop() { }
	// RVA: 0x2dad0a8 VA: 0x75953c50a8
	private Void set_isAutoPop(Boolean value) { }
	// RVA: 0x2dacee0 VA: 0x75953c4ee0
	public String get_title() { }
	// RVA: 0x2dad128 VA: 0x75953c5128
	private Void set_title(String value) { }
	// RVA: 0x2dace78 VA: 0x75953c4e78
	public String get_desc() { }
	// RVA: 0x2dad1ac VA: 0x75953c51ac
	private Void set_desc(String value) { }
	// RVA: 0x2dacfb0 VA: 0x75953c4fb0
	public List`1 get_roundItemList() { }
	// RVA: 0x2dad230 VA: 0x75953c5230
	private Void set_roundItemList(List`1 value) { }
	// RVA: 0x2dac738 VA: 0x75953c4738
	public String get_actId() { }
	// RVA: 0x2dad2b4 VA: 0x75953c52b4
	private Void set_actId(String value) { }
	// RVA: 0x2dad338 VA: 0x75953c5338
	public Void LoadData(String activityId, Boolean isAutoPop) { }
	// RVA: 0x2dadc98 VA: 0x75953c5c98
	public Void .ctor() { }
}
```