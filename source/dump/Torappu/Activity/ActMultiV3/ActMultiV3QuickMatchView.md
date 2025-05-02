# ActMultiV3QuickMatchView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `SimpleLayoutContent _modeList`

- `SimpleLayoutContent _matchPosList`

- `GameObject _btnStartNormalGO`

- `GameObject _btnStartDisableGO`

- `GameObject _btnMatchPosGO`

- `GameObject _guidebookGO`

- `CanvasGroup _matchPosListPanel`

- `GameObject _matchPosDescGO`

- `Text _textPosDesc`

- `Text _textCurrMatchPos`

- `Text _textInverseDesc`

- `CanvasGroup _inverseDescHandler`

- `Image _imgCurrMatchIcon`

- `Single _posPanelFadeDuration`

- `ActMultiV3InverseToggleView _inverseTogglePrefab`

- `RectTransform _inverseToggleContainer`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _animModeListSwitch`

- `UIAnimationLocation _animBtnSelectPosSwitch`

- `UIAnimationLocation _animInverseModeEnter`

- `CanvasGroup _inverseEffectHandler`

- `Single _inverseEffectFadeDuration`

- `PageCameraRenderTextureHolder _renderTextureHolder`

- `RectTransform _billboardCanvasRoot`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ActMultiV3QuickMatchModel m_matchModel`

- `ModeListAdapter m_modeListAdapter`

- `MatchPosList m_matchPosListAdapter`

- `FadeSwitchTween m_posListPanelTween`

- `AnimationSwitchTween m_btnSelectPosTween`

- `ActMultiV3InverseToggleView m_inverseToggleView`

- `Int32 m_cacheEnterSeqNum`

- `Tween m_enterTween`

- `AnimationSwitchTween m_modeListTween`

- `FadeSwitchTween m_inverseEffectTween`

- `FadeSwitchTween m_inverseDescTween`

- `Tween m_inverseEffectEnterTween`

- `String m_cachedActId`

- `GameObject m_matchAnimObj`


## Methods

- `Void _PlayInverseEffectAnimIfNeed(ActMultiV3QuickMatchModel)`

- `Void _PlayEnterAnimIfNeed(ActMultiV3QuickMatchModel)`

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Void _EventOnInverseToggleClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3QuickMatchView : DataBinder`1
{
	private SimpleLayoutContent _modeList; // 0x20
	private SimpleLayoutContent _matchPosList; // 0x28
	private GameObject _btnStartNormalGO; // 0x30
	private GameObject _btnStartDisableGO; // 0x38
	private GameObject _btnMatchPosGO; // 0x40
	private GameObject _guidebookGO; // 0x48
	private CanvasGroup _matchPosListPanel; // 0x50
	private GameObject _matchPosDescGO; // 0x58
	private Text _textPosDesc; // 0x60
	private Text _textCurrMatchPos; // 0x68
	private Text _textInverseDesc; // 0x70
	private CanvasGroup _inverseDescHandler; // 0x78
	private Image _imgCurrMatchIcon; // 0x80
	private Single _posPanelFadeDuration; // 0x88
	private ActMultiV3InverseToggleView _inverseTogglePrefab; // 0x90
	private RectTransform _inverseToggleContainer; // 0x98
	private UIAnimationLocation _animEnter; // 0xa0
	private UIAnimationLocation _animModeListSwitch; // 0xb0
	private UIAnimationLocation _animBtnSelectPosSwitch; // 0xc0
	private UIAnimationLocation _animInverseModeEnter; // 0xd0
	private CanvasGroup _inverseEffectHandler; // 0xe0
	private Single _inverseEffectFadeDuration; // 0xe8
	private PageCameraRenderTextureHolder _renderTextureHolder; // 0xf0
	private UIMeshImage[] _billboardMeshImages; // 0xf8
	private RectTransform _billboardCanvasRoot; // 0x100
	private Boolean m_hasInited; // 0x108
	private UIPageFinder m_pageFinder; // 0x110
	private UIStateFinder m_stateFinder; // 0x120
	private ActMultiV3QuickMatchModel m_matchModel; // 0x130
	private ModeListAdapter m_modeListAdapter; // 0x138
	private MatchPosList m_matchPosListAdapter; // 0x140
	private FadeSwitchTween m_posListPanelTween; // 0x148
	private AnimationSwitchTween m_btnSelectPosTween; // 0x150
	private ActMultiV3InverseToggleView m_inverseToggleView; // 0x158
	private Int32 m_cacheEnterSeqNum; // 0x160
	private Tween m_enterTween; // 0x168
	private AnimationSwitchTween m_modeListTween; // 0x170
	private FadeSwitchTween m_inverseEffectTween; // 0x178
	private FadeSwitchTween m_inverseDescTween; // 0x180
	private Tween m_inverseEffectEnterTween; // 0x188
	private String m_cachedActId; // 0x190
	private GameObject m_matchAnimObj; // 0x198
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayInverseEffectAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__PlayEnterAnimIfNeed; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x20
	private static DelegateBridge __Hotfix0__EventOnInverseToggleClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3134b18 VA: 0x759574cb18
	public override Void OnValueChanged(ActMultiV3QuickMatchProp property) { }
	// RVA: 0x3135584 VA: 0x759574d584
	private Void _PlayInverseEffectAnimIfNeed(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3135438 VA: 0x759574d438
	private Void _PlayEnterAnimIfNeed(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3134fc8 VA: 0x759574cfc8
	private Void _InitIfNot() { }
	// RVA: 0x31356fc VA: 0x759574d6fc
	private Void _RegisterTutorialGo() { }
	// RVA: 0x3135940 VA: 0x759574d940
	private Void _EventOnInverseToggleClick() { }
	// RVA: 0x31359e4 VA: 0x759574d9e4
	public Void .ctor() { }
}
```