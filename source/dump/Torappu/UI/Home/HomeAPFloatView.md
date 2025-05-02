# HomeAPFloatView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textApCountDown`

- `GameObject _countDownDesc`

- `UIAnimationLocation _showAnimation`

- `UnityEvent _eventBuyApFinish`

- `TwoStateToggle _useApItemState`

- `TwoStateToggle _useDiamondState`

- `HomeAPUseDiamondView _useDiamondView`

- `GameObject _noDiamondView`

- `GameObject _noTimesView`

- `GameObject _noApItemView`

- `HomeAPUseApItemView _useApItemView`

- `ItemRepoActionPointViewModelWithBuyApCount _apProperty`

- `Boolean m_isShow`

- `Tween m_showTweener`

- `Int64 m_remainSeconds`

- `Single m_timeAccum`

- `ActionPointViewModel m_apModel`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `Boolean m_isApItemFlag`


## Methods

- `Void Show()`

- `Void OnSelectTag(Boolean)`

- `Void RefreshIfActive()`

- `Void RenderDiamond()`

- `Void CleanDiamond()`

- `Void RenderApItem()`

- `Void CleanApItem()`

- `Void OpenShopPage()`

- `Void Dismiss()`

- `Void UpdateTime(Single)`

- `Void EventOnConfirmBuyClick()`

- `Void EventOnCancelBuyClick()`

- `Void SendUseApItemService(List`1)`

- `Void _InitIfNot()`

- `Void _SendBuyApService()`

- `Void _OnBuyApSuccess(BuyApResponse)`

- `ActionPointViewModel _GetApModel()`

- `Void <Show>b__23_0()`

- `Void <Dismiss>b__31_0()`

- `Void <SendUseApItemService>b__35_0(UseItemResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAPFloatView : MonoBehaviour, ITimeWatcher, IHotfixable
{
	public const Single UPDATE_INTERVAL; // 0x0
	private Text _textApCountDown; // 0x18
	private GameObject _countDownDesc; // 0x20
	private UIAnimationLocation _showAnimation; // 0x28
	private UnityEvent _eventBuyApFinish; // 0x38
	private TwoStateToggle _useApItemState; // 0x40
	private TwoStateToggle _useDiamondState; // 0x48
	private HomeAPUseDiamondView _useDiamondView; // 0x50
	private GameObject _noDiamondView; // 0x58
	private GameObject _noTimesView; // 0x60
	private GameObject _noApItemView; // 0x68
	private HomeAPUseApItemView _useApItemView; // 0x70
	private Text[] _textsUseDiamond; // 0x78
	private ItemRepoActionPointViewModelWithBuyApCount _apProperty; // 0x80
	private Boolean m_isShow; // 0x88
	private Tween m_showTweener; // 0x90
	private Int64 m_remainSeconds; // 0x98
	private Single m_timeAccum; // 0xa0
	private ActionPointViewModel m_apModel; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private Boolean m_isInited; // 0xc0
	private Boolean m_isApItemFlag; // 0xc1
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_OnSelectTag; // 0x10
	private static DelegateBridge __Hotfix0_RefreshIfActive; // 0x18
	private static DelegateBridge __Hotfix0_RenderDiamond; // 0x20
	private static DelegateBridge __Hotfix0_CleanDiamond; // 0x28
	private static DelegateBridge __Hotfix0_RenderApItem; // 0x30
	private static DelegateBridge __Hotfix0_CleanApItem; // 0x38
	private static DelegateBridge __Hotfix0_OpenShopPage; // 0x40
	private static DelegateBridge __Hotfix0_Dismiss; // 0x48
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x50
	private static DelegateBridge __Hotfix0_EventOnConfirmBuyClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnCancelBuyClick; // 0x60
	private static DelegateBridge __Hotfix0_SendUseApItemService; // 0x68
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__SendBuyApService; // 0x80
	private static DelegateBridge __Hotfix0__OnBuyApSuccess; // 0x88
	private static DelegateBridge __Hotfix0__GetApModel; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x28275ec VA: 0x7594e3f5ec
	protected virtual Void Start() { }
	// RVA: 0x282770c VA: 0x7594e3f70c
	public Void Show() { }
	// RVA: 0x2827b38 VA: 0x7594e3fb38
	public Void OnSelectTag(Boolean isApItem) { }
	// RVA: 0x2828004 VA: 0x7594e40004
	public Void RefreshIfActive() { }
	// RVA: 0x2827e08 VA: 0x7594e3fe08
	private Void RenderDiamond() { }
	// RVA: 0x2827d50 VA: 0x7594e3fd50
	private Void CleanDiamond() { }
	// RVA: 0x2827c10 VA: 0x7594e3fc10
	private Void RenderApItem() { }
	// RVA: 0x2827f68 VA: 0x7594e3ff68
	private Void CleanApItem() { }
	// RVA: 0x2828084 VA: 0x7594e40084
	public Void OpenShopPage() { }
	// RVA: 0x2828110 VA: 0x7594e40110
	public Void Dismiss() { }
	// RVA: 0x2828308 VA: 0x7594e40308
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2828704 VA: 0x7594e40704
	public Void EventOnConfirmBuyClick() { }
	// RVA: 0x2828b20 VA: 0x7594e40b20
	public Void EventOnCancelBuyClick() { }
	// RVA: 0x2828ba0 VA: 0x7594e40ba0
	public Void SendUseApItemService(List`1 itemViewModelList) { }
	// RVA: 0x28290bc VA: 0x7594e410bc
	public static IEnumerator ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x2827a60 VA: 0x7594e3fa60
	private Void _InitIfNot() { }
	// RVA: 0x2828924 VA: 0x7594e40924
	private Void _SendBuyApService() { }
	// RVA: 0x2829168 VA: 0x7594e41168
	private Void _OnBuyApSuccess(BuyApResponse response) { }
	// RVA: 0x2828610 VA: 0x7594e40610
	private ActionPointViewModel _GetApModel() { }
	// RVA: 0x28292bc VA: 0x7594e412bc
	public Void .ctor() { }
	// RVA: 0x2829334 VA: 0x7594e41334
	private Void <Show>b__23_0() { }
	// RVA: 0x2829360 VA: 0x7594e41360
	private Void <Dismiss>b__31_0() { }
	// RVA: 0x28293b0 VA: 0x7594e413b0
	private Void <SendUseApItemService>b__35_0(UseItemResponse response) { }
}
```