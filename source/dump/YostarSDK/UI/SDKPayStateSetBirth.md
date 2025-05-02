# SDKPayStateSetBirth

**Namespace:** `YostarSDK.UI`


## Fields

- `InputField _birthInput`

- `SDKInputWarning _birthInputWarning`


## Methods

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`

- `Void _ConfirmSetBirth()`

- `Void _OnAiriSDKSetBirth(BirthSetRet)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKPayStateSetBirth : UIState
{
	private InputField _birthInput; // 0x50
	private SDKInputWarning _birthInputWarning; // 0x58

	public override PayState myState { get; }

	// RVA: 0x1b4bc84 VA: 0x7594163c84
	public override PayState get_myState() { }
	// RVA: 0x1b4bc8c VA: 0x7594163c8c
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x1b4be34 VA: 0x7594163e34
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b4beb8 VA: 0x7594163eb8
	public Void EventOnConfirmClicked() { }
	// RVA: 0x1b4c52c VA: 0x759416452c
	public Void EventOnCancelClicked() { }
	// RVA: 0x1b4c084 VA: 0x7594164084
	private static Boolean _TryParseBirthDay(String input, out DateTime birthDay) { }
	// RVA: 0x1b4c2f8 VA: 0x75941642f8
	private static Int32 _GetAge(DateTime birthDay) { }
	// RVA: 0x1b4c440 VA: 0x7594164440
	private Void _ConfirmSetBirth() { }
	// RVA: 0x1b4c634 VA: 0x7594164634
	private Void _OnAiriSDKSetBirth(BirthSetRet ret) { }
	// RVA: 0x1b4c8f4 VA: 0x75941648f4
	public Void .ctor() { }
}
```