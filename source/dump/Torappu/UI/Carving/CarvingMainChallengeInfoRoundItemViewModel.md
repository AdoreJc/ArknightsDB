# CarvingMainChallengeInfoRoundItemViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String <roundTitle>k__BackingField`


## Properties

- `String roundTitle`


## Methods

- `String get_roundTitle()`

- `Void set_roundTitle(String)`

- `Void set_materialItemList(List`1)`

- `Void LoadData(String, Dictionary`2, Int32, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeInfoRoundItemViewModel : IHotfixable
{
	private String <roundTitle>k__BackingField; // 0x10
	private List`1 <materialItemList>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_roundTitle; // 0x0
	private static DelegateBridge __Hotfix0_set_roundTitle; // 0x8
	private static DelegateBridge __Hotfix0_get_materialItemList; // 0x10
	private static DelegateBridge __Hotfix0_set_materialItemList; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String roundTitle { get; set; }
	public List`1 materialItemList { get; set; }

	// RVA: 0x2dab4ec VA: 0x75953c34ec
	public String get_roundTitle() { }
	// RVA: 0x2dadd08 VA: 0x75953c5d08
	private Void set_roundTitle(String value) { }
	// RVA: 0x2dab554 VA: 0x75953c3554
	public List`1 get_materialItemList() { }
	// RVA: 0x2dadd8c VA: 0x75953c5d8c
	private Void set_materialItemList(List`1 value) { }
	// RVA: 0x2dad7e0 VA: 0x75953c57e0
	public Void LoadData(String actId, Dictionary`2 fixedMaterialList, Int32 roundNum, Dictionary`2 materialDataMap) { }
	// RVA: 0x2dad770 VA: 0x75953c5770
	public Void .ctor() { }
}
```