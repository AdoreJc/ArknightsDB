# CastSkillWithCost

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_requiredCost`


## Properties

- `Int32 requiredCost`


## Methods

- `Int32 get_requiredCost()`

- `Void set_requiredCost(Int32)`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate, PlayerSide)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CastSkillWithCost : CastSkill
{
	private Int32 m_requiredCost; // 0x11c
	private static DelegateBridge __Hotfix0_get_requiredCost; // 0x0
	private static DelegateBridge __Hotfix0_set_requiredCost; // 0x8
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_DoCast; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Int32 requiredCost { get; set; }

	// RVA: 0x40f202c VA: 0x759670a02c
	public Int32 get_requiredCost() { }
	// RVA: 0x40f2094 VA: 0x759670a094
	public Void set_requiredCost(Int32 value) { }
	// RVA: 0x40f2110 VA: 0x759670a110
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x40f21e0 VA: 0x759670a1e0
	public override Void OnInit() { }
	// RVA: 0x40f22e4 VA: 0x759670a2e4
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x40f25b4 VA: 0x759670a5b4
	public Void .ctor() { }
	// RVA: 0x40f2644 VA: 0x759670a644
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x40f2648 VA: 0x759670a648
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40f264c VA: 0x759670a64c
	private Boolean <>xLuaBaseProxy_DoCast(FinishCallbackDelegate P0, PlayerSide P1) { }
}
```