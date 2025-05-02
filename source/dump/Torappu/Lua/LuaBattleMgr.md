# LuaBattleMgr

**Namespace:** `Torappu.Lua`


## Fields

- `ILuaServiceCallback m_luaCallback`


## Properties

- `Boolean isCallbackReady`


## Methods

- `Boolean get_isCallbackReady()`

- `Void ResetAll()`

- `Boolean RunActions(String, Blackboard, SourceType, ref)`

- `LuaBinding CreateAbilityBehaviour(LuaAbilityBehaviourStub)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaBattleMgr : Singleton`1
{
	private ILuaServiceCallback m_luaCallback; // 0x10
	private static DelegateBridge __Hotfix0_get_isCallbackReady; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_LuaOnlyBindCallback; // 0x10
	private static DelegateBridge __Hotfix0_ResetAll; // 0x18
	private static DelegateBridge __Hotfix0_RunActions; // 0x20
	private static DelegateBridge __Hotfix0_CreateAbilityBehaviour; // 0x28

	private Boolean isCallbackReady { get; }

	// RVA: 0x35adb0c VA: 0x7595bc5b0c
	private Boolean get_isCallbackReady() { }
	// RVA: 0x35adbb0 VA: 0x7595bc5bb0
	private Void .ctor() { }
	// RVA: 0x35adc40 VA: 0x7595bc5c40
	public static Void LuaOnlyBindCallback(ILuaServiceCallback callback) { }
	// RVA: 0x35add14 VA: 0x7595bc5d14
	public Void ResetAll() { }
	// RVA: 0x35adeb8 VA: 0x7595bc5eb8
	public Boolean RunActions(String actionName, Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x35ae0e8 VA: 0x7595bc60e8
	public LuaBinding CreateAbilityBehaviour(LuaAbilityBehaviourStub wrapper) { }
}
```