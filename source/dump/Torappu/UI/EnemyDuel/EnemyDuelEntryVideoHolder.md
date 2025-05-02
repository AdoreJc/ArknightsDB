# EnemyDuelEntryVideoHolder

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `GameObject _panelOnAct`

- `GameObject _panelOnEnd`

- `RectTransform _videoContainer`

- `UIPageFinder m_pageFinder`

- `EnemyDuelEntryVideoView m_videoView`


## Methods

- `Void _LoadViewIfNot(String)`

- `Void Render(EnemyDuelEntryViewModel)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryVideoHolder : MonoBehaviour, IHotfixable
{
	private GameObject _panelOnAct; // 0x18
	private GameObject _panelOnEnd; // 0x20
	private RectTransform _videoContainer; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private EnemyDuelEntryVideoView m_videoView; // 0x40
	private static DelegateBridge __Hotfix0__LoadViewIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x294ce60 VA: 0x7594f64e60
	private Void _LoadViewIfNot(String actId) { }
	// RVA: 0x294d2d8 VA: 0x7594f652d8
	public Void Render(EnemyDuelEntryViewModel viewModel) { }
	// RVA: 0x294d3d8 VA: 0x7594f653d8
	public Void OnDestroy() { }
	// RVA: 0x294d4f8 VA: 0x7594f654f8
	public Void .ctor() { }
}
```