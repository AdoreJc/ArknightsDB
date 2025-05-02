# ActMultiV3SquadEffectSelectView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _textKeyCount`

- `SimpleLayoutContent _effectItemList`

- `Text _textHint`

- `Text _textCollectStarHint`

- `Text _textCollectProgress`

- `ActMultiV3SquadEffectInfoView _effectInfoViewPrefab`

- `Transform _effectInfoViewContainer`

- `GameObject _btnInteractGO`

- `GameObject _btnAlreadyEquipGO`

- `GameObject _btnKeyLackGO`

- `GameObject _collectProgressGO`

- `UIAnimationLocation _animBtnUnlock`

- `UIAnimationLocation _animCoinFade`

- `Boolean m_hasInited`

- `ActMultiV3SquadEffectSelectModel m_viewModel`

- `EffectItemAdapter m_effectItemAdapter`

- `String m_cacheSelectId`

- `AnimationSwitchTween m_btnTween`

- `AnimationSwitchTween m_coinFadeTween`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ActMultiV3SquadEffectInfoView m_effectInfoView`


## Methods

- `Void _RenderSelectEffectInfo(ActMultiV3SquadEffectSelectModel)`

- `Void _InitIfNot()`

- `Void _OnClick(ActMultiV3SquadEffectModel, Param)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectSelectView : DataBinder`1
{
	private Text _textKeyCount; // 0x20
	private SimpleLayoutContent _effectItemList; // 0x28
	private Text _textHint; // 0x30
	private Text _textCollectStarHint; // 0x38
	private Text _textCollectProgress; // 0x40
	private ActMultiV3SquadEffectInfoView _effectInfoViewPrefab; // 0x48
	private Transform _effectInfoViewContainer; // 0x50
	private GameObject _btnInteractGO; // 0x58
	private GameObject _btnAlreadyEquipGO; // 0x60
	private GameObject _btnKeyLackGO; // 0x68
	private GameObject _collectProgressGO; // 0x70
	private UIAnimationLocation _animBtnUnlock; // 0x78
	private UIAnimationLocation _animCoinFade; // 0x88
	private Boolean m_hasInited; // 0x98
	private ActMultiV3SquadEffectSelectModel m_viewModel; // 0xa0
	private EffectItemAdapter m_effectItemAdapter; // 0xa8
	private String m_cacheSelectId; // 0xb0
	private AnimationSwitchTween m_btnTween; // 0xb8
	private AnimationSwitchTween m_coinFadeTween; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd8
	private ActMultiV3SquadEffectInfoView m_effectInfoView; // 0xe8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderSelectEffectInfo; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x313b1b8 VA: 0x75957531b8
	public override Void OnValueChanged(ActMultiV3SquadEffectSelectProp property) { }
	// RVA: 0x313b830 VA: 0x7595753830
	private Void _RenderSelectEffectInfo(ActMultiV3SquadEffectSelectModel viewModel) { }
	// RVA: 0x313b5dc VA: 0x75957535dc
	private Void _InitIfNot() { }
	// RVA: 0x313b970 VA: 0x7595753970
	protected Void _OnClick(ActMultiV3SquadEffectModel effectModel, Param param) { }
	// RVA: 0x313ba84 VA: 0x7595753a84
	public Void .ctor() { }
}
```