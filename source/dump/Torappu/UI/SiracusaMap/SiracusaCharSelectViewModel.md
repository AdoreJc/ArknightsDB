# SiracusaCharSelectViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String <selectingCharCardId>k__BackingField`

- `Boolean <allCharCardComplete>k__BackingField`

- `String <choosingCharCardId>k__BackingField`

- `String <groupId>k__BackingField`

- `Boolean <isRetro>k__BackingField`

- `Int32 viewRefreshIndex`


## Properties

- `String selectingCharCardId`

- `Boolean allCharCardComplete`

- `String choosingCharCardId`

- `String groupId`

- `Boolean isRetro`


## Methods

- `String get_selectingCharCardId()`

- `Void set_selectingCharCardId(String)`

- `Boolean get_allCharCardComplete()`

- `Void set_allCharCardComplete(Boolean)`

- `String get_choosingCharCardId()`

- `Void set_choosingCharCardId(String)`

- `String get_groupId()`

- `Void set_groupId(String)`

- `Boolean get_isRetro()`

- `Void set_isRetro(Boolean)`

- `Void LoadData(String, Boolean)`

- `Void UpdatePlayerData()`

- `Void UpdateChoosingCharCard(String)`

- `Void _InitChoosingCharCardId()`

- `SiracusaCharSelectItemViewModel GetCurChosingCharCardViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectViewModel : IHotfixable
{
	private String <selectingCharCardId>k__BackingField; // 0x10
	private Boolean <allCharCardComplete>k__BackingField; // 0x18
	public ListDict`2 charSelectItemViewModelsMap; // 0x20
	private String <choosingCharCardId>k__BackingField; // 0x28
	private String <groupId>k__BackingField; // 0x30
	private Boolean <isRetro>k__BackingField; // 0x38
	public Int32 viewRefreshIndex; // 0x3c
	private static DelegateBridge __Hotfix0_get_selectingCharCardId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectingCharCardId; // 0x8
	private static DelegateBridge __Hotfix0_get_allCharCardComplete; // 0x10
	private static DelegateBridge __Hotfix0_set_allCharCardComplete; // 0x18
	private static DelegateBridge __Hotfix0_get_choosingCharCardId; // 0x20
	private static DelegateBridge __Hotfix0_set_choosingCharCardId; // 0x28
	private static DelegateBridge __Hotfix0_get_groupId; // 0x30
	private static DelegateBridge __Hotfix0_set_groupId; // 0x38
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x40
	private static DelegateBridge __Hotfix0_set_isRetro; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x58
	private static DelegateBridge __Hotfix0_UpdateChoosingCharCard; // 0x60
	private static DelegateBridge __Hotfix0__InitChoosingCharCardId; // 0x68
	private static DelegateBridge __Hotfix0_GetCurChosingCharCardViewModel; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String selectingCharCardId { get; set; }
	public Boolean allCharCardComplete { get; set; }
	public String choosingCharCardId { get; set; }
	public String groupId { get; set; }
	public Boolean isRetro { get; set; }

	// RVA: 0x23f33f4 VA: 0x7594a0b3f4
	public String get_selectingCharCardId() { }
	// RVA: 0x23f345c VA: 0x7594a0b45c
	private Void set_selectingCharCardId(String value) { }
	// RVA: 0x23f34e0 VA: 0x7594a0b4e0
	public Boolean get_allCharCardComplete() { }
	// RVA: 0x23f3548 VA: 0x7594a0b548
	private Void set_allCharCardComplete(Boolean value) { }
	// RVA: 0x23efeb0 VA: 0x7594a07eb0
	public String get_choosingCharCardId() { }
	// RVA: 0x23f35c8 VA: 0x7594a0b5c8
	private Void set_choosingCharCardId(String value) { }
	// RVA: 0x23f364c VA: 0x7594a0b64c
	public String get_groupId() { }
	// RVA: 0x23f36b4 VA: 0x7594a0b6b4
	private Void set_groupId(String value) { }
	// RVA: 0x23f1858 VA: 0x7594a09858
	public Boolean get_isRetro() { }
	// RVA: 0x23f3738 VA: 0x7594a0b738
	private Void set_isRetro(Boolean value) { }
	// RVA: 0x23ef10c VA: 0x7594a0710c
	public Void LoadData(String groupId, Boolean isRetro) { }
	// RVA: 0x23f065c VA: 0x7594a0865c
	public Void UpdatePlayerData() { }
	// RVA: 0x23eff18 VA: 0x7594a07f18
	public Void UpdateChoosingCharCard(String charCardId) { }
	// RVA: 0x23f39d0 VA: 0x7594a0b9d0
	private Void _InitChoosingCharCardId() { }
	// RVA: 0x23f14d4 VA: 0x7594a094d4
	public SiracusaCharSelectItemViewModel GetCurChosingCharCardViewModel() { }
	// RVA: 0x23ef09c VA: 0x7594a0709c
	public Void .ctor() { }
}
```