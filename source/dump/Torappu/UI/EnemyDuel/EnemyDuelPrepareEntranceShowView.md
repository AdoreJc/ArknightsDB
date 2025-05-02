# EnemyDuelPrepareEntranceShowView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelPrepareEntranceShowPlayerView _playerViewPrefab`

- `Text _maxPlayerCount`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _AdjustViewsCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareEntranceShowView : DataBinder`1, IHotfixable
{
	private EnemyDuelPrepareEntranceShowPlayerView _playerViewPrefab; // 0x20
	private List`1 _playerViewContainers; // 0x28
	private Text _maxPlayerCount; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private List`1 m_playerViews; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__AdjustViewsCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2995ba8 VA: 0x7594fadba8
	public override Void OnValueChanged(EnemyDuelPrepareEntranceShowProperty property) { }
	// RVA: 0x2995de4 VA: 0x7594fadde4
	private Void _AdjustViewsCount(Int32 expectedCount) { }
	// RVA: 0x2996070 VA: 0x7594fae070
	public Void .ctor() { }
}
```