# ActMultiV3PrepareMainStageChooseView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `Text _roomIdText`

- `Text _mapCodeText`

- `Text _mapModeText`

- `ActMultiV3DifficultyIconView _mapDiffIconViewPrefab`

- `Transform _mapDiffIconViewContainer`

- `ActMultiV3InverseToggleView _inverseToggleViewPrefab`

- `Transform _inverseToggleViewContainer`

- `Single _mapDiffScale`

- `RectTransform _emptyMapRoot`

- `TwoStateToggle _randomMapToggle`

- `TwoStateToggle _ownerGusetToggle`

- `TwoStateToggle _guestBtnAvailToggle`

- `TwoStateToggle _guestPreparedCancelBtnToggle`

- `TwoStateToggle _ownerPreparBtnAvailToggle`

- `Text _ownerWatingStatusTxt`

- `Text _guestWatingStatusTxt`

- `Image _stageBigPreviewImg`

- `UIAnimationLocation _ownerInAnim`

- `UIAnimationLocation _guestInAnim`

- `UIAnimationLocation _guestMapDetailInAnim`

- `UIAnimationLocation _topMenuNormToFlipAnim`

- `UIAnimationLocation _topMeunFlipToNormAnim`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `Boolean m_isInited`

- `String m_cachedActId`

- `String m_cacheStagePicId`

- `ActMultiV3DifficultyIconView m_mapDiffIconView`

- `ActMultiV3InverseToggleView m_inverseToggleView`

- `AnimationSwitchTween m_guestMapDetailSwitchTween`

- `GameObject m_prepareLoopAnimObj`

- `Int32 m_cacheEnterSeqNum`

- `Int32 m_cacheModeChangeSeqNum`

- `Int32 m_cachePartnerInSeqNum`

- `Int32 m_cacheMapChangeSeqNum`

- `Action <onModeToggleClick>k__BackingField`


## Properties

- `Action onModeToggleClick`


## Methods

- `Void set_onModeToggleClick(Action)`

- `Action get_onModeToggleClick()`

- `Void _InitIfNot()`

- `Void _PlayEnterAnim(ActMultiV3PrepareMainStageChooseViewModel)`

- `Void _SetGameObjectsActive(GameObject[], Boolean)`

- `Tween <_InitIfNot>b__46_0()`

- `Tween <_InitIfNot>b__46_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainStageChooseView : DataBinder`1
{
	private Text _roomIdText; // 0x20
	private Text _mapCodeText; // 0x28
	private Text _mapModeText; // 0x30
	private ActMultiV3DifficultyIconView _mapDiffIconViewPrefab; // 0x38
	private Transform _mapDiffIconViewContainer; // 0x40
	private ActMultiV3InverseToggleView _inverseToggleViewPrefab; // 0x48
	private Transform _inverseToggleViewContainer; // 0x50
	private Single _mapDiffScale; // 0x58
	private GameObject[] _emptyMapObjs; // 0x60
	private RectTransform _emptyMapRoot; // 0x68
	private GameObject[] _selectedMapObjs; // 0x70
	private GameObject[] _ownerObjs; // 0x78
	private GameObject[] _guestObjs; // 0x80
	private TwoStateToggle _randomMapToggle; // 0x88
	private TwoStateToggle _ownerGusetToggle; // 0x90
	private TwoStateToggle _guestBtnAvailToggle; // 0x98
	private TwoStateToggle _guestPreparedCancelBtnToggle; // 0xa0
	private TwoStateToggle _ownerPreparBtnAvailToggle; // 0xa8
	private Text _ownerWatingStatusTxt; // 0xb0
	private Text _guestWatingStatusTxt; // 0xb8
	private Image _stageBigPreviewImg; // 0xc0
	private UIAnimationLocation _ownerInAnim; // 0xc8
	private UIAnimationLocation _guestInAnim; // 0xd8
	private UIAnimationLocation _guestMapDetailInAnim; // 0xe8
	private UIAnimationLocation _topMenuNormToFlipAnim; // 0xf8
	private UIAnimationLocation _topMeunFlipToNormAnim; // 0x108
	private UIPageFinder m_pageFinder; // 0x118
	private UIStateFinder m_stateFinder; // 0x128
	private Boolean m_isInited; // 0x138
	private String m_cachedActId; // 0x140
	private String m_cacheStagePicId; // 0x148
	private ActMultiV3DifficultyIconView m_mapDiffIconView; // 0x150
	private ActMultiV3InverseToggleView m_inverseToggleView; // 0x158
	private AnimationSwitchTween m_guestMapDetailSwitchTween; // 0x160
	private UIStateTransitionTween`1 m_topMenuTransTween; // 0x168
	private GameObject m_prepareLoopAnimObj; // 0x170
	private Int32 m_cacheEnterSeqNum; // 0x178
	private Int32 m_cacheModeChangeSeqNum; // 0x17c
	private Int32 m_cachePartnerInSeqNum; // 0x180
	private Int32 m_cacheMapChangeSeqNum; // 0x184
	private Action <onModeToggleClick>k__BackingField; // 0x188
	private static DelegateBridge __Hotfix0_set_onModeToggleClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onModeToggleClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x20
	private static DelegateBridge __Hotfix0__SetGameObjectsActive; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action onModeToggleClick { get; set; }

	// RVA: 0x3177154 VA: 0x759578f154
	public Void set_onModeToggleClick(Action value) { }
	// RVA: 0x3178634 VA: 0x7595790634
	private Action get_onModeToggleClick() { }
	// RVA: 0x317869c VA: 0x759579069c
	public override Void OnValueChanged(ActMultiV3PrepareMainStageChooseProperty property) { }
	// RVA: 0x3178d54 VA: 0x7595790d54
	private Void _InitIfNot() { }
	// RVA: 0x3179408 VA: 0x7595791408
	private Void _PlayEnterAnim(ActMultiV3PrepareMainStageChooseViewModel viewModel) { }
	// RVA: 0x31792b8 VA: 0x75957912b8
	private Void _SetGameObjectsActive(GameObject[] gameObjs, Boolean value) { }
	// RVA: 0x3179924 VA: 0x7595791924
	public Void .ctor() { }
	// RVA: 0x31799b4 VA: 0x75957919b4
	private Tween <_InitIfNot>b__46_0() { }
	// RVA: 0x31799f0 VA: 0x75957919f0
	private Tween <_InitIfNot>b__46_1() { }
}
```