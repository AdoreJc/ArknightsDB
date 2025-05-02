# FifthAnnivExploreGroupHeritageViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `PlayerExploreGameResult lastResult`

- `Boolean <hasSelectHeritage>k__BackingField`


## Properties

- `Boolean hasHeritageData`

- `Boolean hasSelectHeritage`


## Methods

- `Boolean get_hasHeritageData()`

- `Boolean get_hasSelectHeritage()`

- `Void set_hasSelectHeritage(Boolean)`

- `Void LoadData(Boolean)`

- `Void SetSelectHeritage(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupHeritageViewModel : IHotfixable
{
	public PlayerExploreGameResult lastResult; // 0x10
	private Boolean <hasSelectHeritage>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_hasHeritageData; // 0x0
	private static DelegateBridge __Hotfix0_get_hasSelectHeritage; // 0x8
	private static DelegateBridge __Hotfix0_set_hasSelectHeritage; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_SetSelectHeritage; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean hasHeritageData { get; }
	public Boolean hasSelectHeritage { get; set; }

	// RVA: 0x29328e8 VA: 0x7594f4a8e8
	public Boolean get_hasHeritageData() { }
	// RVA: 0x2932958 VA: 0x7594f4a958
	public Boolean get_hasSelectHeritage() { }
	// RVA: 0x2933e04 VA: 0x7594f4be04
	private Void set_hasSelectHeritage(Boolean value) { }
	// RVA: 0x2933944 VA: 0x7594f4b944
	public Void LoadData(Boolean isInit) { }
	// RVA: 0x2933e84 VA: 0x7594f4be84
	public Void SetSelectHeritage(Boolean value) { }
	// RVA: 0x2933d24 VA: 0x7594f4bd24
	public Void .ctor() { }
}
```