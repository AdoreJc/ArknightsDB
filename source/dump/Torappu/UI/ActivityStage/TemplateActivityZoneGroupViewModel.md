# TemplateActivityZoneGroupViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `DataBundle meta`

- `String <selectedZoneId>k__BackingField`

- `Boolean <isAllTimeout>k__BackingField`


## Properties

- `String selectedZoneId`

- `Boolean isAllTimeout`


## Methods

- `String get_selectedZoneId()`

- `Void set_selectedZoneId(String)`

- `Boolean get_isAllTimeout()`

- `Void set_isAllTimeout(Boolean)`

- `Void LoadData(ActivityBasicInfo, List`1, Dictionary`2, Dictionary`2)`

- `Void SetSelectedZone(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityZoneGroupViewModel : TemplateActivityViewModel
{
	public List`1 zoneDescModelList; // 0x20
	public DataBundle meta; // 0x28
	private String <selectedZoneId>k__BackingField; // 0x30
	private Boolean <isAllTimeout>k__BackingField; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedZoneId; // 0x8
	private static DelegateBridge __Hotfix0_set_selectedZoneId; // 0x10
	private static DelegateBridge __Hotfix0_get_isAllTimeout; // 0x18
	private static DelegateBridge __Hotfix0_set_isAllTimeout; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_SetSelectedZone; // 0x30

	public String selectedZoneId { get; set; }
	public Boolean isAllTimeout { get; set; }

	// RVA: 0x30b05a4 VA: 0x75956c85a4
	public Void .ctor(Object param) { }
	// RVA: 0x30b0af4 VA: 0x75956c8af4
	public String get_selectedZoneId() { }
	// RVA: 0x30b0b5c VA: 0x75956c8b5c
	private Void set_selectedZoneId(String value) { }
	// RVA: 0x30b0be0 VA: 0x75956c8be0
	public Boolean get_isAllTimeout() { }
	// RVA: 0x30b0c48 VA: 0x75956c8c48
	private Void set_isAllTimeout(Boolean value) { }
	// RVA: 0x30b073c VA: 0x75956c873c
	public Void LoadData(ActivityBasicInfo actBasicInfo, List`1 actZoneModels, Dictionary`2 unlockParamDict, Dictionary`2 zoneMetaList) { }
	// RVA: 0x30b101c VA: 0x75956c901c
	public Void SetSelectedZone(String zoneId) { }
}
```