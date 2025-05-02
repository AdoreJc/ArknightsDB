# NameCardV2EditResumeDialog

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UIRenderTextureImage _blurImg`

- `InputField _input`

- `Button _btnConfirm`

- `Button _btnCancel`


## Methods

- `Void _OnConfirmClicked()`

- `Void _OnCancelClicked()`

- `Void <_OnConfirmClicked>b__8_0()`

- `Void <_OnConfirmClicked>b__8_1(ChangeResumeResponse)`

- `Void <_OnConfirmClicked>b__8_2()`

- `Void <_OnConfirmClicked>b__8_3()`

- `Void <_OnCancelClicked>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2EditResumeDialog : UICustomDialog`1
{
	private UIRenderTextureImage _blurImg; // 0x40
	private InputField _input; // 0x48
	private Button _btnConfirm; // 0x50
	private Button _btnCancel; // 0x58
	private Action`1 m_callback; // 0x60
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_DefaultShowTweenDuration; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0__OnConfirmClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnCancelClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x28da7f8 VA: 0x7594ef27f8
	protected override Void OnRender(Action`1 callback) { }
	// RVA: 0x28daac8 VA: 0x7594ef2ac8
	protected override Single DefaultShowTweenDuration() { }
	// RVA: 0x28dab34 VA: 0x7594ef2b34
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x28dab9c VA: 0x7594ef2b9c
	private Void _OnConfirmClicked() { }
	// RVA: 0x28dae90 VA: 0x7594ef2e90
	private Void _OnCancelClicked() { }
	// RVA: 0x28daf74 VA: 0x7594ef2f74
	public Void .ctor() { }
	// RVA: 0x28db004 VA: 0x7594ef3004
	private Void <_OnConfirmClicked>b__8_0() { }
	// RVA: 0x28db050 VA: 0x7594ef3050
	private Void <_OnConfirmClicked>b__8_1(ChangeResumeResponse response) { }
	// RVA: 0x28db0e0 VA: 0x7594ef30e0
	private Void <_OnConfirmClicked>b__8_2() { }
	// RVA: 0x28db178 VA: 0x7594ef3178
	private Void <_OnConfirmClicked>b__8_3() { }
	// RVA: 0x28db1c4 VA: 0x7594ef31c4
	private Void <_OnCancelClicked>b__9_0() { }
}
```