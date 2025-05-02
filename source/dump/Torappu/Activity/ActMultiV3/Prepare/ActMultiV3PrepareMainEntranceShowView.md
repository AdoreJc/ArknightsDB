# ActMultiV3PrepareMainEntranceShowView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `GameObject _entranceShowRoot`

- `Image _selfEffectIcon`

- `Image _partnerEffectIcon`

- `Image _seasonIconImg2`

- `Text _selfEffectNameTxt`

- `Text _partnerEffectNameTxt`

- `TwoStateToggle _partnerReadyToggle`

- `TwoStateToggle _confirmBtnToggle`

- `ActMultiV3ShortNameCardView _nameCardPrefab`

- `ActMultiV3StageDetailView _stageDetailPrefab`

- `RectTransform _selfNameCardContainer`

- `RectTransform _partnerNameCardContainer`

- `RectTransform _selfAssitIllustContainer`

- `RectTransform _partnerAssitIllustContainer`

- `RectTransform _stageDetailContainer`

- `RectTransform _bottomBarContainer`

- `UIAnimationLocation _normEnterAnim`

- `UIAnimationLocation _flipEnterAnim`

- `UIAnimationLocation _showExitAnim`

- `UIAnimationLocation _mapConfirmEnterAnim`

- `UIAnimationLocation _mapConfirmExitAnim`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `String m_actId`

- `Int32 m_cachedEnterSeqNum`

- `Int32 m_cachedPlayerShowEnterSeqNum`

- `Int32 m_cachedExitSeqNum`

- `ActMultiV3PrepareMainEntranceShowViewModel m_cachedViewModel`

- `ActMultiV3StageDetailView m_stageDetailView`

- `ActMultiV3ShortNameCardView m_selfNameCardView`

- `ActMultiV3ShortNameCardView m_partnerNameCardView`

- `ActMultiV3CommonBottomBar m_botBarView`

- `Builder m_animTweenBuilder`

- `UIAnimationLocation m_lastPlayerShowEnterAnim`

- `Tween m_cachedExitTween`


## Properties

- `Boolean isPlayingExit`

- `Int32 playingExitSeqNum`

- `GameObject entranceShowRoot`


## Methods

- `Boolean get_isPlayingExit()`

- `Int32 get_playingExitSeqNum()`

- `GameObject get_entranceShowRoot()`

- `Void InitIfNot()`

- `Void Render(ActMultiV3PrepareMainEntranceShowViewModel)`

- `Tween _GenShowMapConfirmTween()`

- `Tween _GenPlayerShowAndExitTween()`

- `Tween _GenResetTween()`

- `Void _SetGameObjectsActive(GameObject[], Boolean)`

- `IEnumerator PlayerShowCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainEntranceShowView : DataBinder`1, IHotfixable
{
	private GameObject[] _invertObjs; // 0x20
	private GameObject _entranceShowRoot; // 0x28
	private Image _selfEffectIcon; // 0x30
	private Image _partnerEffectIcon; // 0x38
	private Image _seasonIconImg2; // 0x40
	private Text _selfEffectNameTxt; // 0x48
	private Text _partnerEffectNameTxt; // 0x50
	private TwoStateToggle _partnerReadyToggle; // 0x58
	private TwoStateToggle _confirmBtnToggle; // 0x60
	private ActMultiV3ShortNameCardView _nameCardPrefab; // 0x68
	private ActMultiV3StageDetailView _stageDetailPrefab; // 0x70
	private RectTransform _selfNameCardContainer; // 0x78
	private RectTransform _partnerNameCardContainer; // 0x80
	private RectTransform _selfAssitIllustContainer; // 0x88
	private RectTransform _partnerAssitIllustContainer; // 0x90
	private RectTransform _stageDetailContainer; // 0x98
	private RectTransform _bottomBarContainer; // 0xa0
	private UIAnimationLocation _normEnterAnim; // 0xa8
	private UIAnimationLocation _flipEnterAnim; // 0xb8
	private UIAnimationLocation _showExitAnim; // 0xc8
	private UIAnimationLocation _mapConfirmEnterAnim; // 0xd8
	private UIAnimationLocation _mapConfirmExitAnim; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf8
	private Boolean m_isInited; // 0x108
	private String m_actId; // 0x110
	private Int32 m_cachedEnterSeqNum; // 0x118
	private Int32 m_cachedPlayerShowEnterSeqNum; // 0x11c
	private Int32 m_cachedExitSeqNum; // 0x120
	private ActMultiV3PrepareMainEntranceShowViewModel m_cachedViewModel; // 0x128
	private ActMultiV3StageDetailView m_stageDetailView; // 0x130
	private ActMultiV3ShortNameCardView m_selfNameCardView; // 0x138
	private ActMultiV3ShortNameCardView m_partnerNameCardView; // 0x140
	private ActMultiV3CommonBottomBar m_botBarView; // 0x148
	private UIStateTransitionTween`1 m_transTween; // 0x150
	private Builder m_animTweenBuilder; // 0x158
	private UIAnimationLocation m_lastPlayerShowEnterAnim; // 0x180
	private Tween m_cachedExitTween; // 0x190
	private static DelegateBridge __Hotfix0_get_isPlayingExit; // 0x0
	private static DelegateBridge __Hotfix0_get_playingExitSeqNum; // 0x8
	private static DelegateBridge __Hotfix0_get_entranceShowRoot; // 0x10
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__GenShowMapConfirmTween; // 0x30
	private static DelegateBridge __Hotfix0__GenPlayerShowAndExitTween; // 0x38
	private static DelegateBridge __Hotfix0__GenResetTween; // 0x40
	private static DelegateBridge __Hotfix0__SetGameObjectsActive; // 0x48
	private static DelegateBridge __Hotfix0_PlayerShowCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isPlayingExit { get; }
	public Int32 playingExitSeqNum { get; }
	public GameObject entranceShowRoot { get; }

	// RVA: 0x316ca28 VA: 0x7595784a28
	public Boolean get_isPlayingExit() { }
	// RVA: 0x316caa4 VA: 0x7595784aa4
	public Int32 get_playingExitSeqNum() { }
	// RVA: 0x316c410 VA: 0x7595784410
	public GameObject get_entranceShowRoot() { }
	// RVA: 0x316c044 VA: 0x7595784044
	public Void InitIfNot() { }
	// RVA: 0x316cb0c VA: 0x7595784b0c
	public override Void OnValueChanged(ActMultiV3PrepareMainEntranceShowProperty property) { }
	// RVA: 0x316cba0 VA: 0x7595784ba0
	public Void Render(ActMultiV3PrepareMainEntranceShowViewModel viewModel) { }
	// RVA: 0x316d138 VA: 0x7595785138
	private Tween _GenShowMapConfirmTween() { }
	// RVA: 0x316d288 VA: 0x7595785288
	private Tween _GenPlayerShowAndExitTween() { }
	// RVA: 0x316d628 VA: 0x7595785628
	private Tween _GenResetTween() { }
	// RVA: 0x316d050 VA: 0x7595785050
	private Void _SetGameObjectsActive(GameObject[] gameObjs, Boolean value) { }
	// RVA: 0x316c92c VA: 0x759578492c
	public IEnumerator PlayerShowCoroutine() { }
	// RVA: 0x316d99c VA: 0x759578599c
	public Void .ctor() { }
}
```