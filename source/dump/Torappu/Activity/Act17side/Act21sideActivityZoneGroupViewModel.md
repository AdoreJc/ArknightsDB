# Act21sideActivityZoneGroupViewModel

**Namespace:** `Torappu.Activity.Act17side`


## Fields

- `Boolean <isAllTimeout>k__BackingField`


## Properties

- `Boolean isAllTimeout`

- `Boolean hasNewSign`


## Methods

- `Void LoadData(ActivityBasicInfo, List`1)`

- `Boolean get_isAllTimeout()`

- `Void set_isAllTimeout(Boolean)`

- `Boolean get_hasNewSign()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act17side
public class Act21sideActivityZoneGroupViewModel : TemplateActivityViewModel, IHotfixable
{
	public List`1 zoneDescList; // 0x20
	private Boolean <isAllTimeout>k__BackingField; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_get_isAllTimeout; // 0x10
	private static DelegateBridge __Hotfix0_set_isAllTimeout; // 0x18
	private static DelegateBridge __Hotfix0_get_hasNewSign; // 0x20

	public Boolean isAllTimeout { get; set; }
	public Boolean hasNewSign { get; }

	// RVA: 0x341eafc VA: 0x7595a36afc
	public Void .ctor(Object param) { }
	// RVA: 0x341ec90 VA: 0x7595a36c90
	public Void LoadData(ActivityBasicInfo actBasicInfo, List`1 zoneViewModelList) { }
	// RVA: 0x341f264 VA: 0x7595a37264
	public Boolean get_isAllTimeout() { }
	// RVA: 0x341ef00 VA: 0x7595a36f00
	private Void set_isAllTimeout(Boolean value) { }
	// RVA: 0x341f2cc VA: 0x7595a372cc
	public Boolean get_hasNewSign() { }
}
```