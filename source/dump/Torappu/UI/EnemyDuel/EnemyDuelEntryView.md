# EnemyDuelEntryView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EntryWindow _mainWnd`

- `EntryWindow _musicWnd`

- `Text _titleMainWnd`

- `Text _musicName`

- `EnemyDuelEntryMatchButtonView _matchBtnView`

- `EnemyDuelEntryAnnounceView _announceView`

- `EnemyDuelEntryDailyButtonView _dailyBtnView`

- `EnemyDuelEntryVideoHolder _videoHolder`

- `Text _playerName`

- `Image _playerAvatar`

- `Boolean m_isBasicInited`

- `Int32 m_enterSeq`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNecessary(EnemyDuelEntryViewModel)`

- `Void OnBackClick()`

- `Void OnHomeClick()`

- `Void OnMainBtnClick()`

- `Void OnMainCloseClick()`

- `Void OnMusicBtnClick()`

- `Void OnMusicCloseClick()`

- `Void OnJoinRoomClick()`

- `Void OnRoomClick()`

- `Void OnMatchClick()`

- `Void OnMedalClick()`

- `Void OnRewardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryView : DataBinder`1, IHotfixable
{
	private EntryWindow _mainWnd; // 0x20
	private EntryWindow _musicWnd; // 0x28
	private Text _titleMainWnd; // 0x30
	private Text _musicName; // 0x38
	private EnemyDuelEntryActButtonView[] _actBtns; // 0x40
	private EnemyDuelEntryMatchButtonView _matchBtnView; // 0x48
	private EnemyDuelEntryAnnounceView _announceView; // 0x50
	private EnemyDuelEntryDailyButtonView _dailyBtnView; // 0x58
	private EnemyDuelEntryVideoHolder _videoHolder; // 0x60
	private Text _playerName; // 0x68
	private Image _playerAvatar; // 0x70
	private Boolean m_isBasicInited; // 0x78
	private Int32 m_enterSeq; // 0x7c
	private UIStateFinder m_stateFinder; // 0x80
	private UIPageFinder m_pageFinder; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNecessary; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x10
	private static DelegateBridge __Hotfix0_OnHomeClick; // 0x18
	private static DelegateBridge __Hotfix0_OnMainBtnClick; // 0x20
	private static DelegateBridge __Hotfix0_OnMainCloseClick; // 0x28
	private static DelegateBridge __Hotfix0_OnMusicBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_OnMusicCloseClick; // 0x38
	private static DelegateBridge __Hotfix0_OnJoinRoomClick; // 0x40
	private static DelegateBridge __Hotfix0_OnRoomClick; // 0x48
	private static DelegateBridge __Hotfix0_OnMatchClick; // 0x50
	private static DelegateBridge __Hotfix0_OnMedalClick; // 0x58
	private static DelegateBridge __Hotfix0_OnRewardClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x294d678 VA: 0x7594f65678
	private Void _InitIfNecessary(EnemyDuelEntryViewModel viewModel) { }
	// RVA: 0x294d7ec VA: 0x7594f657ec
	public override Void OnValueChanged(EnemyDuelEntryProperty property) { }
	// RVA: 0x294dbd0 VA: 0x7594f65bd0
	public Void OnBackClick() { }
	// RVA: 0x294dc84 VA: 0x7594f65c84
	public Void OnHomeClick() { }
	// RVA: 0x294dd38 VA: 0x7594f65d38
	public Void OnMainBtnClick() { }
	// RVA: 0x294de7c VA: 0x7594f65e7c
	public Void OnMainCloseClick() { }
	// RVA: 0x294df44 VA: 0x7594f65f44
	public Void OnMusicBtnClick() { }
	// RVA: 0x294e00c VA: 0x7594f6600c
	public Void OnMusicCloseClick() { }
	// RVA: 0x294e0d4 VA: 0x7594f660d4
	public Void OnJoinRoomClick() { }
	// RVA: 0x294e19c VA: 0x7594f6619c
	public Void OnRoomClick() { }
	// RVA: 0x294e264 VA: 0x7594f66264
	public Void OnMatchClick() { }
	// RVA: 0x294e32c VA: 0x7594f6632c
	public Void OnMedalClick() { }
	// RVA: 0x294e3f4 VA: 0x7594f663f4
	public Void OnRewardClick() { }
	// RVA: 0x294e4bc VA: 0x7594f664bc
	public Void .ctor() { }
}
```