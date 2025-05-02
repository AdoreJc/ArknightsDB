# FifthAnnivExploreViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `GameState gameState`

- `FifthAnnivExploreMapViewModel mapViewModel`

- `FifthAnnivExploreTopMenuViewModel topMenuViewModel`

- `FifthAnnivExploreSideInfoViewModel sideInfoViewModel`


## Methods

- `Void LoadData(Param, Boolean, Boolean)`

- `Void LoadGameState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreViewModel : IHotfixable
{
	public GameState gameState; // 0x10
	public FifthAnnivExploreMapViewModel mapViewModel; // 0x18
	public FifthAnnivExploreTopMenuViewModel topMenuViewModel; // 0x20
	public FifthAnnivExploreSideInfoViewModel sideInfoViewModel; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadGameState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x292a404 VA: 0x7594f42404
	public Void LoadData(Param param, Boolean isInit, Boolean isNewGame) { }
	// RVA: 0x292a920 VA: 0x7594f42920
	public Void LoadGameState() { }
	// RVA: 0x292a9f8 VA: 0x7594f429f8
	public Void .ctor() { }
}
```