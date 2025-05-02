# HGSDKRouter

**Namespace:** `HGSDK`


## Fields

- `HGSDK _sdkV1`

- `HGSDKV2 _sdkV2`


## Methods

- `ISDKBase GetSDKInst()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class HGSDKRouter : MonoBehaviour, ISDKRouter, IHotfixable
{
	private HGSDK _sdkV1; // 0x18
	private HGSDKV2 _sdkV2; // 0x20
	private static DelegateBridge __Hotfix0_GetSDKInst; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2f2c894 VA: 0x7595544894
	public ISDKBase GetSDKInst() { }
	// RVA: 0x2f2c8fc VA: 0x75955448fc
	public Void .ctor() { }
}
```