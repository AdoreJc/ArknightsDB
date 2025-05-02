# Act1VAutoChessEntryTeamInfoSubBackView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _charGroup`

- `GameObject _charBottomGroup`

- `Text _charTeamName`

- `Text _charTeamLeaderName`

- `Text _charTeamEffectDesc`

- `Text _teamHp`

- `GameObject _lockMask`

- `GameObject _lockIntroGroup`

- `GameObject _unlockedIntroGroup`

- `Text _unlockReqDesc`

- `Image _charTeamLogo`

- `Image _charTeamLeaderIcon`

- `GameObject _enemyGroup`

- `GameObject _enemyBottomGroup`

- `Text _enemyTeamName`

- `Text _enemyIntroDesc`

- `Text _enemyTeamLeaderName`

- `Image _enemyTeamLogo`

- `Image _enemyTeamLeaderIcon`

- `UIAnimationLocation _animSwitchToChar`

- `UIAnimationLocation _animsSwitchToEnemy`

- `Act1AutoChessEntryTeamInfoEnterExitAnim _enterExitAnim`

- `AnimationWrapper _lockTeamMaskAnimWrapper`

- `UIBiAnimClipSwitchTween m_backGroupSwitchTween`

- `Act1VAutoChessEntryTeamInfoViewModel m_cachedTeamInfoViewModel`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInit`

- `UIPageFinder m_finder`


## Methods

- `Void TutorialOnlyRegisterTutorialGo()`

- `Void OnClickEnemyHandBookInfo()`

- `Void _InitIfNot()`

- `Void _PlayBackGroupSwitchAnim(Boolean)`

- `Void _TryPlayLockMaskAnim(Boolean, Boolean)`

- `Void _SetGroupActive(Boolean)`

- `Void _SetAllGroupActive()`

- `Void _SetEntryAnim(Boolean)`

- `Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryTeamInfoSubBackView : Act1VAutoChessBaseSubView
{
	private GameObject _charGroup; // 0x18
	private GameObject _charBottomGroup; // 0x20
	private Text _charTeamName; // 0x28
	private Text _charTeamLeaderName; // 0x30
	private Text _charTeamEffectDesc; // 0x38
	private Text _teamHp; // 0x40
	private GameObject _lockMask; // 0x48
	private GameObject _lockIntroGroup; // 0x50
	private GameObject _unlockedIntroGroup; // 0x58
	private Text _unlockReqDesc; // 0x60
	private Image _charTeamLogo; // 0x68
	private Image _charTeamLeaderIcon; // 0x70
	private GameObject _enemyGroup; // 0x78
	private GameObject _enemyBottomGroup; // 0x80
	private Text _enemyTeamName; // 0x88
	private Text _enemyIntroDesc; // 0x90
	private Text _enemyTeamLeaderName; // 0x98
	private Image _enemyTeamLogo; // 0xa0
	private Image _enemyTeamLeaderIcon; // 0xa8
	private UIAnimationLocation _animSwitchToChar; // 0xb0
	private UIAnimationLocation _animsSwitchToEnemy; // 0xc0
	private Act1AutoChessEntryTeamInfoEnterExitAnim _enterExitAnim; // 0xd0
	private AnimationWrapper _lockTeamMaskAnimWrapper; // 0xd8
	private UIBiAnimClipSwitchTween m_backGroupSwitchTween; // 0xe0
	private Act1VAutoChessEntryTeamInfoViewModel m_cachedTeamInfoViewModel; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf0
	private Boolean m_isInit; // 0x100
	private UIPageFinder m_finder; // 0x108
	private const String HP_QUESTION_MARK; // 0x0
	private const String ENEMY_IN_ANIM_NAME; // 0x0
	private const String CHAR_IN_ANIM_NAME; // 0x0
	private const String CHAR_TEAM_LOCK_MASK_ANIM_NAME; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnlyRegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0_OnClickEnemyHandBookInfo; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayBackGroupSwitchAnim; // 0x20
	private static DelegateBridge __Hotfix0__TryPlayLockMaskAnim; // 0x28
	private static DelegateBridge __Hotfix0__SetGroupActive; // 0x30
	private static DelegateBridge __Hotfix0__SetAllGroupActive; // 0x38
	private static DelegateBridge __Hotfix0__SetEntryAnim; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x334d11c VA: 0x759596511c
	public override Void Render(Act1VAutoChessEntryBaseSubViewModel subViewModel) { }
	// RVA: 0x334da54 VA: 0x7595965a54
	public Void TutorialOnlyRegisterTutorialGo() { }
	// RVA: 0x334dab8 VA: 0x7595965ab8
	public Void OnClickEnemyHandBookInfo() { }
	// RVA: 0x334d51c VA: 0x759596551c
	private Void _InitIfNot() { }
	// RVA: 0x334d620 VA: 0x7595965620
	private Void _PlayBackGroupSwitchAnim(Boolean isToEnemy) { }
	// RVA: 0x334d7f0 VA: 0x75959657f0
	private Void _TryPlayLockMaskAnim(Boolean isLock, Boolean shouldPlay) { }
	// RVA: 0x334dc24 VA: 0x7595965c24
	private Void _SetGroupActive(Boolean isEnemyTeam) { }
	// RVA: 0x334db84 VA: 0x7595965b84
	private Void _SetAllGroupActive() { }
	// RVA: 0x334d910 VA: 0x7595965910
	private Void _SetEntryAnim(Boolean isEnemy) { }
	// RVA: 0x334dce4 VA: 0x7595965ce4
	public Void .ctor() { }
	// RVA: 0x334dd54 VA: 0x7595965d54
	private Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel P0) { }
}
```