# SDKUnbindConfirmState

**Namespace:** `HGSDK.UI`


## Fields

- `Text _textInfo`


## Methods

- `Void _EventOnCloseClicked()`

- `Void _EventOnBackClicked()`

- `Void _OnUnbindGrantSuc(APIV2RespWrapper`1)`

- `Void _OnUnbindGrantFail(APIV2FailResponse)`

- `Void EventOnConfirmClicked()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKUnbindConfirmState : UIState
{
	private Text _textInfo; // 0x50
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetFloatV2Handler; // 0x10
	private static DelegateBridge __Hotfix0__EventOnCloseClicked; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBackClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnUnbindGrantSuc; // 0x28
	private static DelegateBridge __Hotfix0__OnUnbindGrantFail; // 0x30
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override PopupState myState { get; }

	// RVA: 0x3561da4 VA: 0x7595b79da4
	public override PopupState get_myState() { }
	// RVA: 0x3561e0c VA: 0x7595b79e0c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3561eb8 VA: 0x7595b79eb8
	public override FloatV2Handler GetFloatV2Handler() { }
	// RVA: 0x3562020 VA: 0x7595b7a020
	private Void _EventOnCloseClicked() { }
	// RVA: 0x3562094 VA: 0x7595b7a094
	private Void _EventOnBackClicked() { }
	// RVA: 0x356213c VA: 0x7595b7a13c
	private Void _OnUnbindGrantSuc(APIV2RespWrapper`1 response) { }
	// RVA: 0x3562268 VA: 0x7595b7a268
	private Void _OnUnbindGrantFail(APIV2FailResponse response) { }
	// RVA: 0x35623e0 VA: 0x7595b7a3e0
	public Void EventOnConfirmClicked() { }
	// RVA: 0x35625e4 VA: 0x7595b7a5e4
	public Void .ctor() { }
	// RVA: 0x3562650 VA: 0x7595b7a650
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3562654 VA: 0x7595b7a654
	private FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler() { }
}
```