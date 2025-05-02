# MultiAppearSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_pendingToCast`


## Methods

- `Void SetPendingToCast()`

- `Void _StopSkill()`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnBorn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MultiAppearSkill : AppearSkill
{
	private Boolean m_pendingToCast; // 0x104
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_SetPendingToCast; // 0x10
	private static DelegateBridge __Hotfix0_OnBorn; // 0x18
	private static DelegateBridge __Hotfix0__StopSkill; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b6ffd0 VA: 0x7594187fd0
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x1b70070 VA: 0x7594188070
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x1b70248 VA: 0x7594188248
	public Void SetPendingToCast() { }
	// RVA: 0x1b702b4 VA: 0x75941882b4
	public override Void OnBorn() { }
	// RVA: 0x1b701b0 VA: 0x75941881b0
	private Void _StopSkill() { }
	// RVA: 0x1b70328 VA: 0x7594188328
	public Void .ctor() { }
	// RVA: 0x1b70398 VA: 0x7594188398
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x1b703a0 VA: 0x75941883a0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1b703a8 VA: 0x75941883a8
	private Void <>xLuaBaseProxy_OnBorn() { }
}
```