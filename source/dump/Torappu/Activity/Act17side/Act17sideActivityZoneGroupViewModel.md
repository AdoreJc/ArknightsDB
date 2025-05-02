# Act17sideActivityZoneGroupViewModel

**Namespace:** `Torappu.Activity.Act17side`


## Fields

- `Boolean <isAllTimeout>k__BackingField`

- `String <selectedZoneId>k__BackingField`


## Properties

- `Boolean isAllTimeout`

- `String selectedZoneId`


## Methods

- `Boolean get_isAllTimeout()`

- `Void set_isAllTimeout(Boolean)`

- `String get_selectedZoneId()`

- `Void set_selectedZoneId(String)`

- `Boolean CheckIfZoneUnlock(String)`

- `Void LoadData(ActivityBasicInfo, Act17sideData)`

- `Void SetSelectedZone(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act17side
public class Act17sideActivityZoneGroupViewModel : TemplateActivityViewModel, IHotfixable
{
	public List`1 zoneDescModelList; // 0x20
	private Boolean <isAllTimeout>k__BackingField; // 0x28
	private String <selectedZoneId>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_isAllTimeout; // 0x0
	private static DelegateBridge __Hotfix0_set_isAllTimeout; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedZoneId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedZoneId; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfZoneUnlock; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_SetSelectedZone; // 0x38

	public Boolean isAllTimeout { get; set; }
	public String selectedZoneId { get; set; }

	// RVA: 0x341d508 VA: 0x7595a35508
	public Boolean get_isAllTimeout() { }
	// RVA: 0x341d74c VA: 0x7595a3574c
	private Void set_isAllTimeout(Boolean value) { }
	// RVA: 0x341d7cc VA: 0x7595a357cc
	public String get_selectedZoneId() { }
	// RVA: 0x341d834 VA: 0x7595a35834
	private Void set_selectedZoneId(String value) { }
	// RVA: 0x341d8b8 VA: 0x7595a358b8
	public Boolean CheckIfZoneUnlock(String zoneId) { }
	// RVA: 0x341d9e8 VA: 0x7595a359e8
	public Void .ctor(Object param) { }
	// RVA: 0x341db7c VA: 0x7595a35b7c
	public Void LoadData(ActivityBasicInfo actBasicInfo, Act17sideData actData) { }
	// RVA: 0x341e8b8 VA: 0x7595a368b8
	public Void SetSelectedZone(String zoneId) { }
}
```