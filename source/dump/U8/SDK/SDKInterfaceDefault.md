# SDKInterfaceDefault

**Namespace:** `U8.SDK`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class SDKInterfaceDefault : U8SDKInterface
{


	// RVA: 0x67e4ee8 VA: 0x7598dfcee8
	protected override String LoadExtraConfig() { }
	// RVA: 0x67e4f68 VA: 0x7598dfcf68
	protected override Void V2Init(String env) { }
	// RVA: 0x67e4f74 VA: 0x7598dfcf74
	protected override Void Init() { }
	// RVA: 0x67e5040 VA: 0x7598dfd040
	protected override Void Login() { }
	// RVA: 0x67e5080 VA: 0x7598dfd080
	protected override Void LoginCustom(String customData) { }
	// RVA: 0x67e50c0 VA: 0x7598dfd0c0
	protected override Void SwitchLogin() { }
	// RVA: 0x67e5100 VA: 0x7598dfd100
	protected override Boolean Logout() { }
	// RVA: 0x67e5140 VA: 0x7598dfd140
	public override Boolean ShowAccountCenter() { }
	// RVA: 0x67e5180 VA: 0x7598dfd180
	public override Void SubmitGameData(U8ExtraGameData data) { }
	// RVA: 0x67e5214 VA: 0x7598dfd214
	public override Boolean SDKExit() { }
	// RVA: 0x67e5254 VA: 0x7598dfd254
	protected override Void Pay(U8PayParams data) { }
	// RVA: 0x67e5294 VA: 0x7598dfd294
	public override Boolean IsSupportLogin() { }
	// RVA: 0x67e52d4 VA: 0x7598dfd2d4
	public override Boolean IsSupportExit() { }
	// RVA: 0x67e5314 VA: 0x7598dfd314
	public override Boolean IsSupportAccountCenter() { }
	// RVA: 0x67e5354 VA: 0x7598dfd354
	public override Boolean IsSupportLogout() { }
	// RVA: 0x67e5394 VA: 0x7598dfd394
	public override Void SetData(Int32 type, String paramJson) { }
	// RVA: 0x67e5398 VA: 0x7598dfd398
	public override String GetData(Int32 type, String paramJson) { }
	// RVA: 0x67e53e0 VA: 0x7598dfd3e0
	protected override SDKMeta LoadSDKMeta() { }
	// RVA: 0x67e5420 VA: 0x7598dfd420
	protected override Boolean IsNativePlugin() { }
	// RVA: 0x67e5428 VA: 0x7598dfd428
	public Void .ctor() { }
}
```