# Act24sideMeldingState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMeldingView _view`

- `RectTransform _backPressRt`

- `UIAnimationLocation _animShow`

- `Boolean m_inited`

- `Act24sideMeldingProperty m_property`

- `TemplateActivityController m_cachedController`

- `Tween m_showTween`


## Methods

- `Void BindController(TemplateActivityController)`

- `Void _InitIfNot()`

- `Void _SendMeldRequest()`

- `Void _RefreshAfterClaimRewards()`

- `IEnumerator _MeldingSuc(String, List`1, List`1, Action)`

- `Boolean _CheckIsTransiting()`

- `Void _RefreshStageMeldingData()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnBackClicked()`

- `Void _EventOnSwitch()`

- `Void _EventOnItemLongPressAdd(String)`

- `Void _EventOnItemAdd(String)`

- `Void _AddItem(String, Int32)`

- `Void _EventOnItemLongPressMinus(String)`

- `Void _EventOnItemMinus(String)`

- `Void _MinusItem(String, Int32)`

- `Void _EventOnFastInputMaterial(String)`

- `Void _EventOnClearAllInputMaterial()`

- `Void _EventOnMeldClick(String)`

- `Void _EventOnChooseDetailShow(Int64)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingState : PopupFadeState, IBaseActStateHolder, IHotfixable, IValueMsgReceiver
{
	private Act24sideMeldingView _view; // 0x70
	private RectTransform _backPressRt; // 0x78
	private UIAnimationLocation _animShow; // 0x80
	public const Int32 MSG_SWITCH_CLICKED; // 0x0
	public const Int32 MSG_ITEM_ADD_CLICKED; // 0x0
	public const Int32 MSG_ITEM_MINUS_CLICKED; // 0x0
	public const Int32 MSG_FAST_INPUT_CLICKED; // 0x0
	public const Int32 MSG_MELDING_CLICKED; // 0x0
	public const Int32 MSG_CHOOSE_DETAIL_SHOW_CLICKED; // 0x0
	public const Int32 MSG_ITEM_ADD_LONG_PRESS; // 0x0
	public const Int32 MSG_ITEM_MINUS_LONG_PRESS; // 0x0
	public const Int32 MSG_CLEAR_ALL_INPUT_CLICKED; // 0x0
	private Boolean m_inited; // 0x90
	private Act24sideMeldingProperty m_property; // 0x98
	private TemplateActivityController m_cachedController; // 0xa0
	private Tween m_showTween; // 0xa8
	private const Int32 LONG_PRESS_MAX_CHANGE_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_BindController; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SendMeldRequest; // 0x30
	private static DelegateBridge __Hotfix0__RefreshAfterClaimRewards; // 0x38
	private static DelegateBridge __Hotfix0__MeldingSuc; // 0x40
	private static DelegateBridge __Hotfix0__CheckIsTransiting; // 0x48
	private static DelegateBridge __Hotfix0__RefreshStageMeldingData; // 0x50
	private static DelegateBridge __Hotfix0_OnMessage; // 0x58
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x60
	private static DelegateBridge __Hotfix0__EventOnSwitch; // 0x68
	private static DelegateBridge __Hotfix0__EventOnItemLongPressAdd; // 0x70
	private static DelegateBridge __Hotfix0__EventOnItemAdd; // 0x78
	private static DelegateBridge __Hotfix0__AddItem; // 0x80
	private static DelegateBridge __Hotfix0__EventOnItemLongPressMinus; // 0x88
	private static DelegateBridge __Hotfix0__EventOnItemMinus; // 0x90
	private static DelegateBridge __Hotfix0__MinusItem; // 0x98
	private static DelegateBridge __Hotfix0__EventOnFastInputMaterial; // 0xa0
	private static DelegateBridge __Hotfix0__EventOnClearAllInputMaterial; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnMeldClick; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnChooseDetailShow; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x32a3784 VA: 0x75958bb784
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32a37e8 VA: 0x75958bb7e8
	protected override Void OnEnter() { }
	// RVA: 0x32a43f4 VA: 0x75958bc3f4
	protected override Void OnResume() { }
	// RVA: 0x32a44d8 VA: 0x75958bc4d8
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x32a455c VA: 0x75958bc55c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x32a398c VA: 0x75958bb98c
	private Void _InitIfNot() { }
	// RVA: 0x32a4724 VA: 0x75958bc724
	private Void _SendMeldRequest() { }
	// RVA: 0x32a4dac VA: 0x75958bcdac
	private Void _RefreshAfterClaimRewards() { }
	// RVA: 0x32a4ea0 VA: 0x75958bcea0
	private IEnumerator _MeldingSuc(String gachaBoxId, List`1 progressChangesList, List`1 rewardList, Action onConfirm) { }
	// RVA: 0x32a4fec VA: 0x75958bcfec
	private Boolean _CheckIsTransiting() { }
	// RVA: 0x32a5178 VA: 0x75958bd178
	private Void _RefreshStageMeldingData() { }
	// RVA: 0x32a52b0 VA: 0x75958bd2b0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x32a5bfc VA: 0x75958bdbfc
	public Void OnBackClicked() { }
	// RVA: 0x32a544c VA: 0x75958bd44c
	private Void _EventOnSwitch() { }
	// RVA: 0x32a5a30 VA: 0x75958bda30
	private Void _EventOnItemLongPressAdd(String meldingItemId) { }
	// RVA: 0x32a5538 VA: 0x75958bd538
	private Void _EventOnItemAdd(String meldingItemId) { }
	// RVA: 0x32a5f34 VA: 0x75958bdf34
	private Void _AddItem(String meldingItemId, Int32 tryAddCount) { }
	// RVA: 0x32a5ab4 VA: 0x75958bdab4
	private Void _EventOnItemLongPressMinus(String meldingItemId) { }
	// RVA: 0x32a55bc VA: 0x75958bd5bc
	private Void _EventOnItemMinus(String meldingItemId) { }
	// RVA: 0x32a6640 VA: 0x75958be640
	private Void _MinusItem(String meldingItemId, Int32 count) { }
	// RVA: 0x32a5640 VA: 0x75958bd640
	private Void _EventOnFastInputMaterial(String gachaBoxId) { }
	// RVA: 0x32a5b38 VA: 0x75958bdb38
	private Void _EventOnClearAllInputMaterial() { }
	// RVA: 0x32a57a4 VA: 0x75958bd7a4
	private Void _EventOnMeldClick(String gachaBoxId) { }
	// RVA: 0x32a595c VA: 0x75958bd95c
	private Void _EventOnChooseDetailShow(Int64 show) { }
	// RVA: 0x32a6ca8 VA: 0x75958beca8
	public Void .ctor() { }
	// RVA: 0x32a6d18 VA: 0x75958bed18
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32a6d20 VA: 0x75958bed20
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x32a6d28 VA: 0x75958bed28
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```