# EmptyRange

**Namespace:** `Torappu.Battle`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EmptyRange : Range
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

	// RVA: 0x1b901ec VA: 0x75941a81ec
	public override Boolean get_extendable() { }
	// RVA: 0x1b90250 VA: 0x75941a8250
	public override Void set_extendable(Boolean value) { }
	// RVA: 0x1b902c8 VA: 0x75941a82c8
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b90340 VA: 0x75941a8340
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b903f0 VA: 0x75941a83f0
	public override List`1 FindTiles(Vector2 mapPos, Func`2 validator) { }
	// RVA: 0x1b90484 VA: 0x75941a8484
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b90508 VA: 0x75941a8508
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b90588 VA: 0x75941a8588
	public Void .ctor() { }
}
```