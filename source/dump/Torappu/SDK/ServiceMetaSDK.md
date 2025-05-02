# ServiceMetaSDK

**Namespace:** `Torappu.SDK`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.SDK
public class ServiceMetaSDK : IHotfixable
{
	private const String KEY_ANTI_DATA; // 0x0
	private const String KEY_DATA1; // 0x0
	private const String KEY_DATA2; // 0x0
	private const String KEY_DATA4; // 0x0
	private static ServiceAntiDataSDK s_antiDataSDK; // 0x0
	private static readonly HashSet`1 s_antiDataServices; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_InitOrReset; // 0x10
	private static __XLua_Gen_Delegate127 __Hotfix0_AchieveServiceMetaAsJObject; // 0x18
	private static __XLua_Gen_Delegate1 __Hotfix0_MarkServiceSucceed; // 0x20
	private static __XLua_Gen_Delegate89 __Hotfix0__EncodeBytes; // 0x28
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x30


	// RVA: 0x67902c8 VA: 0x7598da82c8
	public static Void InitOrReset(List`1 antiDataServices) { }
	// RVA: 0x67907e0 VA: 0x7598da87e0
	public static JObject AchieveServiceMetaAsJObject(String serviceCode) { }
	// RVA: 0x6790d88 VA: 0x7598da8d88
	public static Void MarkServiceSucceed(String serviceCode) { }
	// RVA: 0x6790f08 VA: 0x7598da8f08
	private static String _EncodeBytes(Byte[] data) { }
	// RVA: 0x6790fec VA: 0x7598da8fec
	public Void .ctor() { }
	// RVA: 0x6791074 VA: 0x7598da9074
	private static Void .cctor() { }
}
```