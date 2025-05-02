# LuaAIRLSampleMgr

**Namespace:** `Torappu.Lua`


## Fields

- `ILuaAIRLSampler m_luaCallback`


## Properties

- `Boolean isCallbackReady`


## Methods

- `Boolean get_isCallbackReady()`

- `String SampleGameData()`

- `Void ResetAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaAIRLSampleMgr : Singleton`1
{
	private ILuaAIRLSampler m_luaCallback; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_isCallbackReady; // 0x8
	private static DelegateBridge __Hotfix0_LuaOnlyBindCallback; // 0x10
	private static DelegateBridge __Hotfix0_GetTimestamp; // 0x18
	private static DelegateBridge __Hotfix0_SampleGameData; // 0x20
	private static DelegateBridge __Hotfix0_ResetAll; // 0x28

	public Boolean isCallbackReady { get; }

	// RVA: 0x35ad66c VA: 0x7595bc566c
	private Void .ctor() { }
	// RVA: 0x35ad6fc VA: 0x7595bc56fc
	public Boolean get_isCallbackReady() { }
	// RVA: 0x35ad76c VA: 0x7595bc576c
	public static Void LuaOnlyBindCallback(ILuaAIRLSampler callback) { }
	// RVA: 0x35ad7fc VA: 0x7595bc57fc
	public static Int64 GetTimestamp() { }
	// RVA: 0x35ad924 VA: 0x7595bc5924
	public String SampleGameData() { }
	// RVA: 0x35ada18 VA: 0x7595bc5a18
	public Void ResetAll() { }
}
```