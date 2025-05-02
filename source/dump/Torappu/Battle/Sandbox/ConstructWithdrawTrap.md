# ConstructWithdrawTrap

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `GridPosition m_pos`

- `Direction m_dir`

- `String m_buildingId`

- `FP m_cachedHpRatio`


## Methods

- `Void _SetMat(FP, Boolean)`

- `Void <>xLuaBaseProxy_Execute()`

- `Void <>xLuaBaseProxy_Revert()`

- `JObject <>xLuaBaseProxy_GetDataNullable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class ConstructWithdrawTrap : ConstructOp
{
	private GridPosition m_pos; // 0x10
	private Direction m_dir; // 0x18
	private String m_buildingId; // 0x20
	private FP m_cachedHpRatio; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_Revert; // 0x10
	private static DelegateBridge __Hotfix0_GetDataNullable; // 0x18
	private static DelegateBridge __Hotfix0__SetMat; // 0x20


	// RVA: 0x1dd85dc VA: 0x75943f05dc
	public Void .ctor(Character character) { }
	// RVA: 0x1dd866c VA: 0x75943f066c
	public override Void Execute() { }
	// RVA: 0x1dd8b6c VA: 0x75943f0b6c
	public override Void Revert() { }
	// RVA: 0x1dd8c4c VA: 0x75943f0c4c
	public override JObject GetDataNullable() { }
	// RVA: 0x1dd8814 VA: 0x75943f0814
	private Void _SetMat(FP hpRatio, Boolean isRevert) { }
	// RVA: 0x1dd8dfc VA: 0x75943f0dfc
	private Void <>xLuaBaseProxy_Execute() { }
	// RVA: 0x1dd8e00 VA: 0x75943f0e00
	private Void <>xLuaBaseProxy_Revert() { }
	// RVA: 0x1dd8e04 VA: 0x75943f0e04
	private JObject <>xLuaBaseProxy_GetDataNullable() { }
}
```