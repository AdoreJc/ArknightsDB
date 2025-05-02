# FifthAnnivExploreValueGroupViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Boolean showNum`


## Methods

- `Void _LoadConstData()`

- `Void LoadInitialData(FifthAnnivExploreGroupData, PlayerExploreGameResult)`

- `Void LoadDataAndDeltaWithOld(PlayerExploreGameContextState)`

- `Void SetShowDeltaValue(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreValueGroupViewModel : IHotfixable
{
	public ListDict`2 valueViewModels; // 0x10
	public List`1 valueOrders; // 0x18
	public Boolean showNum; // 0x20
	private static DelegateBridge __Hotfix0__LoadConstData; // 0x0
	private static DelegateBridge __Hotfix0_LoadInitialData; // 0x8
	private static DelegateBridge __Hotfix0_LoadDataAndDeltaWithOld; // 0x10
	private static DelegateBridge __Hotfix0_SetShowDeltaValue; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x291cca0 VA: 0x7594f34ca0
	private Void _LoadConstData() { }
	// RVA: 0x291c8ac VA: 0x7594f348ac
	public Void LoadInitialData(FifthAnnivExploreGroupData groupData, PlayerExploreGameResult heritageData) { }
	// RVA: 0x291cef4 VA: 0x7594f34ef4
	public Void LoadDataAndDeltaWithOld(PlayerExploreGameContextState state) { }
	// RVA: 0x291c5f8 VA: 0x7594f345f8
	public Void SetShowDeltaValue(Boolean showDeltaValue) { }
	// RVA: 0x291c7e8 VA: 0x7594f347e8
	public Void .ctor() { }
}
```