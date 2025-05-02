# TorappuLuaLuaSenderILuaServiceCallbackBridge

**Namespace:** `XLua.CSObjectWrap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua.CSObjectWrap
public class TorappuLuaLuaSenderILuaServiceCallbackBridge : LuaBase, ILuaServiceCallback
{


	// RVA: 0x239c2a0 VA: 0x75949b42a0
	public static LuaBase __Create(Int32 reference, LuaEnv luaenv) { }
	// RVA: 0x239c314 VA: 0x75949b4314
	public Void .ctor(Int32 reference, LuaEnv luaenv) { }
	// RVA: 0x239c31c VA: 0x75949b431c
	private Void Torappu.Lua.LuaSender.ILuaServiceCallback.ExportOnProceed(String requestId, LuaTable response) { }
	// RVA: 0x239c5e8 VA: 0x75949b45e8
	private Boolean Torappu.Lua.LuaSender.ILuaServiceCallback.ExportOnBlock(String requestId, LuaRespError error) { }
	// RVA: 0x239c8f0 VA: 0x75949b48f0
	private Void Torappu.Lua.LuaSender.ILuaServiceCallback.ExportOnFinal(String requestId) { }
	// RVA: 0x239cb7c VA: 0x75949b4b7c
	private Void Torappu.Lua.LuaSender.ILuaServiceCallback.ExportRemoveRequest(String requestId) { }
	// RVA: 0x239ce08 VA: 0x75949b4e08
	private Void Torappu.Lua.LuaSender.ILuaServiceCallback.ExportResetNetwork() { }
}
```