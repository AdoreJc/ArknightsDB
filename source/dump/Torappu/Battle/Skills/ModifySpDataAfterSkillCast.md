# ModifySpDataAfterSkillCast

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `Int32 _spCost`

- `Boolean _modifySpType`

- `SpType _spType`

- `Boolean _resetWhenSkillEnd`

- `Int32 m_originSpCost`

- `Int32 m_spCost`


## Properties

- `Boolean modifySpType`


## Methods

- `Boolean get_modifySpType()`

- `Void _ModifySpData(Int32)`

- `Void <>xLuaBaseProxy_AssignData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastSucceed()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`

- `Void <>xLuaBaseProxy_OnOwnerFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class ModifySpDataAfterSkillCast : Behaviour
{
	private Int32 _spCost; // 0x20
	private Boolean _modifySpType; // 0x24
	private SpType _spType; // 0x28
	private Boolean _resetWhenSkillEnd; // 0x2c
	private Int32 m_originSpCost; // 0x30
	private Int32 m_spCost; // 0x34
	private static DelegateBridge __Hotfix0_get_modifySpType; // 0x0
	private static DelegateBridge __Hotfix0_AssignData; // 0x8
	private static DelegateBridge __Hotfix0_OnCastSucceed; // 0x10
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x18
	private static DelegateBridge __Hotfix0_OnOwnerFinish; // 0x20
	private static DelegateBridge __Hotfix0__ModifySpData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Boolean modifySpType { get; }

	// RVA: 0x1d32ddc VA: 0x759434addc
	private Boolean get_modifySpType() { }
	// RVA: 0x1d32e44 VA: 0x759434ae44
	public override Void AssignData(Blackboard blackboard) { }
	// RVA: 0x1d32f04 VA: 0x759434af04
	public override Void OnCastSucceed() { }
	// RVA: 0x1d3314c VA: 0x759434b14c
	public override Void OnSkillEnd() { }
	// RVA: 0x1d331d8 VA: 0x759434b1d8
	public override Void OnOwnerFinish() { }
	// RVA: 0x1d32f9c VA: 0x759434af9c
	private Void _ModifySpData(Int32 spCost) { }
	// RVA: 0x1d33260 VA: 0x759434b260
	public Void .ctor() { }
	// RVA: 0x1d332d8 VA: 0x759434b2d8
	private Void <>xLuaBaseProxy_AssignData(Blackboard P0) { }
	// RVA: 0x1d332e0 VA: 0x759434b2e0
	private Void <>xLuaBaseProxy_OnCastSucceed() { }
	// RVA: 0x1d332e8 VA: 0x759434b2e8
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
	// RVA: 0x1d332f0 VA: 0x759434b2f0
	private Void <>xLuaBaseProxy_OnOwnerFinish() { }
}
```