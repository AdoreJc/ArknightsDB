# EnemyDuelRoundEndPlayerInfoView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _avatar`

- `TwoStateToggle _toggle`

- `Text _nameWin`

- `Text _nickIdWin`

- `Text _nameLose`

- `Text _nickIdLose`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(Boolean, PlayerInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndPlayerInfoView : MonoBehaviour, IHotfixable
{
	private const String NICK_ID_FORMAT; // 0x0
	private Image _avatar; // 0x18
	private TwoStateToggle _toggle; // 0x20
	private Text _nameWin; // 0x28
	private Text _nickIdWin; // 0x30
	private Text _nameLose; // 0x38
	private Text _nickIdLose; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x298f4d0 VA: 0x7594fa74d0
	public Void Render(Boolean isWin, PlayerInfo playerInfo) { }
	// RVA: 0x298f684 VA: 0x7594fa7684
	public Void .ctor() { }
}
```