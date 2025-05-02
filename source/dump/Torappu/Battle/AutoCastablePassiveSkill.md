# AutoCastablePassiveSkill

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AutoCastablePassiveSkill : CastSkill
{
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x40e9838 VA: 0x7596701838
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x40e9bf0 VA: 0x7596701bf0
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x40e9e84 VA: 0x7596701e84
	public Void .ctor() { }
	// RVA: 0x40e9fa4 VA: 0x7596701fa4
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x40ea0a4 VA: 0x75967020a4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```