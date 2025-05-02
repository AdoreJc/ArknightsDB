# FifthAnnivExploreGroupChooseStateBean

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreGroupChooseProperty property`


## Properties

- `Boolean needConfirmHeritage`

- `String selectedGroupId`

- `Boolean hasSelectHeritage`


## Methods

- `Boolean get_needConfirmHeritage()`

- `String get_selectedGroupId()`

- `Boolean get_hasSelectHeritage()`

- `Void LoadData()`

- `Void SelectGroup(Int32)`

- `Void SetSelectHeritage(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupChooseStateBean : IStateBean, IHotfixable
{
	public FifthAnnivExploreGroupChooseProperty property; // 0x10
	private static DelegateBridge __Hotfix0_get_needConfirmHeritage; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedGroupId; // 0x8
	private static DelegateBridge __Hotfix0_get_hasSelectHeritage; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_SelectGroup; // 0x20
	private static DelegateBridge __Hotfix0_SetSelectHeritage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean needConfirmHeritage { get; }
	public String selectedGroupId { get; }
	public Boolean hasSelectHeritage { get; }

	// RVA: 0x291aa40 VA: 0x7594f32a40
	public Boolean get_needConfirmHeritage() { }
	// RVA: 0x291b370 VA: 0x7594f33370
	public String get_selectedGroupId() { }
	// RVA: 0x291b42c VA: 0x7594f3342c
	public Boolean get_hasSelectHeritage() { }
	// RVA: 0x291b1ec VA: 0x7594f331ec
	public Void LoadData() { }
	// RVA: 0x291b2a0 VA: 0x7594f332a0
	public Void SelectGroup(Int32 position) { }
	// RVA: 0x291afb8 VA: 0x7594f32fb8
	public Void SetSelectHeritage(Boolean select) { }
	// RVA: 0x291b140 VA: 0x7594f33140
	public Void .ctor() { }
}
```