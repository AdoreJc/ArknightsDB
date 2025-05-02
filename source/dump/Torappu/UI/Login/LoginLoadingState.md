# LoginLoadingState

**Namespace:** `Torappu.UI.Login`


## Fields

- `UnityEvent _onCompleted`

- `UITextSlider _leftSlider`

- `UITextSlider _rightSlider`


## Methods

- `IEnumerator _DoTrackProgress()`

- `Void _OnAlmostCompleted()`

- `Void _OnCompleted()`

- `Void _OnFailed()`

- `Void _SetProgress(Single)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Login
public class LoginLoadingState : State
{
	private const Single COMPLETED_HOLD_ON_TIME; // 0x0
	private const Single LOADING_PROG_SPEED; // 0x0
	private UnityEvent _onCompleted; // 0x50
	private UITextSlider _leftSlider; // 0x58
	private UITextSlider _rightSlider; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__DoTrackProgress; // 0x18
	private static DelegateBridge __Hotfix0__OnAlmostCompleted; // 0x20
	private static DelegateBridge __Hotfix0__OnCompleted; // 0x28
	private static DelegateBridge __Hotfix0__OnFailed; // 0x30
	private static DelegateBridge __Hotfix0__SetProgress; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x27b0918 VA: 0x7594dc8918
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27b097c VA: 0x7594dc897c
	protected override Void OnEnter() { }
	// RVA: 0x27b0a24 VA: 0x7594dc8a24
	protected override Void OnResume() { }
	// RVA: 0x27b0aa8 VA: 0x7594dc8aa8
	private IEnumerator _DoTrackProgress() { }
	// RVA: 0x27b0b7c VA: 0x7594dc8b7c
	private Void _OnAlmostCompleted() { }
	// RVA: 0x27b0be0 VA: 0x7594dc8be0
	private Void _OnCompleted() { }
	// RVA: 0x27b0c5c VA: 0x7594dc8c5c
	private Void _OnFailed() { }
	// RVA: 0x27b0cdc VA: 0x7594dc8cdc
	private Void _SetProgress(Single progress) { }
	// RVA: 0x27b0d7c VA: 0x7594dc8d7c
	public Void .ctor() { }
	// RVA: 0x27b0dec VA: 0x7594dc8dec
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27b0df4 VA: 0x7594dc8df4
	private Void <>xLuaBaseProxy_OnResume() { }
}
```