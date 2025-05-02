# LuaSender

**Namespace:** `Torappu.Lua`


## Fields

- `Int64 m_requestCount`

- `ILuaServiceCallback m_luaCallback`


## Methods

- `String _SendRequest(Options)`

- `String _SendGet(String, String, Boolean)`

- `Void _LuaRequestOnProceed(String, PlayerRawJsonResponse)`

- `Void _LuaGetOnProceed(String, MIMEObject)`

- `Boolean _LuaOnBlock(String, ResponseError)`

- `Void _LuaOnFinal(String)`

- `Void _LuaOnSystemCancel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaSender : Singleton`1
{
	private Int64 m_requestCount; // 0x10
	private ILuaServiceCallback m_luaCallback; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LuaOnlyBindCallback; // 0x8
	private static DelegateBridge __Hotfix0_ResetNetwork; // 0x10
	private static DelegateBridge __Hotfix0_AchieveServiceMeta; // 0x18
	private static DelegateBridge __Hotfix0_SendRequest; // 0x20
	private static DelegateBridge __Hotfix0__SendRequest; // 0x28
	private static DelegateBridge __Hotfix0_SendGet; // 0x30
	private static DelegateBridge __Hotfix0__SendGet; // 0x38
	private static DelegateBridge __Hotfix0__LuaRequestOnProceed; // 0x40
	private static DelegateBridge __Hotfix0__LuaGetOnProceed; // 0x48
	private static DelegateBridge __Hotfix0__LuaOnBlock; // 0x50
	private static DelegateBridge __Hotfix0__LuaOnFinal; // 0x58
	private static DelegateBridge __Hotfix0__LuaOnSystemCancel; // 0x60
	private static DelegateBridge __Hotfix0__ProcessRequestData; // 0x68
	private static DelegateBridge __Hotfix0__ReplaceEmptyObj2Ary; // 0x70
	private static DelegateBridge __Hotfix1__ReplaceEmptyObj2Ary; // 0x78


	// RVA: 0x35b1220 VA: 0x7595bc9220
	private Void .ctor() { }
	// RVA: 0x35b12b8 VA: 0x7595bc92b8
	public static Void LuaOnlyBindCallback(ILuaServiceCallback callback) { }
	// RVA: 0x35b1348 VA: 0x7595bc9348
	public static Void ResetNetwork() { }
	// RVA: 0x35b145c VA: 0x7595bc945c
	public static Void AchieveServiceMeta(String serviceCode, LuaTable body) { }
	// RVA: 0x35b160c VA: 0x7595bc960c
	public static String SendRequest(Options options) { }
	// RVA: 0x35b16d0 VA: 0x7595bc96d0
	private String _SendRequest(Options options) { }
	// RVA: 0x35b1c34 VA: 0x7595bc9c34
	public static String SendGet(String url, String param, Boolean useLoadingMask) { }
	// RVA: 0x35b1ce4 VA: 0x7595bc9ce4
	private String _SendGet(String url, String param, Boolean useLoadingMask) { }
	// RVA: 0x35b1f24 VA: 0x7595bc9f24
	private Void _LuaRequestOnProceed(String id, PlayerRawJsonResponse response) { }
	// RVA: 0x35b2118 VA: 0x7595bca118
	private Void _LuaGetOnProceed(String id, MIMEObject response) { }
	// RVA: 0x35b236c VA: 0x7595bca36c
	private Boolean _LuaOnBlock(String id, ResponseError error) { }
	// RVA: 0x35b25bc VA: 0x7595bca5bc
	private Void _LuaOnFinal(String id) { }
	// RVA: 0x35b27dc VA: 0x7595bca7dc
	private Void _LuaOnSystemCancel(String id) { }
	// RVA: 0x35b1a74 VA: 0x7595bc9a74
	private static String _ProcessRequestData(String rawRequest) { }
	// RVA: 0x35b298c VA: 0x7595bca98c
	private static Void _ReplaceEmptyObj2Ary(JObject root) { }
	// RVA: 0x35b2c9c VA: 0x7595bcac9c
	private static Void _ReplaceEmptyObj2Ary(JArray array) { }
}
```