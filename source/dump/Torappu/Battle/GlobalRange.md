# GlobalRange

**Namespace:** `Torappu.Battle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GlobalRange : Range
{
	private static DelegateBridge __Hotfix0_get_extendable; // 0x0
	private static DelegateBridge __Hotfix0_set_extendable; // 0x8
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x10
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x18
	private static DelegateBridge __Hotfix0_FindTiles; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_UpdateExtend; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Boolean extendable { get; set; }

	// RVA: 0x1b90e74 VA: 0x75941a8e74
	public override Boolean get_extendable() { }
	// RVA: 0x1b90ed8 VA: 0x75941a8ed8
	public override Void set_extendable(Boolean value) { }
	// RVA: 0x1b90f50 VA: 0x75941a8f50
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b90fcc VA: 0x75941a8fcc
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b91298 VA: 0x75941a9298
	public override List`1 FindTiles(Vector2 mapPos, Func`2 validator) { }
	// RVA: 0x1b914a8 VA: 0x75941a94a8
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b9152c VA: 0x75941a952c
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b915ac VA: 0x75941a95ac
	public Void .ctor() { }
}
```