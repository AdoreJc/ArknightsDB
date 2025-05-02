# ConstructPlaceTrap

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `GridPosition m_pos`

- `Direction m_dir`

- `String m_buildingId`

- `Boolean m_notExecute`


## Methods

- `Void <>xLuaBaseProxy_Execute()`

- `Void <>xLuaBaseProxy_Revert()`

- `JObject <>xLuaBaseProxy_GetDataNullable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class ConstructPlaceTrap : ConstructOp
{
	private GridPosition m_pos; // 0x10
	private Direction m_dir; // 0x18
	private String m_buildingId; // 0x20
	private Boolean m_notExecute; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_Revert; // 0x10
	private static DelegateBridge __Hotfix0_GetDataNullable; // 0x18


	// RVA: 0x1dd7b2c VA: 0x75943efb2c
	public Void .ctor(GridPosition pos, Direction dir, String buildingId, Boolean notExecute) { }
	// RVA: 0x1dd7c00 VA: 0x75943efc00
	public override Void Execute() { }
	// RVA: 0x1dd7cdc VA: 0x75943efcdc
	public override Void Revert() { }
	// RVA: 0x1dd7dec VA: 0x75943efdec
	public override JObject GetDataNullable() { }
	// RVA: 0x1dd8010 VA: 0x75943f0010
	private Void <>xLuaBaseProxy_Execute() { }
	// RVA: 0x1dd8014 VA: 0x75943f0014
	private Void <>xLuaBaseProxy_Revert() { }
	// RVA: 0x1dd8018 VA: 0x75943f0018
	private JObject <>xLuaBaseProxy_GetDataNullable() { }
}
```