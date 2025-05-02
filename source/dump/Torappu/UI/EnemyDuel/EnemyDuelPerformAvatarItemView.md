# EnemyDuelPerformAvatarItemView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _avatar`

- `GameObject _panelSelf`

- `GameObject _panelAllinSelf`

- `GameObject _panelAllin`

- `GameObject _panelWinLeft`

- `GameObject _panelWinRight`

- `Text _streakLeft`

- `Text _streakRight`

- `Boolean m_cachedIsNpc`

- `String m_cachedAvatarId`

- `PlayerAvatarType m_cachedAvatarType`

- `UIPageFinder m_pageFinder`

- `ILoadAsset m_assetLoader`


## Methods

- `Void Render(String, EnemyDuelBattleCharItemViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPerformAvatarItemView : MonoBehaviour, IHotfixable
{
	private Image _avatar; // 0x18
	private GameObject _panelSelf; // 0x20
	private GameObject _panelAllinSelf; // 0x28
	private GameObject _panelAllin; // 0x30
	private GameObject _panelWinLeft; // 0x38
	private GameObject _panelWinRight; // 0x40
	private Text _streakLeft; // 0x48
	private Text _streakRight; // 0x50
	private Boolean m_cachedIsNpc; // 0x58
	private String m_cachedAvatarId; // 0x60
	private PlayerAvatarType m_cachedAvatarType; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private ILoadAsset m_assetLoader; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2989d18 VA: 0x7594fa1d18
	public Void Render(String actId, EnemyDuelBattleCharItemViewModel viewModel, Boolean showStreak) { }
	// RVA: 0x298a004 VA: 0x7594fa2004
	public Void .ctor() { }
}
```