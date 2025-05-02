# Act42D0MapAreaView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `GameObject _btnEffect`

- `Text _textStageName`

- `Text _textStageCode`

- `GameObject _bkgAreaTitleNormal`

- `GameObject _bkgAreaTitleHard`

- `GameObject _bkgAreaInfoPanelHard`

- `GameObject _bkgAreaInfoPanelNormal`

- `Text _textUnlockTips`

- `GameObject _objUnlockTips`

- `SimpleLayoutContent _difficultyContent`

- `GameObject _objRating`

- `Image _imgRating`

- `Act42D0MapStageSelectItemView _stageSelectItemPrefab`

- `GameObject _bkgStartNormal`

- `GameObject _bkgStartHard`

- `UIAtlasImage _bkgBossBtn`

- `Button _btnBoss`

- `UIAtlasObject _atlasObject`

- `UIAnimationLocation _animSelectStage`

- `UIAnimationLocation _animStageDetailEnter`

- `UIAnimationLocation _animBottomMenu`

- `UIAnimationLocation _animStageDetailChange`

- `GameObject _btnStartBattleGo`

- `GameObject _newTrackPointGo`

- `Boolean m_IsInited`

- `UIPageFinder m_pageFinder`

- `Act42D0MapStageItemViewModel m_stageSelectedData`

- `Adapter m_adapter`

- `String m_bossId`

- `String m_areaSelectedId`

- `Int32 m_stageSelectedIndex`

- `AnimationSwitchTween m_selectStageSwitchTween`

- `AnimationSwitchTween m_stageDetailEnterSwitchTween`

- `AnimationSwitchTween m_bottomMenuSwitchTween`

- `AnimationSwitchTween m_stageDetailChangeSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Void _RenderDetail(Act42d0AreaViewModel)`

- `Void _RenderStageSelectedItems(Act42d0AreaViewModel, Boolean)`

- `Void _CheckAnimation(String, Int32)`

- `Void _CheckSelectStageAnimation(String)`

- `Void _CheckStageDetailAnimation(Int32)`

- `Void _CheckBottomMenuAnimation()`

- `Void _NotifyFirstStageSelected()`

- `Void _NotifyAreaSelected()`

- `Void OnClickEnemy()`

- `Void OnClickMap()`

- `Void OnClickBoss()`

- `Void OnClickEffect()`

- `Void OnClickReward()`

- `Void OnClickBattleStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0MapAreaView : DataBinder`1
{
	private GameObject _btnEffect; // 0x20
	private Text _textStageName; // 0x28
	private Text _textStageCode; // 0x30
	private GameObject _bkgAreaTitleNormal; // 0x38
	private GameObject _bkgAreaTitleHard; // 0x40
	private GameObject _bkgAreaInfoPanelHard; // 0x48
	private GameObject _bkgAreaInfoPanelNormal; // 0x50
	private Text _textUnlockTips; // 0x58
	private GameObject _objUnlockTips; // 0x60
	private SimpleLayoutContent _difficultyContent; // 0x68
	private GameObject _objRating; // 0x70
	private Image _imgRating; // 0x78
	private Act42D0MapStageSelectItemView _stageSelectItemPrefab; // 0x80
	private RectTransform[] _rectStageSelectItemContainers; // 0x88
	private GameObject _bkgStartNormal; // 0x90
	private GameObject _bkgStartHard; // 0x98
	private UIAtlasImage _bkgBossBtn; // 0xa0
	private Button _btnBoss; // 0xa8
	private UIAtlasObject _atlasObject; // 0xb0
	private UIAnimationLocation _animSelectStage; // 0xb8
	private UIAnimationLocation _animStageDetailEnter; // 0xc8
	private UIAnimationLocation _animBottomMenu; // 0xd8
	private UIAnimationLocation _animStageDetailChange; // 0xe8
	private GameObject _btnStartBattleGo; // 0xf8
	private GameObject _newTrackPointGo; // 0x100
	private const String ICON_RATING_NAME; // 0x0
	private const Int32 STAGE_COUNT_IN_A_AREA; // 0x0
	private Boolean m_IsInited; // 0x108
	private List`1 m_stageSelectItemList; // 0x110
	private UIPageFinder m_pageFinder; // 0x118
	private Act42D0MapStageItemViewModel m_stageSelectedData; // 0x128
	private Adapter m_adapter; // 0x130
	private String m_bossId; // 0x138
	private String m_areaSelectedId; // 0x140
	private Int32 m_stageSelectedIndex; // 0x148
	private AnimationSwitchTween m_selectStageSwitchTween; // 0x150
	private AnimationSwitchTween m_stageDetailEnterSwitchTween; // 0x158
	private AnimationSwitchTween m_bottomMenuSwitchTween; // 0x160
	private AnimationSwitchTween m_stageDetailChangeSwitchTween; // 0x168
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__RenderDetail; // 0x18
	private static DelegateBridge __Hotfix0__RenderStageSelectedItems; // 0x20
	private static DelegateBridge __Hotfix0__CheckAnimation; // 0x28
	private static DelegateBridge __Hotfix0__CheckSelectStageAnimation; // 0x30
	private static DelegateBridge __Hotfix0__CheckStageDetailAnimation; // 0x38
	private static DelegateBridge __Hotfix0__CheckBottomMenuAnimation; // 0x40
	private static DelegateBridge __Hotfix0__NotifyFirstStageSelected; // 0x48
	private static DelegateBridge __Hotfix0__NotifyAreaSelected; // 0x50
	private static DelegateBridge __Hotfix0_OnClickEnemy; // 0x58
	private static DelegateBridge __Hotfix0_OnClickMap; // 0x60
	private static DelegateBridge __Hotfix0_OnClickBoss; // 0x68
	private static DelegateBridge __Hotfix0_OnClickEffect; // 0x70
	private static DelegateBridge __Hotfix0_OnClickReward; // 0x78
	private static DelegateBridge __Hotfix0_OnClickBattleStart; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x321ae20 VA: 0x7595832e20
	private Void _InitIfNot() { }
	// RVA: 0x321b32c VA: 0x759583332c
	private Void _RegisterTutorialGo() { }
	// RVA: 0x321b5d4 VA: 0x75958335d4
	public override Void OnValueChanged(Act42d0AreaMapProperty property) { }
	// RVA: 0x321b968 VA: 0x7595833968
	private Void _RenderDetail(Act42d0AreaViewModel areaModel) { }
	// RVA: 0x321b7d8 VA: 0x75958337d8
	private Void _RenderStageSelectedItems(Act42d0AreaViewModel areaModel, Boolean areaChanged) { }
	// RVA: 0x321b73c VA: 0x759583373c
	private Void _CheckAnimation(String previousAreaSelectedId, Int32 previousStageSelectedIndex) { }
	// RVA: 0x321c080 VA: 0x7595834080
	private Void _CheckSelectStageAnimation(String previousAreaSelectedId) { }
	// RVA: 0x321c164 VA: 0x7595834164
	private Void _CheckStageDetailAnimation(Int32 previousStageSelectedIndex) { }
	// RVA: 0x321c258 VA: 0x7595834258
	private Void _CheckBottomMenuAnimation() { }
	// RVA: 0x321c2dc VA: 0x75958342dc
	private Void _NotifyFirstStageSelected() { }
	// RVA: 0x321c390 VA: 0x7595834390
	private Void _NotifyAreaSelected() { }
	// RVA: 0x321c444 VA: 0x7595834444
	public Void OnClickEnemy() { }
	// RVA: 0x321c55c VA: 0x759583455c
	public Void OnClickMap() { }
	// RVA: 0x321c664 VA: 0x7595834664
	public Void OnClickBoss() { }
	// RVA: 0x321c76c VA: 0x759583476c
	public Void OnClickEffect() { }
	// RVA: 0x321c820 VA: 0x7595834820
	public Void OnClickReward() { }
	// RVA: 0x321c8d4 VA: 0x75958348d4
	public Void OnClickBattleStart() { }
	// RVA: 0x321c988 VA: 0x7595834988
	public Void .ctor() { }
}
```