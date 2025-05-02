# SDKPopupStateWealth

**Namespace:** `YostarSDK.UI`


## Fields

- `Text _textTitle`

- `Text _titleTotal`

- `Text _countTotal`

- `Text _titleFree`

- `Text _countFree`

- `Text _titlePaid`

- `Text _countPaid`

- `Text _textDesc`

- `Button _btnClose`


## Methods

- `Void EventOnCloseClicked()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPopupStateWealth : UIState
{
	private Text _textTitle; // 0x50
	private Text _titleTotal; // 0x58
	private Text _countTotal; // 0x60
	private Text _titleFree; // 0x68
	private Text _countFree; // 0x70
	private Text _titlePaid; // 0x78
	private Text _countPaid; // 0x80
	private Text _textDesc; // 0x88
	private Button _btnClose; // 0x90
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PopupState myState { get; }

	// RVA: 0x257a810 VA: 0x7594b92810
	public override PopupState get_myState() { }
	// RVA: 0x257a878 VA: 0x7594b92878
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x257aba0 VA: 0x7594b92ba0
	public Void EventOnCloseClicked() { }
	// RVA: 0x257ac2c VA: 0x7594b92c2c
	public Void .ctor() { }
	// RVA: 0x257ac98 VA: 0x7594b92c98
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```