# FifthAnnivExploreGroupChooseViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreGroupChoiceItemViewModel selectedChoiceItemViewModel`

- `Boolean <hasSelectHeritage>k__BackingField`

- `Boolean <hasHeritageData>k__BackingField`


## Properties

- `Boolean hasSelectHeritage`

- `Boolean hasHeritageData`


## Methods

- `Boolean get_hasSelectHeritage()`

- `Void set_hasSelectHeritage(Boolean)`

- `Boolean get_hasHeritageData()`

- `Void set_hasHeritageData(Boolean)`

- `Void LoadData()`

- `Void SetHeritageSelect(Boolean)`

- `Void SelectGroup(Int32)`

- `PlayerExploreGameResult _GetLastGameResultFromPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupChooseViewModel : IHotfixable
{
	public FifthAnnivExploreGroupChoiceItemViewModel selectedChoiceItemViewModel; // 0x10
	public List`1 groupChoiceItemViewModels; // 0x18
	private Boolean <hasSelectHeritage>k__BackingField; // 0x20
	private Boolean <hasHeritageData>k__BackingField; // 0x21
	private static DelegateBridge __Hotfix0_get_hasSelectHeritage; // 0x0
	private static DelegateBridge __Hotfix0_set_hasSelectHeritage; // 0x8
	private static DelegateBridge __Hotfix0_get_hasHeritageData; // 0x10
	private static DelegateBridge __Hotfix0_set_hasHeritageData; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_SetHeritageSelect; // 0x28
	private static DelegateBridge __Hotfix0_SelectGroup; // 0x30
	private static DelegateBridge __Hotfix0__GetLastGameResultFromPlayerData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean hasSelectHeritage { get; set; }
	public Boolean hasHeritageData { get; set; }

	// RVA: 0x291bbdc VA: 0x7594f33bdc
	public Boolean get_hasSelectHeritage() { }
	// RVA: 0x291c304 VA: 0x7594f34304
	private Void set_hasSelectHeritage(Boolean value) { }
	// RVA: 0x291bb74 VA: 0x7594f33b74
	public Boolean get_hasHeritageData() { }
	// RVA: 0x291c384 VA: 0x7594f34384
	private Void set_hasHeritageData(Boolean value) { }
	// RVA: 0x291bc44 VA: 0x7594f33c44
	public Void LoadData() { }
	// RVA: 0x291c0f4 VA: 0x7594f340f4
	public Void SetHeritageSelect(Boolean value) { }
	// RVA: 0x291bf88 VA: 0x7594f33f88
	public Void SelectGroup(Int32 position) { }
	// RVA: 0x291c404 VA: 0x7594f34404
	private PlayerExploreGameResult _GetLastGameResultFromPlayerData() { }
	// RVA: 0x291c778 VA: 0x7594f34778
	public Void .ctor() { }
}
```