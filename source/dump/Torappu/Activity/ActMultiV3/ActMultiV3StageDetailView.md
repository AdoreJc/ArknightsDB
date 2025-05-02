# ActMultiV3StageDetailView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _stageCodeTxt`

- `Text _modeNameCodeTxt`

- `ActMultiV3DifficultyIconView _diffIconViewPrefab`

- `Transform _diffIconViewContainer`

- `Single _diffScale`

- `Text _stageDetailTxt`

- `ActMultiV3StageDetailViewGoalItem _goalItemPrefab`

- `RectTransform _goalItemContainer`

- `Image _titleModeIconImg`

- `Image _seasonIcon`

- `Image _stageBigPreviewImg`

- `GameObject _pnlSeasonIcon`

- `UIAnimationLocation _inAnim`

- `UIAnimationLocation _outAnim`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `ActMultiV3DifficultyIconView m_diffIconView`

- `ActMultiV3StageDetailViewModel m_viewModel`

- `String m_actId`

- `Sprite m_cacheGoalItemIconSprite`


## Methods

- `Void Render(ActMultiV3StageDetailViewModel, Boolean)`

- `Void _InitIfNot()`

- `Void _AdjustViewCount(Int32)`

- `Tween BuildInAnimTween(Boolean)`

- `Tween BuildOutAnimTween(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageDetailView : MonoBehaviour, IHotfixable
{
	private ModeConfig[] _modeConfigs; // 0x18
	private Text _stageCodeTxt; // 0x20
	private Text _modeNameCodeTxt; // 0x28
	private ActMultiV3DifficultyIconView _diffIconViewPrefab; // 0x30
	private Transform _diffIconViewContainer; // 0x38
	private Single _diffScale; // 0x40
	private Text _stageDetailTxt; // 0x48
	private ActMultiV3StageDetailViewGoalItem _goalItemPrefab; // 0x50
	private RectTransform _goalItemContainer; // 0x58
	private Text[] _recordScoreTexts; // 0x60
	private SimpleLayoutContent[] _recordStarContents; // 0x68
	private Image _titleModeIconImg; // 0x70
	private Image _seasonIcon; // 0x78
	private Image _stageBigPreviewImg; // 0x80
	private GameObject _pnlSeasonIcon; // 0x88
	private UIAnimationLocation _inAnim; // 0x90
	private UIAnimationLocation _outAnim; // 0xa0
	private UIPageFinder m_pageFinder; // 0xb0
	private Boolean m_isInited; // 0xc0
	private ActMultiV3DifficultyIconView m_diffIconView; // 0xc8
	private ActMultiV3StageDetailViewModel m_viewModel; // 0xd0
	private List`1 m_starAdapters; // 0xd8
	private String m_actId; // 0xe0
	private List`1 m_goalItems; // 0xe8
	private Sprite m_cacheGoalItemIconSprite; // 0xf0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__AdjustViewCount; // 0x10
	private static DelegateBridge __Hotfix0_BuildInAnimTween; // 0x18
	private static DelegateBridge __Hotfix0_BuildOutAnimTween; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3145ccc VA: 0x759575dccc
	public Void Render(ActMultiV3StageDetailViewModel viewModel, Boolean isStageDetailState) { }
	// RVA: 0x314622c VA: 0x759575e22c
	private Void _InitIfNot() { }
	// RVA: 0x314696c VA: 0x759575e96c
	private Void _AdjustViewCount(Int32 viewCnt) { }
	// RVA: 0x3146d60 VA: 0x759575ed60
	public Tween BuildInAnimTween(Boolean isInverse) { }
	// RVA: 0x3146e50 VA: 0x759575ee50
	public Tween BuildOutAnimTween(Boolean isInverse) { }
	// RVA: 0x3146f40 VA: 0x759575ef40
	public Void .ctor() { }
}
```