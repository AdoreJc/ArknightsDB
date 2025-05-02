# ItemRepoOptionalVoucherState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoOptionalVoucherView _view`

- `GameObject _backImg`

- `ItemRepoOptionalVoucherStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _ToDetailState(IStateBean)`

- `Void AddPickItem(String)`

- `Void MinusPickItem(String)`

- `Void ShowItemDetail(String)`

- `Void _InitView()`

- `Void _ChooseConfirm()`

- `Void _OutputCancel()`

- `Void _OutputConfirm()`

- `IEnumerator _AfterConfirmItem(UIPage)`

- `Void BackToChoosePartOrDismissSelf()`

- `Void <OnEnter>b__5_0(GetVoucherDetailResponse)`

- `Void <_OutputConfirm>b__15_0(UseOptionalVoucherResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherState : PopupFloatState
{
	private ItemRepoOptionalVoucherView _view; // 0x70
	private GameObject _backImg; // 0x78
	private ItemRepoOptionalVoucherStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__ToDetailState; // 0x20
	private static DelegateBridge __Hotfix0_AddPickItem; // 0x28
	private static DelegateBridge __Hotfix0_MinusPickItem; // 0x30
	private static DelegateBridge __Hotfix0_ShowItemDetail; // 0x38
	private static DelegateBridge __Hotfix0__InitView; // 0x40
	private static DelegateBridge __Hotfix0__ChooseConfirm; // 0x48
	private static DelegateBridge __Hotfix0__OutputCancel; // 0x50
	private static DelegateBridge __Hotfix0__OutputConfirm; // 0x58
	private static DelegateBridge __Hotfix0__AfterConfirmItem; // 0x60
	private static DelegateBridge __Hotfix0__ReceiveItems; // 0x68
	private static DelegateBridge __Hotfix0_BackToChoosePartOrDismissSelf; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2d21fac VA: 0x7595339fac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d22014 VA: 0x759533a014
	protected override Void OnEnter() { }
	// RVA: 0x2d22514 VA: 0x759533a514
	protected override Void OnExit() { }
	// RVA: 0x2d225a0 VA: 0x759533a5a0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d22718 VA: 0x759533a718
	private Void _ToDetailState(IStateBean stateBean) { }
	// RVA: 0x2d22838 VA: 0x759533a838
	public Void AddPickItem(String itemId) { }
	// RVA: 0x2d228c0 VA: 0x759533a8c0
	public Void MinusPickItem(String itemId) { }
	// RVA: 0x2d22948 VA: 0x759533a948
	public Void ShowItemDetail(String itemId) { }
	// RVA: 0x2d22acc VA: 0x759533aacc
	private Void _InitView() { }
	// RVA: 0x2d22c78 VA: 0x759533ac78
	private Void _ChooseConfirm() { }
	// RVA: 0x2d22cec VA: 0x759533acec
	private Void _OutputCancel() { }
	// RVA: 0x2d22d60 VA: 0x759533ad60
	private Void _OutputConfirm() { }
	// RVA: 0x2d22fe8 VA: 0x759533afe8
	private IEnumerator _AfterConfirmItem(UIPage page) { }
	// RVA: 0x2d230e0 VA: 0x759533b0e0
	private static IEnumerator _ReceiveItems(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x2d231d8 VA: 0x759533b1d8
	public Void BackToChoosePartOrDismissSelf() { }
	// RVA: 0x2d233b8 VA: 0x759533b3b8
	public Void .ctor() { }
	// RVA: 0x2d23464 VA: 0x759533b464
	private Void <OnEnter>b__5_0(GetVoucherDetailResponse response) { }
	// RVA: 0x2d23544 VA: 0x759533b544
	private Void <_OutputConfirm>b__15_0(UseOptionalVoucherResponse response) { }
	// RVA: 0x2d23654 VA: 0x759533b654
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d2365c VA: 0x759533b65c
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2d23664 VA: 0x759533b664
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```