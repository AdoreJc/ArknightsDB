# ConstructRepairAllTrap

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Int32 m_discount`


## Methods

- `Void <>xLuaBaseProxy_Execute()`

- `Void <>xLuaBaseProxy_Revert()`

- `JObject <>xLuaBaseProxy_GetDataNullable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class ConstructRepairAllTrap : ConstructOp
{
	private ListDict`2 m_cachedHpRatio; // 0x10
	private Int32 m_discount; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_Revert; // 0x10
	private static DelegateBridge __Hotfix0_GetDataNullable; // 0x18


	// RVA: 0x1dd9818 VA: 0x75943f1818
	public Void .ctor(Int32 discount) { }
	// RVA: 0x1dd98f0 VA: 0x75943f18f0
	public override Void Execute() { }
	// RVA: 0x1dd9b34 VA: 0x75943f1b34
	public override Void Revert() { }
	// RVA: 0x1dd9d38 VA: 0x75943f1d38
	public override JObject GetDataNullable() { }
	// RVA: 0x1dd9e28 VA: 0x75943f1e28
	private Void <>xLuaBaseProxy_Execute() { }
	// RVA: 0x1dd9e2c VA: 0x75943f1e2c
	private Void <>xLuaBaseProxy_Revert() { }
	// RVA: 0x1dd9e30 VA: 0x75943f1e30
	private JObject <>xLuaBaseProxy_GetDataNullable() { }
}
```