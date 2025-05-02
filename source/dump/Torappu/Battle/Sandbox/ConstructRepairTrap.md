# ConstructRepairTrap

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `FP m_cachedHpRatio`

- `FP m_hpRatio`

- `GridPosition m_pos`

- `Int32 m_discount`

- `Boolean m_isBaseBuilding`

- `Boolean m_isPortBuilding`


## Methods

- `Void <>xLuaBaseProxy_Execute()`

- `Void <>xLuaBaseProxy_Revert()`

- `JObject <>xLuaBaseProxy_GetDataNullable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class ConstructRepairTrap : ConstructOp
{
	private FP m_cachedHpRatio; // 0x10
	private FP m_hpRatio; // 0x18
	private GridPosition m_pos; // 0x20
	private Int32 m_discount; // 0x28
	private Boolean m_isBaseBuilding; // 0x2c
	private Boolean m_isPortBuilding; // 0x2d
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_Revert; // 0x10
	private static DelegateBridge __Hotfix0_GetDataNullable; // 0x18


	// RVA: 0x1dd801c VA: 0x75943f001c
	public Void .ctor(GridPosition pos, Int32 discount) { }
	// RVA: 0x1dd80ac VA: 0x75943f00ac
	public override Void Execute() { }
	// RVA: 0x1dd8288 VA: 0x75943f0288
	public override Void Revert() { }
	// RVA: 0x1dd8420 VA: 0x75943f0420
	public override JObject GetDataNullable() { }
	// RVA: 0x1dd85d0 VA: 0x75943f05d0
	private Void <>xLuaBaseProxy_Execute() { }
	// RVA: 0x1dd85d4 VA: 0x75943f05d4
	private Void <>xLuaBaseProxy_Revert() { }
	// RVA: 0x1dd85d8 VA: 0x75943f05d8
	private JObject <>xLuaBaseProxy_GetDataNullable() { }
}
```