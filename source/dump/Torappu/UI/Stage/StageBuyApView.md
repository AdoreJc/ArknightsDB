# StageBuyApView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `TwoStateToggle _useDiamondState`

- `TwoStateToggle _useApItemState`

- `GameObject _allContainer`

- `GameObject _noTimesView`

- `StageNoDiamondView _noDiamondView`

- `HomeAPUseApItemView _useApItemView`

- `StageUseDiamondView _useDiamondView`

- `GameObject _noApItemView`

- `UIBlurFloatPanel _backImage`

- `Text _textApCountDown`

- `GameObject _countDownDesc`

- `UIPageFinder m_pageFinder`

- `ActionPointViewModel m_apViewModel`

- `ItemRepoActionPointViewModelWithBuyApCount _apProperty`

- `Boolean m_isApItemFlag`

- `UIPageListener m_pageListener`

- `Int64 m_remainSeconds`

- `Single m_timeAccum`

- `ActionPointViewModel m_apModel`

- `Int32 m_cacheNeedCount`

- `Boolean m_isInited`

- `Boolean m_isOpen`


## Properties

- `ActionPointViewModel apViewModel`


## Methods

- `ActionPointViewModel get_apViewModel()`

- `Void _InitIfNot()`

- `Void _RefreshView(Int32)`

- `Void Refresh()`

- `Boolean _CheckHaveApItem()`

- `Boolean _CheckHaveDiamond()`

- `Void RefreshState(Boolean)`

- `Void RefreshState(Boolean, Int32)`

- `Void RenderDiamond()`

- `Void CleanDiamond()`

- `Void RenderApItem(Int32)`

- `Void CleanApItem()`

- `Void Dismiss()`

- `Void SendBuyApService()`

- `Void _OnBuyApSuccess(BuyApResponse)`

- `Void SendUseApItemService(List`1)`

- `Void UpdateTime(Single)`

- `Void OpenShopPage()`

- `Void <SendUseApItemService>b__41_0(UseItemResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageBuyApView : PageSingleComponent, ITimeWatcher, IHotfixable
{
	private TwoStateToggle _useDiamondState; // 0x20
	private TwoStateToggle _useApItemState; // 0x28
	private GameObject _allContainer; // 0x30
	private GameObject _noTimesView; // 0x38
	private StageNoDiamondView _noDiamondView; // 0x40
	private HomeAPUseApItemView _useApItemView; // 0x48
	private StageUseDiamondView _useDiamondView; // 0x50
	private GameObject _noApItemView; // 0x58
	private UIBlurFloatPanel _backImage; // 0x60
	private Text _textApCountDown; // 0x68
	private GameObject _countDownDesc; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private ActionPointViewModel m_apViewModel; // 0x88
	private Text[] _textsByDiamond; // 0x90
	private ItemRepoActionPointViewModelWithBuyApCount _apProperty; // 0x98
	private Boolean m_isApItemFlag; // 0xa0
	private UIPageListener m_pageListener; // 0xa8
	private Int64 m_remainSeconds; // 0xb0
	private Single m_timeAccum; // 0xb8
	private ActionPointViewModel m_apModel; // 0xc0
	private Int32 m_cacheNeedCount; // 0xc8
	private Boolean m_isInited; // 0xcc
	private Boolean m_isOpen; // 0xcd
	private static DelegateBridge __Hotfix0_get_apViewModel; // 0x0
	private static DelegateBridge __Hotfix0_InitRender; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RefreshView; // 0x18
	private static DelegateBridge __Hotfix0_RefreshViewOnResume; // 0x20
	private static DelegateBridge __Hotfix0_Refresh; // 0x28
	private static DelegateBridge __Hotfix0__CheckHaveApItem; // 0x30
	private static DelegateBridge __Hotfix0__CheckHaveDiamond; // 0x38
	private static DelegateBridge __Hotfix0_RefreshState; // 0x40
	private static DelegateBridge __Hotfix1_RefreshState; // 0x48
	private static DelegateBridge __Hotfix0_RenderDiamond; // 0x50
	private static DelegateBridge __Hotfix0_CleanDiamond; // 0x58
	private static DelegateBridge __Hotfix0_RenderApItem; // 0x60
	private static DelegateBridge __Hotfix0_CleanApItem; // 0x68
	private static DelegateBridge __Hotfix0_Dismiss; // 0x70
	private static DelegateBridge __Hotfix0_SendBuyApService; // 0x78
	private static DelegateBridge __Hotfix0__OnBuyApSuccess; // 0x80
	private static DelegateBridge __Hotfix0_SendUseApItemService; // 0x88
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x90
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x98
	private static DelegateBridge __Hotfix0_OpenShopPage; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public ActionPointViewModel apViewModel { get; }

	// RVA: 0x2f87fdc VA: 0x759559ffdc
	public ActionPointViewModel get_apViewModel() { }
	// RVA: 0x2f880d0 VA: 0x75955a00d0
	public static Void InitRender(Interface pageInterface, Int32 needAp) { }
	// RVA: 0x2f88224 VA: 0x75955a0224
	private Void _InitIfNot() { }
	// RVA: 0x2f883a8 VA: 0x75955a03a8
	private Void _RefreshView(Int32 needAp) { }
	// RVA: 0x2f886b0 VA: 0x75955a06b0
	public static Void RefreshViewOnResume() { }
	// RVA: 0x2f88810 VA: 0x75955a0810
	public Void Refresh() { }
	// RVA: 0x2f88528 VA: 0x75955a0528
	private Boolean _CheckHaveApItem() { }
	// RVA: 0x2f8887c VA: 0x75955a087c
	private Boolean _CheckHaveDiamond() { }
	// RVA: 0x2f8878c VA: 0x75955a078c
	public Void RefreshState(Boolean isApItem) { }
	// RVA: 0x2f885b4 VA: 0x75955a05b4
	public Void RefreshState(Boolean isApItem, Int32 needAp) { }
	// RVA: 0x2f88b14 VA: 0x75955a0b14
	private Void RenderDiamond() { }
	// RVA: 0x2f88a5c VA: 0x75955a0a5c
	private Void CleanDiamond() { }
	// RVA: 0x2f88928 VA: 0x75955a0928
	private Void RenderApItem(Int32 needAp) { }
	// RVA: 0x2f88c28 VA: 0x75955a0c28
	private Void CleanApItem() { }
	// RVA: 0x2f88cc4 VA: 0x75955a0cc4
	public Void Dismiss() { }
	// RVA: 0x2f88d5c VA: 0x75955a0d5c
	public Void SendBuyApService() { }
	// RVA: 0x2f8905c VA: 0x75955a105c
	private Void _OnBuyApSuccess(BuyApResponse response) { }
	// RVA: 0x2f89198 VA: 0x75955a1198
	public Void SendUseApItemService(List`1 itemViewModelList) { }
	// RVA: 0x2f89674 VA: 0x75955a1674
	public static IEnumerator ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x2f89720 VA: 0x75955a1720
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2f899f4 VA: 0x75955a19f4
	public Void OpenShopPage() { }
	// RVA: 0x2f89a80 VA: 0x75955a1a80
	public Void .ctor() { }
	// RVA: 0x2f89b38 VA: 0x75955a1b38
	private Void <SendUseApItemService>b__41_0(UseItemResponse response) { }
}
```