# SDKLoginStateInit

**Namespace:** `YostarSDK.UI`


## Methods

- `Void _BeginInit()`

- `Void _OnInitSuccess()`

- `Void _OnAiriSDKInit(InitRet)`

- `Void _OnAiriSDKInitFailed(InitRet)`

- `Void <_OnAiriSDKInitFailed>b__6_0()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKLoginStateInit : UIState
{
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__BeginInit; // 0x10
	private static DelegateBridge __Hotfix0__OnInitSuccess; // 0x18
	private static DelegateBridge __Hotfix0__OnAiriSDKInit; // 0x20
	private static DelegateBridge __Hotfix0__OnAiriSDKInitFailed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override LoginState myState { get; }

	// RVA: 0x1b45fec VA: 0x759415dfec
	public override LoginState get_myState() { }
	// RVA: 0x1b46054 VA: 0x759415e054
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b460dc VA: 0x759415e0dc
	private Void _BeginInit() { }
	// RVA: 0x1b461c0 VA: 0x759415e1c0
	private Void _OnInitSuccess() { }
	// RVA: 0x1b462d4 VA: 0x759415e2d4
	private Void _OnAiriSDKInit(InitRet ret) { }
	// RVA: 0x1b46454 VA: 0x759415e454
	private Void _OnAiriSDKInitFailed(InitRet ret) { }
	// RVA: 0x1b4659c VA: 0x759415e59c
	public Void .ctor() { }
	// RVA: 0x1b46608 VA: 0x759415e608
	private Void <_OnAiriSDKInitFailed>b__6_0() { }
	// RVA: 0x1b4660c VA: 0x759415e60c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```