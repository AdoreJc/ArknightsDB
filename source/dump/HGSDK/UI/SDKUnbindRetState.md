# SDKUnbindRetState

**Namespace:** `HGSDK.UI`


## Fields

- `Text _text`

- `Boolean m_isViewConfirmed`


## Methods

- `Void _OnViewConfirmed()`

- `Void EventOnConfirmClicked()`

- `FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKUnbindRetState : UIState
{
	private Text _text; // 0x50
	private Boolean m_isViewConfirmed; // 0x58
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_GetFloatV2Handler; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__OnViewConfirmed; // 0x18
	private static DelegateBridge __Hotfix0__GetUnbindRecoverNoticeStr; // 0x20
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override PopupState myState { get; }

	// RVA: 0x3563e1c VA: 0x7595b7be1c
	public override PopupState get_myState() { }
	// RVA: 0x3563e84 VA: 0x7595b7be84
	public override FloatV2Handler GetFloatV2Handler() { }
	// RVA: 0x3563fa8 VA: 0x7595b7bfa8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x35643d0 VA: 0x7595b7c3d0
	private Void _OnViewConfirmed() { }
	// RVA: 0x35640b0 VA: 0x7595b7c0b0
	private static String _GetUnbindRecoverNoticeStr(Int64 deleteCommitTs) { }
	// RVA: 0x3564460 VA: 0x7595b7c460
	public Void EventOnConfirmClicked() { }
	// RVA: 0x35644c8 VA: 0x7595b7c4c8
	public Void .ctor() { }
	// RVA: 0x3564534 VA: 0x7595b7c534
	private FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler() { }
	// RVA: 0x3564564 VA: 0x7595b7c564
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```