# BuildingMusicPlayerItemView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _trackPoint`

- `GameObject _playingPanel`

- `Text _namePlaying`

- `GameObject _iconLockPlaying`

- `GameObject _iconCurrMusicPlaying`

- `GameObject _defaultPanel`

- `Text _name`

- `GameObject _iconLock`

- `GameObject _iconCurrMusic`

- `String m_bgmId`

- `String m_gameMusicId`

- `Boolean m_hasInited`

- `Boolean m_cachedPlaying`

- `Single m_maxNameWidth`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(BuildingMusicItemViewModel)`

- `Void OnMusicItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMusicPlayerItemView : MonoBehaviour, IHotfixable
{
	private GameObject _trackPoint; // 0x18
	private GameObject _playingPanel; // 0x20
	private Text _namePlaying; // 0x28
	private GameObject _iconLockPlaying; // 0x30
	private GameObject _iconCurrMusicPlaying; // 0x38
	private GameObject _defaultPanel; // 0x40
	private Text _name; // 0x48
	private GameObject _iconLock; // 0x50
	private GameObject _iconCurrMusic; // 0x58
	private String m_bgmId; // 0x60
	private String m_gameMusicId; // 0x68
	private Boolean m_hasInited; // 0x70
	private Boolean m_cachedPlaying; // 0x71
	private Single m_maxNameWidth; // 0x74
	private UIPageFinder m_pageFinder; // 0x78
	private UIStateFinder m_stateFinder; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnMusicItemClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3ded2dc VA: 0x75964052dc
	public Void Render(BuildingMusicItemViewModel viewModel) { }
	// RVA: 0x3ded440 VA: 0x7596405440
	public Void OnMusicItemClicked() { }
	// RVA: 0x3ded59c VA: 0x759640559c
	public Void .ctor() { }
}
```