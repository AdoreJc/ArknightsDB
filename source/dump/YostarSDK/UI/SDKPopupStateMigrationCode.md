# SDKPopupStateMigrationCode

**Namespace:** `YostarSDK.UI`


## Fields

- `Button _btnCopyId`

- `Button _btnCopyCode`

- `InputField _inputId`

- `InputField _inputCode`

- `Button _btnClose`


## Methods

- `Void EventOnCloseClicked()`

- `Void EventOnCopyIdClicked()`

- `Void EventOnCopyCodeClicked()`

- `Void EventOnGenerateCode()`

- `Void _MigrationCodeCallback(MigrationCodeRet)`

- `Void _UpdateViewStatus()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPopupStateMigrationCode : UIState
{
	private Button _btnCopyId; // 0x50
	private Button _btnCopyCode; // 0x58
	private InputField _inputId; // 0x60
	private InputField _inputCode; // 0x68
	private Button _btnClose; // 0x70
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCopyIdClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCopyCodeClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnGenerateCode; // 0x28
	private static DelegateBridge __Hotfix0__MigrationCodeCallback; // 0x30
	private static DelegateBridge __Hotfix0__UpdateViewStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override PopupState myState { get; }

	// RVA: 0x2578054 VA: 0x7594b90054
	public override PopupState get_myState() { }
	// RVA: 0x25780bc VA: 0x7594b900bc
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x25782e0 VA: 0x7594b902e0
	public Void EventOnCloseClicked() { }
	// RVA: 0x257836c VA: 0x7594b9036c
	public Void EventOnCopyIdClicked() { }
	// RVA: 0x257842c VA: 0x7594b9042c
	public Void EventOnCopyCodeClicked() { }
	// RVA: 0x25784ec VA: 0x7594b904ec
	public Void EventOnGenerateCode() { }
	// RVA: 0x25785fc VA: 0x7594b905fc
	private Void _MigrationCodeCallback(MigrationCodeRet ret) { }
	// RVA: 0x25781e0 VA: 0x7594b901e0
	private Void _UpdateViewStatus() { }
	// RVA: 0x257889c VA: 0x7594b9089c
	public Void .ctor() { }
	// RVA: 0x2578908 VA: 0x7594b90908
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```