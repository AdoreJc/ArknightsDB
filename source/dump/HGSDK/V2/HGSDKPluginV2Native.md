# HGSDKPluginV2Native

**Namespace:** `HGSDK.V2`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.V2
public class HGSDKPluginV2Native : HGSDKPluginV2, IHotfixable
{
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Login; // 0x8
	private static DelegateBridge __Hotfix0__UpdateLastUsedUserName; // 0x10
	private static DelegateBridge __Hotfix0_Logout; // 0x18
	private static DelegateBridge __Hotfix0_Pay; // 0x20
	private static DelegateBridge __Hotfix0__TestOnlyMockPay; // 0x28


	// RVA: 0x2f2cddc VA: 0x7595544ddc
	public Void .ctor(HGSDKV2 sdk) { }
	// RVA: 0x2f2da00 VA: 0x7595545a00
	public override Void Login(ExternalPluginLoginParams args) { }
	// RVA: 0x2f2deac VA: 0x7595545eac
	private static Void _UpdateLastUsedUserName(String currentName, HGSDKV2 sdk) { }
	// RVA: 0x2f2e15c VA: 0x759554615c
	public override Void Logout(ExternalPluginLogoutParams args) { }
	// RVA: 0x2f2e220 VA: 0x7595546220
	public override Void Pay(ExternalPluginPayParams args) { }
	// RVA: 0x2f2e3f0 VA: 0x75955463f0
	private static Void _TestOnlyMockPay(ExternalPluginPayParams args, ref Boolean isMockPay) { }
}
```