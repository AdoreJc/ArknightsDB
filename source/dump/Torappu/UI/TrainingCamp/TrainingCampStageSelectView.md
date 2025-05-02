# TrainingCampStageSelectView

**Namespace:** `Torappu.UI.TrainingCamp`


## Fields

- `TrainingCampStageListAdapter _adapter`

- `Image _stageIconImg`

- `Image _stageBigIconImg`

- `Text _stageDescText`

- `Text _stageNameText`

- `UIDynImage _stageMapPreviewImg`

- `Text _stageProgressText`

- `Transform _rewardContainer`

- `Single _rewardScale`

- `GameObject _mapTipsObj`

- `Image _mapTipsBlur`

- `UIDynImage _mapTipsImg`

- `CanvasGroup _rewardCanvasGroup`

- `Single _gainedRewardAlpha`

- `GameObject _gainedRewardObj`

- `UILayoutDimensionListener _layoutListener`

- `RectTransform _listViewRect`

- `GridLayoutGroup _listGridLayout`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _selectAnim`

- `Boolean m_isInited`

- `TrainingCampStageSelectViewModel m_cachedViewModel`

- `TrainingCampStageListItemViewModel m_cachedStageViewModel`

- `UIItemCard m_rewardItemCard`

- `UIItemViewModel m_rewardItemModel`

- `UIPageFinder m_pageFinder`

- `ILoadAsset m_assetLoader`

- `Int32 m_cachedFocusSeqNum`

- `AnimationSwitchTween m_enterTween`

- `AnimationSwitchTween m_selectTween`

- `Int32 m_cachedSelectIdx`


## Methods

- `Void _InitIfNot()`

- `Void OpenMapTips()`

- `Void CloseMapTips()`

- `Void _FoucsIfNeeded()`

- `Void _RenderReward(Boolean)`

- `Void _ClearBlurSprite()`

- `Void _ShotBlurredSprite()`

- `Void <_RenderReward>b__36_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TrainingCamp
public class TrainingCampStageSelectView : DataBinder`1
{
	private TrainingCampStageListAdapter _adapter; // 0x20
	private Image _stageIconImg; // 0x28
	private Image _stageBigIconImg; // 0x30
	private Text _stageDescText; // 0x38
	private Text _stageNameText; // 0x40
	private UIDynImage _stageMapPreviewImg; // 0x48
	private Text _stageProgressText; // 0x50
	private Transform _rewardContainer; // 0x58
	private Single _rewardScale; // 0x60
	private GameObject _mapTipsObj; // 0x68
	private Image _mapTipsBlur; // 0x70
	private UIDynImage _mapTipsImg; // 0x78
	private CanvasGroup _rewardCanvasGroup; // 0x80
	private Single _gainedRewardAlpha; // 0x88
	private GameObject _gainedRewardObj; // 0x90
	private UILayoutDimensionListener _layoutListener; // 0x98
	private RectTransform _listViewRect; // 0xa0
	private GridLayoutGroup _listGridLayout; // 0xa8
	private UIAnimationLocation _enterAnim; // 0xb0
	private UIAnimationLocation _selectAnim; // 0xc0
	private Boolean m_isInited; // 0xd0
	private TrainingCampStageSelectViewModel m_cachedViewModel; // 0xd8
	private TrainingCampStageListItemViewModel m_cachedStageViewModel; // 0xe0
	private UIItemCard m_rewardItemCard; // 0xe8
	private UIItemViewModel m_rewardItemModel; // 0xf0
	private UIPageFinder m_pageFinder; // 0xf8
	private ILoadAsset m_assetLoader; // 0x108
	private Int32 m_cachedFocusSeqNum; // 0x110
	private AnimationSwitchTween m_enterTween; // 0x118
	private AnimationSwitchTween m_selectTween; // 0x120
	private Int32 m_cachedSelectIdx; // 0x128
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OpenMapTips; // 0x10
	private static DelegateBridge __Hotfix0_CloseMapTips; // 0x18
	private static DelegateBridge __Hotfix0__FoucsIfNeeded; // 0x20
	private static DelegateBridge __Hotfix0__RenderReward; // 0x28
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0x30
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x234c058 VA: 0x7594964058
	private Void _InitIfNot() { }
	// RVA: 0x234c258 VA: 0x7594964258
	public override Void OnValueChanged(TrainingCampStageSelectProperty property) { }
	// RVA: 0x234ca60 VA: 0x7594964a60
	public Void OpenMapTips() { }
	// RVA: 0x234cbb0 VA: 0x7594964bb0
	public Void CloseMapTips() { }
	// RVA: 0x234cd2c VA: 0x7594964d2c
	private Void _FoucsIfNeeded() { }
	// RVA: 0x234c740 VA: 0x7594964740
	private Void _RenderReward(Boolean isGained) { }
	// RVA: 0x234cc28 VA: 0x7594964c28
	private Void _ClearBlurSprite() { }
	// RVA: 0x234cb3c VA: 0x7594964b3c
	private Void _ShotBlurredSprite() { }
	// RVA: 0x234cebc VA: 0x7594964ebc
	public Void .ctor() { }
	// RVA: 0x234cf54 VA: 0x7594964f54
	private Void <_RenderReward>b__36_0(Int32 _) { }
}
```