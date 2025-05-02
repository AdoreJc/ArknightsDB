# ItemRepoIssueVoucherState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoIssueVoucherView _view`

- `GameObject _backPart`

- `ItemRepoIssueVoucherStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void BackToChoosePartOrDismissSelf()`

- `Void _ChooseConfirm()`

- `Void _OutputCancel()`

- `Void _OutputConfirm()`

- `IEnumerator _AfterConfirmItem(UIPage)`

- `Boolean _SelectItem(Int32, Int32)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <OnEnter>b__8_0(GetVoucherDetailResponse)`

- `Void <_OutputConfirm>b__14_0(UseOptionalVoucherResponse)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoIssueVoucherState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 MESSAGE_CHOOSE_CONFIRM; // 0x0
	public const Int32 MESSAGE_OUTPUT_CANCEL; // 0x0
	public const Int32 MESSAGE_OUTPUT_CONFIRM; // 0x0
	private ItemRepoIssueVoucherView _view; // 0x70
	private GameObject _backPart; // 0x78
	private ItemRepoIssueVoucherStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0_BackToChoosePartOrDismissSelf; // 0x28
	private static DelegateBridge __Hotfix0__ChooseConfirm; // 0x30
	private static DelegateBridge __Hotfix0__OutputCancel; // 0x38
	private static DelegateBridge __Hotfix0__OutputConfirm; // 0x40
	private static DelegateBridge __Hotfix0__AfterConfirmItem; // 0x48
	private static DelegateBridge __Hotfix0__SelectItem; // 0x50
	private static DelegateBridge __Hotfix0__ReceiveItems; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2d1e1b0 VA: 0x75953361b0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d1e218 VA: 0x7595336218
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2d1e3ac VA: 0x75953363ac
	protected override Void OnEnter() { }
	// RVA: 0x2d1e890 VA: 0x7595336890
	protected override Void OnExit() { }
	// RVA: 0x2d1e91c VA: 0x759533691c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2d1ee68 VA: 0x7595336e68
	public Void BackToChoosePartOrDismissSelf() { }
	// RVA: 0x2d1e9fc VA: 0x75953369fc
	private Void _ChooseConfirm() { }
	// RVA: 0x2d1ead4 VA: 0x7595336ad4
	private Void _OutputCancel() { }
	// RVA: 0x2d1ebac VA: 0x7595336bac
	private Void _OutputConfirm() { }
	// RVA: 0x2d1f444 VA: 0x7595337444
	private IEnumerator _AfterConfirmItem(UIPage page) { }
	// RVA: 0x2d1f53c VA: 0x759533753c
	private Boolean _SelectItem(Int32 index, Int32 count) { }
	// RVA: 0x2d1f8c0 VA: 0x75953378c0
	private static IEnumerator _ReceiveItems(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x2d1f9b8 VA: 0x75953379b8
	public Void .ctor() { }
	// RVA: 0x2d1fa64 VA: 0x7595337a64
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2d1fa8c VA: 0x7595337a8c
	private Void <OnEnter>b__8_0(GetVoucherDetailResponse response) { }
	// RVA: 0x2d20234 VA: 0x7595338234
	private Void <_OutputConfirm>b__14_0(UseOptionalVoucherResponse response) { }
	// RVA: 0x2d20344 VA: 0x7595338344
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2d2036c VA: 0x759533836c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d20374 VA: 0x7595338374
	private Void <>xLuaBaseProxy_OnExit() { }
}
```