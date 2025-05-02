# BirthdaySettingState

**Namespace:** `Torappu.UI.Birthday`


## Fields

- `RectTransform _dlgContainer`

- `BirthdaySettingView _view`

- `RectTransform _backRect`

- `Boolean m_isInited`

- `Int32 m_dateSelectDlg`

- `UICompDialogMgr m_dlgMgr`

- `BirthdaySettingProperty m_prop`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateData()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSetDateClick()`

- `Void _OnSetRegisterDateClick()`

- `Void _OnCloseClick()`

- `Void _OnConfirmClick()`

- `Void _OnJudgeConfirm()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _OnDateSelect(ValueBundle)`

- `Void <_OnJudgeConfirm>b__20_0(BirthdaySettingResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Birthday
public class BirthdaySettingState : PopupFloatState, ICompDialogCallBack, IValueMsgReceiver
{
	private RectTransform _dlgContainer; // 0x70
	private BirthdaySettingView _view; // 0x78
	private RectTransform _backRect; // 0x80
	private Boolean m_isInited; // 0x88
	private Int32 m_dateSelectDlg; // 0x8c
	private UICompDialogMgr m_dlgMgr; // 0x90
	private BirthdaySettingProperty m_prop; // 0x98
	public const Int32 ON_SET_DATE_CLICK; // 0x0
	public const Int32 ON_SET_REGISTER_DATE_CLICK; // 0x0
	public const Int32 ON_CONFIRM_CLICK; // 0x0
	public const Int32 ON_CLOSE_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__UpdateData; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnSetDateClick; // 0x28
	private static DelegateBridge __Hotfix0__OnSetRegisterDateClick; // 0x30
	private static DelegateBridge __Hotfix0__OnCloseClick; // 0x38
	private static DelegateBridge __Hotfix0__OnConfirmClick; // 0x40
	private static DelegateBridge __Hotfix0__OnJudgeConfirm; // 0x48
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x50
	private static DelegateBridge __Hotfix0__OnDateSelect; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2e7cc5c VA: 0x7595494c5c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e7ccc0 VA: 0x7595494cc0
	private Void _InitIfNot() { }
	// RVA: 0x2e7ce70 VA: 0x7595494e70
	protected override Void OnEnter() { }
	// RVA: 0x2e7cf40 VA: 0x7595494f40
	private Void _UpdateData() { }
	// RVA: 0x2e7d1d8 VA: 0x75954951d8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2e7d2e0 VA: 0x75954952e0
	private Void _OnSetDateClick() { }
	// RVA: 0x2e7d4b8 VA: 0x75954954b8
	private Void _OnSetRegisterDateClick() { }
	// RVA: 0x2e7dac4 VA: 0x7595495ac4
	private Void _OnCloseClick() { }
	// RVA: 0x2e7d590 VA: 0x7595495590
	private Void _OnConfirmClick() { }
	// RVA: 0x2e7dda0 VA: 0x7595495da0
	private Void _OnJudgeConfirm() { }
	// RVA: 0x2e7e0fc VA: 0x75954960fc
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2e7e1a4 VA: 0x75954961a4
	private Void _OnDateSelect(ValueBundle output) { }
	// RVA: 0x2e7e31c VA: 0x759549631c
	public Void .ctor() { }
	// RVA: 0x2e7e434 VA: 0x7595496434
	private Void <_OnJudgeConfirm>b__20_0(BirthdaySettingResponse response) { }
	// RVA: 0x2e7e4a0 VA: 0x75954964a0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```