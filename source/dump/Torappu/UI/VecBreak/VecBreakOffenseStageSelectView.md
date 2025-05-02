# VecBreakOffenseStageSelectView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `GameObject _stageInfoNormalPart`

- `Text _textCurrLv`

- `Text _textTotalLv`

- `Text _textStageCodeName`

- `Text _textStoryDesc`

- `GameObject _enemyInfoPanel`

- `GameObject _bossDetailNormalPart`

- `GameObject _emptyBossDecoGo`

- `LayoutElement _bossDescScrollElement`

- `Single _bossDescScrollMaxHeight`

- `Single _bossDescScrollMinHeight`

- `Single _bossDescTweenDuration`

- `GameObject _bossDetailEmtpyPart`

- `Text _textBossDescTitle`

- `Text _textBossDesc`

- `Text _textDiffDesc`

- `Text _textBossName`

- `GameObject _bossBtnBgNormalGo`

- `GameObject _bossBtnBgHardGo`

- `GameObject _bossBtnMaskNormalGo`

- `GameObject _bossBtnMaskHardGo`

- `UIAtlasImage _imgBossNameDeco`

- `Image _imgBossIcon`

- `Color _colorBossNameDecoNormal`

- `Color _colorBossNameDecoHard`

- `SimpleLayoutContent _navList`

- `RectTransform _navCursorTrans`

- `RectTransform _navLockRegionTrans`

- `Text _textLockRegionHint`

- `HorizontalLayoutGroup _navListLayoutGroup`

- `Single _cursorTweenDuration`

- `Single _navItemWidth`

- `GameObject _btnNavPrevNormalGo`

- `GameObject _btnNavPrevDisableGo`

- `GameObject _btnNavNextAvailGo`

- `GameObject _btnNavNextEmptyGo`

- `GameObject _btnNavNextLockGo`

- `GameObject _btnBattleNormalGo`

- `GameObject _btnBattleDisableGo`

- `GameObject _commonRewardGo`

- `GameObject _firstRewardGo`

- `Text _textFirstRewardCount`

- `Text _textCommonRewardCount`

- `Image _imgItemIcon`

- `CanvasGroup _diffNormalParticle`

- `CanvasGroup _diffHardParticle`

- `Single _particleShowDuration`

- `GameObject _btnNavDefenseNormalGo`

- `GameObject _btnNavDefenseDisableGo`

- `Text _textDefenseUnlockHint`

- `SimpleLayoutContent _defenseBuffList`

- `GameObject _newTrackPointGo`

- `UIAnimationLocation _animEnter`

- `Boolean m_hasInited`

- `VecBreakOffenseModel m_offenseModel`

- `NavListAdapter m_navListAdapter`

- `DefenseBuffListAdapter m_defenseBuffListAdapter`

- `Tween m_navCursorTween`

- `Int32 m_cacheNavIdx`

- `UIPageFinder m_pageFinder`

- `Int32 m_cacheEnterSeqNum`

- `Tween m_enterAnimTween`

- `Tween m_bossDescTween`

- `FadeSwitchTween m_diffNormalTween`

- `FadeSwitchTween m_diffHardTween`


## Methods

- `Void _PlayEnterAnimIfNeed(VecBreakOffenseModel)`

- `Void _RenderDefenseNavi(VecBreakOffenseModel)`

- `Void _PlayNavCursorTweenIfNeed()`

- `Single _GetCursorTargetPos(Int32)`

- `Void _RenderStageInfo(VecBreakOffenseModel, VecBreakOffenseStageModel)`

- `Void _RenderEnemyInfo(VecBreakOffenseModel, VecBreakOffenseStageModel)`

- `Void _RenderBossInfo(VecBreakOffenseModel, VecBreakOffenseStageModel)`

- `Void _RenderNavBar()`

- `Void _RenderBtnStartBattle(VecBreakOffenseModel, VecBreakOffenseStageModel)`

- `Void _InitIfNot()`

- `Single <_RenderEnemyInfo>b__73_0()`

- `Void <_RenderEnemyInfo>b__73_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseStageSelectView : DataBinder`1
{
	private GameObject _stageInfoNormalPart; // 0x20
	private Text _textCurrLv; // 0x28
	private Text _textTotalLv; // 0x30
	private Text _textStageCodeName; // 0x38
	private Text _textStoryDesc; // 0x40
	private GameObject _enemyInfoPanel; // 0x48
	private GameObject _bossDetailNormalPart; // 0x50
	private GameObject _emptyBossDecoGo; // 0x58
	private GameObject[] _bossDescGoList; // 0x60
	private LayoutElement _bossDescScrollElement; // 0x68
	private Single _bossDescScrollMaxHeight; // 0x70
	private Single _bossDescScrollMinHeight; // 0x74
	private Single _bossDescTweenDuration; // 0x78
	private GameObject _bossDetailEmtpyPart; // 0x80
	private Text _textBossDescTitle; // 0x88
	private Text _textBossDesc; // 0x90
	private Text _textDiffDesc; // 0x98
	private Text _textBossName; // 0xa0
	private GameObject[] _iconBossDiffList; // 0xa8
	private GameObject _bossBtnBgNormalGo; // 0xb0
	private GameObject _bossBtnBgHardGo; // 0xb8
	private GameObject _bossBtnMaskNormalGo; // 0xc0
	private GameObject _bossBtnMaskHardGo; // 0xc8
	private UIAtlasImage _imgBossNameDeco; // 0xd0
	private Image _imgBossIcon; // 0xd8
	private Color _colorBossNameDecoNormal; // 0xe0
	private Color _colorBossNameDecoHard; // 0xf0
	private SimpleLayoutContent _navList; // 0x100
	private RectTransform _navCursorTrans; // 0x108
	private RectTransform _navLockRegionTrans; // 0x110
	private Text _textLockRegionHint; // 0x118
	private HorizontalLayoutGroup _navListLayoutGroup; // 0x120
	private Single _cursorTweenDuration; // 0x128
	private Single _navItemWidth; // 0x12c
	private GameObject _btnNavPrevNormalGo; // 0x130
	private GameObject _btnNavPrevDisableGo; // 0x138
	private GameObject _btnNavNextAvailGo; // 0x140
	private GameObject _btnNavNextEmptyGo; // 0x148
	private GameObject _btnNavNextLockGo; // 0x150
	private GameObject _btnBattleNormalGo; // 0x158
	private GameObject _btnBattleDisableGo; // 0x160
	private GameObject _commonRewardGo; // 0x168
	private GameObject _firstRewardGo; // 0x170
	private Text _textFirstRewardCount; // 0x178
	private Text _textCommonRewardCount; // 0x180
	private Image _imgItemIcon; // 0x188
	private CanvasGroup _diffNormalParticle; // 0x190
	private CanvasGroup _diffHardParticle; // 0x198
	private Single _particleShowDuration; // 0x1a0
	private GameObject _btnNavDefenseNormalGo; // 0x1a8
	private GameObject _btnNavDefenseDisableGo; // 0x1b0
	private Text _textDefenseUnlockHint; // 0x1b8
	private SimpleLayoutContent _defenseBuffList; // 0x1c0
	private GameObject _newTrackPointGo; // 0x1c8
	private UIAnimationLocation _animEnter; // 0x1d0
	private Boolean m_hasInited; // 0x1e0
	private VecBreakOffenseModel m_offenseModel; // 0x1e8
	private NavListAdapter m_navListAdapter; // 0x1f0
	private DefenseBuffListAdapter m_defenseBuffListAdapter; // 0x1f8
	private Tween m_navCursorTween; // 0x200
	private Int32 m_cacheNavIdx; // 0x208
	private UIPageFinder m_pageFinder; // 0x210
	private Int32 m_cacheEnterSeqNum; // 0x220
	private Tween m_enterAnimTween; // 0x228
	private Tween m_bossDescTween; // 0x230
	private FadeSwitchTween m_diffNormalTween; // 0x238
	private FadeSwitchTween m_diffHardTween; // 0x240
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayEnterAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__RenderDefenseNavi; // 0x10
	private static DelegateBridge __Hotfix0__PlayNavCursorTweenIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__GetCursorTargetPos; // 0x20
	private static DelegateBridge __Hotfix0__RenderStageInfo; // 0x28
	private static DelegateBridge __Hotfix0__RenderEnemyInfo; // 0x30
	private static DelegateBridge __Hotfix0__RenderBossInfo; // 0x38
	private static DelegateBridge __Hotfix0__RenderNavBar; // 0x40
	private static DelegateBridge __Hotfix0__RenderBtnStartBattle; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x22d4df4 VA: 0x75948ecdf4
	public override Void OnValueChanged(VecBreakOffenseProp property) { }
	// RVA: 0x22d5d44 VA: 0x75948edd44
	private Void _PlayEnterAnimIfNeed(VecBreakOffenseModel offenseModel) { }
	// RVA: 0x22d5c30 VA: 0x75948edc30
	private Void _RenderDefenseNavi(VecBreakOffenseModel offenseModel) { }
	// RVA: 0x22d5e90 VA: 0x75948ede90
	private Void _PlayNavCursorTweenIfNeed() { }
	// RVA: 0x22d5f7c VA: 0x75948edf7c
	private Single _GetCursorTargetPos(Int32 navIdx) { }
	// RVA: 0x22d5140 VA: 0x75948ed140
	private Void _RenderStageInfo(VecBreakOffenseModel offenseModel, VecBreakOffenseStageModel currStageModel) { }
	// RVA: 0x22d537c VA: 0x75948ed37c
	private Void _RenderEnemyInfo(VecBreakOffenseModel offenseModel, VecBreakOffenseStageModel currStageModel) { }
	// RVA: 0x22d6040 VA: 0x75948ee040
	private Void _RenderBossInfo(VecBreakOffenseModel offenseModel, VecBreakOffenseStageModel currStageModel) { }
	// RVA: 0x22d56d0 VA: 0x75948ed6d0
	private Void _RenderNavBar() { }
	// RVA: 0x22d594c VA: 0x75948ed94c
	private Void _RenderBtnStartBattle(VecBreakOffenseModel offenseModel, VecBreakOffenseStageModel currStageModel) { }
	// RVA: 0x22d4f0c VA: 0x75948ecf0c
	private Void _InitIfNot() { }
	// RVA: 0x22d6468 VA: 0x75948ee468
	public Void .ctor() { }
	// RVA: 0x22d6510 VA: 0x75948ee510
	private Single <_RenderEnemyInfo>b__73_0() { }
	// RVA: 0x22d6534 VA: 0x75948ee534
	private Void <_RenderEnemyInfo>b__73_1(Single val) { }
}
```