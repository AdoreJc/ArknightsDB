# HGSDKPluginV2Mock

**Namespace:** `HGSDK.V2`


## Methods

- `IEnumerator _MockLoginCoroutine(ExternalPluginLoginParams)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.V2
public class HGSDKPluginV2Mock : HGSDKPluginV2
{


	// RVA: 0x2f2cdd8 VA: 0x7595544dd8
	public Void .ctor(HGSDKV2 sdk) { }
	// RVA: 0x2f2ce60 VA: 0x7595544e60
	public override Void Login(ExternalPluginLoginParams args) { }
	// RVA: 0x2f2cf84 VA: 0x7595544f84
	public override Void Logout(ExternalPluginLogoutParams args) { }
	// RVA: 0x2f2cf9c VA: 0x7595544f9c
	public override Void Pay(ExternalPluginPayParams args) { }
	// RVA: 0x2f2cee4 VA: 0x7595544ee4
	private IEnumerator _MockLoginCoroutine(ExternalPluginLoginParams args) { }
	// RVA: 0x2f2cfd8 VA: 0x7595544fd8
	public static Void MockPayImpl(ExternalPluginPayParams args) { }
}
```