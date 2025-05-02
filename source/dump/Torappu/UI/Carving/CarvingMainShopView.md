# CarvingMainShopView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Text _roundText`

- `GameObject _refreshObj`

- `Text _refreshCoinText`

- `Color _enoughCoinRefreshColor`

- `Color _notEnoughCoinRefreshColor`

- `UIAnimationLocation _shopRefreshAnimLocation`

- `Single _shopRefreshRenderDelay`

- `GameObject _noGoodsObj`

- `CarvingMainShopGoodSlotView _slotView`

- `Single _materialScaler`

- `SimpleLayoutContent _materialContent`

- `GameObject _materialObj`

- `GameObject _canBuyObj`

- `GameObject _canNotBuyObj`

- `GameObject _buyGroupObj`

- `GameObject _canNextStepObj`

- `GameObject _canNotNextStepObj`

- `UIAnimationLocation _freeNotifyAnimLocation`

- `GameObject _freeCntObj`

- `Text _freeCardCntTxt`

- `GameObject _tipsObj`

- `GameObject _panelNextRoundMat`

- `GameObject _panelBtnToProcess`

- `GameObject _panelFreeBuyCount`

- `GameObject _panelBuyCardGroup`

- `GameObject _panelBtnBuyCard`

- `GameObject _panelBtnNewSlot`

- `Boolean m_isInited`

- `ShopMaterialAdapter m_adapter`

- `UIPageFinder m_pageFinder`

- `Int32 m_freeNotifySeqNum`

- `Tween m_freeNotifyTween`

- `Int32 m_refreshNotifySeqNum`

- `Sequence m_refreshSequence`


## Methods

- `Void StateOnlyRegisterTutorialGO()`

- `Void _PlayRefreshTweenAndRender(CarvingMainShopViewModel)`

- `Void _Render(CarvingMainShopViewModel)`

- `Void _InitIfNot()`

- `Void _PlayFreeNotifyAnim()`

- `Void OnClickCheckInfoBtn()`

- `Void OnClickRefreshBtn()`

- `Void OnClickBuyBtn()`

- `Void OnClickToProcessBtn()`

- `Void OnClickHandbookBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainShopView : DataBinder`1
{
	private Text _roundText; // 0x20
	private GameObject _refreshObj; // 0x28
	private Text _refreshCoinText; // 0x30
	private Color _enoughCoinRefreshColor; // 0x38
	private Color _notEnoughCoinRefreshColor; // 0x48
	private UIAnimationLocation _shopRefreshAnimLocation; // 0x58
	private Single _shopRefreshRenderDelay; // 0x68
	private GameObject _noGoodsObj; // 0x70
	private List`1 _cardViewList; // 0x78
	private CarvingMainShopGoodSlotView _slotView; // 0x80
	private Single _materialScaler; // 0x88
	private SimpleLayoutContent _materialContent; // 0x90
	private GameObject _materialObj; // 0x98
	private GameObject _canBuyObj; // 0xa0
	private GameObject _canNotBuyObj; // 0xa8
	private GameObject _buyGroupObj; // 0xb0
	private GameObject _canNextStepObj; // 0xb8
	private GameObject _canNotNextStepObj; // 0xc0
	private UIAnimationLocation _freeNotifyAnimLocation; // 0xc8
	private GameObject _freeCntObj; // 0xd8
	private Text _freeCardCntTxt; // 0xe0
	private GameObject _tipsObj; // 0xe8
	private GameObject _panelNextRoundMat; // 0xf0
	private GameObject _panelBtnToProcess; // 0xf8
	private GameObject _panelFreeBuyCount; // 0x100
	private GameObject _panelBuyCardGroup; // 0x108
	private GameObject _panelBtnBuyCard; // 0x110
	private GameObject _panelBtnNewSlot; // 0x118
	private List`1 m_cachedMaterialList; // 0x120
	private Boolean m_isInited; // 0x128
	private ShopMaterialAdapter m_adapter; // 0x130
	private UIPageFinder m_pageFinder; // 0x138
	private Int32 m_freeNotifySeqNum; // 0x148
	private Tween m_freeNotifyTween; // 0x150
	private Int32 m_refreshNotifySeqNum; // 0x158
	private Sequence m_refreshSequence; // 0x160
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_StateOnlyRegisterTutorialGO; // 0x8
	private static DelegateBridge __Hotfix0__PlayRefreshTweenAndRender; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__PlayFreeNotifyAnim; // 0x28
	private static DelegateBridge __Hotfix0_OnClickCheckInfoBtn; // 0x30
	private static DelegateBridge __Hotfix0_OnClickRefreshBtn; // 0x38
	private static DelegateBridge __Hotfix0_OnClickBuyBtn; // 0x40
	private static DelegateBridge __Hotfix0_OnClickToProcessBtn; // 0x48
	private static DelegateBridge __Hotfix0_OnClickHandbookBtn; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2db9ce8 VA: 0x75953d1ce8
	public override Void OnValueChanged(CarvingMainProperty property) { }
	// RVA: 0x2dba638 VA: 0x75953d2638
	public Void StateOnlyRegisterTutorialGO() { }
	// RVA: 0x2db9f24 VA: 0x75953d1f24
	private Void _PlayRefreshTweenAndRender(CarvingMainShopViewModel model) { }
	// RVA: 0x2dba154 VA: 0x75953d2154
	private Void _Render(CarvingMainShopViewModel model) { }
	// RVA: 0x2db9de8 VA: 0x75953d1de8
	private Void _InitIfNot() { }
	// RVA: 0x2dba8cc VA: 0x75953d28cc
	private Void _PlayFreeNotifyAnim() { }
	// RVA: 0x2dbb188 VA: 0x75953d3188
	public Void OnClickCheckInfoBtn() { }
	// RVA: 0x2dbb240 VA: 0x75953d3240
	public Void OnClickRefreshBtn() { }
	// RVA: 0x2dbb2f8 VA: 0x75953d32f8
	public Void OnClickBuyBtn() { }
	// RVA: 0x2dbb3b0 VA: 0x75953d33b0
	public Void OnClickToProcessBtn() { }
	// RVA: 0x2dbb468 VA: 0x75953d3468
	public Void OnClickHandbookBtn() { }
	// RVA: 0x2dbb568 VA: 0x75953d3568
	public Void .ctor() { }
}
```