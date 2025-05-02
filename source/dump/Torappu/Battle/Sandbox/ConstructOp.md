# ConstructOp

**Namespace:** `Torappu.Battle.Sandbox`


## Properties

- `SandboxV2Data dataTable`


## Methods

- `SandboxV2Data get_dataTable()`

- `Void ApplyGoldCost(Character, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class ConstructOp : IConstructOp, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_dataTable; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_Revert; // 0x10
	private static DelegateBridge __Hotfix0_GetDataNullable; // 0x18
	private static DelegateBridge __Hotfix0_ApplyGoldCost; // 0x20
	private static DelegateBridge __Hotfix0_SetHp; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected SandboxV2Data dataTable { get; }

	// RVA: 0x1dd747c VA: 0x75943ef47c
	protected SandboxV2Data get_dataTable() { }
	// RVA: 0x1dd7514 VA: 0x75943ef514
	public virtual Void Execute() { }
	// RVA: 0x1dd7578 VA: 0x75943ef578
	public virtual Void Revert() { }
	// RVA: 0x1dd75dc VA: 0x75943ef5dc
	public virtual JObject GetDataNullable() { }
	// RVA: 0x1dd7640 VA: 0x75943ef640
	protected Void ApplyGoldCost(Character character, Int32 discount, Boolean isRevert) { }
	// RVA: 0x1dd77e8 VA: 0x75943ef7e8
	public static Void SetHp(Unit character, FP targetHPRatio) { }
	// RVA: 0x1dd795c VA: 0x75943ef95c
	public Void .ctor() { }
}
```