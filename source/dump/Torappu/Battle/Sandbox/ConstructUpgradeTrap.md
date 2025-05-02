# ConstructUpgradeTrap

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `String m_buildingId`

- `GridPosition m_pos`

- `Direction m_dir`


## Methods

- `Void _SetMat(Boolean)`

- `Void <>xLuaBaseProxy_Execute()`

- `Void <>xLuaBaseProxy_Revert()`

- `JObject <>xLuaBaseProxy_GetDataNullable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class ConstructUpgradeTrap : ConstructOp
{
	private String m_buildingId; // 0x10
	private ListDict`2 m_costCache; // 0x18
	private GridPosition m_pos; // 0x20
	private Direction m_dir; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_Revert; // 0x10
	private static DelegateBridge __Hotfix0_GetDataNullable; // 0x18
	private static DelegateBridge __Hotfix0__SetMat; // 0x20


	// RVA: 0x1dd8e08 VA: 0x75943f0e08
	public Void .ctor(GridPosition pos) { }
	// RVA: 0x1dd8ee0 VA: 0x75943f0ee0
	public override Void Execute() { }
	// RVA: 0x1dd9410 VA: 0x75943f1410
	public override Void Revert() { }
	// RVA: 0x1dd95c8 VA: 0x75943f15c8
	public override JObject GetDataNullable() { }
	// RVA: 0x1dd9130 VA: 0x75943f1130
	private Void _SetMat(Boolean isRevert) { }
	// RVA: 0x1dd980c VA: 0x75943f180c
	private Void <>xLuaBaseProxy_Execute() { }
	// RVA: 0x1dd9810 VA: 0x75943f1810
	private Void <>xLuaBaseProxy_Revert() { }
	// RVA: 0x1dd9814 VA: 0x75943f1814
	private JObject <>xLuaBaseProxy_GetDataNullable() { }
}
```