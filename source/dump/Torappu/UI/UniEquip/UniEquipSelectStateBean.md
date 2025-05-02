# UniEquipSelectStateBean

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UniEquipSelectProperty property`

- `String <targetEquipId>k__BackingField`


## Properties

- `String charId`

- `String targetEquipId`

- `UniEquipSelectViewModel targetSelectViewModel`


## Methods

- `String get_charId()`

- `Void set_targetEquipId(String)`

- `String get_targetEquipId()`

- `UniEquipSelectViewModel get_targetSelectViewModel()`

- `Void RefreshViewModel(Int32, String, Boolean, Boolean)`

- `Void _GeneTalentDesc(UniEquipSelectList, PlayerCharacter)`

- `Void _CalculateAttibute(UniEquipSelectList, PlayerCharacter)`

- `Void OnSelectUniEquip(String)`

- `UniEquipSelectViewModel GetViewModelById(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipSelectStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public UniEquipSelectProperty property; // 0x18
	private String <targetEquipId>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_charId; // 0x0
	private static DelegateBridge __Hotfix0_set_targetEquipId; // 0x8
	private static DelegateBridge __Hotfix0_get_targetEquipId; // 0x10
	private static DelegateBridge __Hotfix0_get_targetSelectViewModel; // 0x18
	private static DelegateBridge __Hotfix0_RefreshViewModel; // 0x20
	private static DelegateBridge __Hotfix0__GeneTalentDesc; // 0x28
	private static DelegateBridge __Hotfix0__CalculateAttibute; // 0x30
	private static DelegateBridge __Hotfix0_OnSelectUniEquip; // 0x38
	private static DelegateBridge __Hotfix0_GetViewModelById; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String charId { get; }
	public String targetEquipId { get; set; }
	public UniEquipSelectViewModel targetSelectViewModel { get; }

	// RVA: 0x2309d94 VA: 0x7594921d94
	public String get_charId() { }
	// RVA: 0x2309e28 VA: 0x7594921e28
	public Void set_targetEquipId(String value) { }
	// RVA: 0x2309eac VA: 0x7594921eac
	public String get_targetEquipId() { }
	// RVA: 0x2309f14 VA: 0x7594921f14
	public UniEquipSelectViewModel get_targetSelectViewModel() { }
	// RVA: 0x2309ff0 VA: 0x7594921ff0
	public Void RefreshViewModel(Int32 charInstId, String initSelectEquipId, Boolean isAvgRunning, Boolean needFocus) { }
	// RVA: 0x230aa58 VA: 0x7594922a58
	private Void _GeneTalentDesc(UniEquipSelectList selectList, PlayerCharacter playerChar) { }
	// RVA: 0x230aec4 VA: 0x7594922ec4
	private Void _CalculateAttibute(UniEquipSelectList selectList, PlayerCharacter playerChar) { }
	// RVA: 0x230b250 VA: 0x7594923250
	public Void OnSelectUniEquip(String uniEquipId) { }
	// RVA: 0x230b554 VA: 0x7594923554
	public UniEquipSelectViewModel GetViewModelById(String equipId) { }
	// RVA: 0x230b62c VA: 0x759492362c
	public Void .ctor() { }
}
```