# HGWebAdapter

**Namespace:** ` `


## Fields

- `Core m_context`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HGWebAdapter : Adapter, IHotfixable
{
	private Core m_context; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetSDKEnv; // 0x8
	private static DelegateBridge __Hotfix0_JSONToCallbackRet; // 0x10
	private static DelegateBridge __Hotfix0_UserDataToJSON; // 0x18
	private static DelegateBridge __Hotfix0_UrlParamsToJson; // 0x20
	private static DelegateBridge __Hotfix0_CustomStyleToJson; // 0x28
	private static DelegateBridge __Hotfix0_OnExtraInfo; // 0x30
	private static DelegateBridge __Hotfix0_OnManagerInitFinished; // 0x38


	// RVA: 0x2207324 VA: 0x759481f324
	public Void .ctor(Core context) { }
	// RVA: 0x2207454 VA: 0x759481f454
	public override String GetSDKEnv() { }
	// RVA: 0x22074b8 VA: 0x759481f4b8
	public override CallbackRet JSONToCallbackRet(String jsonStr) { }
	// RVA: 0x22075d0 VA: 0x759481f5d0
	public override String UserDataToJSON(UserData userData) { }
	// RVA: 0x22076b8 VA: 0x759481f6b8
	public override String UrlParamsToJson(UrlParams urlParams) { }
	// RVA: 0x22077a8 VA: 0x759481f7a8
	public override String CustomStyleToJson(MiniWebCustomStyle customStyle) { }
	// RVA: 0x2207898 VA: 0x759481f898
	public override Void OnExtraInfo(CallbackCode code, CallbackMsg msg) { }
	// RVA: 0x2207a58 VA: 0x759481fa58
	public override Void OnManagerInitFinished() { }
}
```