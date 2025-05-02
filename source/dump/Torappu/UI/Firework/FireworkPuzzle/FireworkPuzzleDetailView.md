# FireworkPuzzleDetailView

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `RectTransform _plateContainer`

- `RectTransform _selectionContainer`

- `Transform _plateListContainer`

- `Transform _plateFillContainer`

- `RectTransform _bgContainer`

- `RectTransform _bgParticleEffectContainer`

- `RectTransform _itemContainer`

- `FireworkGroupListRaycastLayer _pnlRaycastLayer`

- `FireworkPuzzleNpcView _npcView`

- `Single _itemScale`

- `Color _colorItemGot`

- `GameObject _itemGotPartGo`

- `GameObject _btnHintGo`

- `Text _textHintCount`

- `GameObject _puzzleCompleteGo`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _animBtnConfirm`

- `UIColorGraphic _btnHintGraphic`

- `Color _colorBtnHintGrey`

- `GameObject _puzzlePlateGo`

- `GameObject _btnConfirmGo`

- `GameObject _plateListGo`

- `GameObject _plateFillGo`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `FireworkPlateViewStyle m_plateStyle`

- `FireworkPlateGroupViewStyle m_plateGroupStyle`

- `FireworkPlateView m_plateView`

- `FireworkPlateSelectionView m_selectionView`

- `FireworkPlateListView m_plateListView`

- `FireworkPlateFilledListView m_plateFillView`

- `UIItemCard m_rewardItem`

- `Int32 m_cacheEnterSeqNum`

- `Tween m_enterTween`

- `AnimationSwitchTween m_btnConfirmTween`

- `Int32 m_cacheHintSeqNum`


## Methods

- `Void _UpdateHintPin(FireworkPuzzleDetailModel)`

- `Void _PlayEnterAnimIfNeed(FireworkPuzzleDetailModel)`

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleDetailView : DataBinder`1
{
	private RectTransform _plateContainer; // 0x20
	private RectTransform _selectionContainer; // 0x28
	private Transform _plateListContainer; // 0x30
	private Transform _plateFillContainer; // 0x38
	private RectTransform _bgContainer; // 0x40
	private RectTransform _bgParticleEffectContainer; // 0x48
	private RectTransform _itemContainer; // 0x50
	private FireworkGroupListRaycastLayer _pnlRaycastLayer; // 0x58
	private FireworkPuzzleNpcView _npcView; // 0x60
	private Single _itemScale; // 0x68
	private Color _colorItemGot; // 0x6c
	private GameObject _itemGotPartGo; // 0x80
	private GameObject _btnHintGo; // 0x88
	private Text _textHintCount; // 0x90
	private GameObject _puzzleCompleteGo; // 0x98
	private UIAnimationLocation _animEnter; // 0xa0
	private UIAnimationLocation _animBtnConfirm; // 0xb0
	private UIAnimationLocation[] _hintPinAnimList; // 0xc0
	private UIColorGraphic _btnHintGraphic; // 0xc8
	private Color _colorBtnHintGrey; // 0xd0
	private GameObject _puzzlePlateGo; // 0xe0
	private GameObject _btnConfirmGo; // 0xe8
	private GameObject _plateListGo; // 0xf0
	private GameObject _plateFillGo; // 0xf8
	private Boolean m_hasInited; // 0x100
	private UIPageFinder m_pageFinder; // 0x108
	private FireworkPlateViewStyle m_plateStyle; // 0x118
	private FireworkPlateGroupViewStyle m_plateGroupStyle; // 0x120
	private FireworkPlateView m_plateView; // 0x128
	private FireworkPlateSelectionView m_selectionView; // 0x130
	private FireworkPlateListView m_plateListView; // 0x138
	private FireworkPlateFilledListView m_plateFillView; // 0x140
	private UIItemCard m_rewardItem; // 0x148
	private Int32 m_cacheEnterSeqNum; // 0x150
	private Tween m_enterTween; // 0x158
	private AnimationSwitchTween m_btnConfirmTween; // 0x160
	private List`1 m_hintPinTweenList; // 0x168
	private Int32 m_cacheHintSeqNum; // 0x170
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__UpdateHintPin; // 0x8
	private static DelegateBridge __Hotfix0__PlayEnterAnimIfNeed; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28fc110 VA: 0x7594f14110
	public override Void OnValueChanged(FireworkPuzzleDetailProp property) { }
	// RVA: 0x28fd2cc VA: 0x7594f152cc
	private Void _UpdateHintPin(FireworkPuzzleDetailModel detailModel) { }
	// RVA: 0x28fd190 VA: 0x7594f15190
	private Void _PlayEnterAnimIfNeed(FireworkPuzzleDetailModel detailModel) { }
	// RVA: 0x28fc68c VA: 0x7594f1468c
	private Void _InitIfNot() { }
	// RVA: 0x28fd420 VA: 0x7594f15420
	private Void _RegisterTutorialGo() { }
	// RVA: 0x28fd5cc VA: 0x7594f155cc
	public Void .ctor() { }
}
```