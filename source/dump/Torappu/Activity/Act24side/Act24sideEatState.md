# Act24sideEatState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideEatView _view`

- `RectTransform _backPressRt`

- `UIAnimationLocation _animShow`

- `Single _audioFxDelay`

- `Boolean m_inited`

- `StateBean m_stateBean`

- `TemplateActivityController m_cachedController`

- `Tween m_showTween`


## Methods

- `Void _InitIfNot()`

- `Void BindController(TemplateActivityController)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _RefreshEntryEatData()`

- `Void _OnMealItemClicked(String)`

- `Void _OnMealConfirmClicked()`

- `Void OnBackClicked()`

- `Void <_OnMealConfirmClicked>b__19_0(Act24SideEatResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEatState : PopupFadeState, IBaseActStateHolder, IHotfixable, IValueMsgReceiver
{
	private Act24sideEatView _view; // 0x70
	private RectTransform _backPressRt; // 0x78
	private UIAnimationLocation _animShow; // 0x80
	private Single _audioFxDelay; // 0x90
	public const Int32 MSG_MEAL_ITEM_CLICKED; // 0x0
	public const Int32 MSG_MEAL_CONFIRM_CLICKED; // 0x0
	private Boolean m_inited; // 0x94
	private StateBean m_stateBean; // 0x98
	private TemplateActivityController m_cachedController; // 0xa0
	private Tween m_showTween; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_BindController; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__RefreshEntryEatData; // 0x30
	private static DelegateBridge __Hotfix0__OnMealItemClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnMealConfirmClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x3298ad4 VA: 0x75958b0ad4
	private Void _InitIfNot() { }
	// RVA: 0x3298bd8 VA: 0x75958b0bd8
	protected override Void OnEnter() { }
	// RVA: 0x3298dd4 VA: 0x75958b0dd4
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x32990d4 VA: 0x75958b10d4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x329913c VA: 0x75958b113c
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x32991c0 VA: 0x75958b11c0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3299878 VA: 0x75958b1878
	private Void _RefreshEntryEatData() { }
	// RVA: 0x3299288 VA: 0x75958b1288
	private Void _OnMealItemClicked(String mealId) { }
	// RVA: 0x3299464 VA: 0x75958b1464
	private Void _OnMealConfirmClicked() { }
	// RVA: 0x3299a60 VA: 0x75958b1a60
	public Void OnBackClicked() { }
	// RVA: 0x3299c04 VA: 0x75958b1c04
	public Void .ctor() { }
	// RVA: 0x3299d68 VA: 0x75958b1d68
	private Void <_OnMealConfirmClicked>b__19_0(Act24SideEatResponse response) { }
	// RVA: 0x3299f58 VA: 0x75958b1f58
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3299f60 VA: 0x75958b1f60
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```