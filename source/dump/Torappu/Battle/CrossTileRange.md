# CrossTileRange

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _skipAdvancedValidateWithCondition`

- `String _conditionBuffKey`


## Properties

- `Boolean skipAdvancedValidateWithCondition`


## Methods

- `Boolean get_skipAdvancedValidateWithCondition()`

- `Boolean _VerifyTargetInternal(Entity, ReusableList`1, TargetOptions, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CrossTileRange : Range
{
	private Boolean _skipAdvancedValidateWithCondition; // 0x20
	private String _conditionBuffKey; // 0x28
	private static DelegateBridge __Hotfix0_get_extendable; // 0x0
	private static DelegateBridge __Hotfix0_set_extendable; // 0x8
	private static DelegateBridge __Hotfix0_get_skipAdvancedValidateWithCondition; // 0x10
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x18
	private static DelegateBridge __Hotfix0_FindTiles; // 0x20
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_UpdateExtend; // 0x38
	private static DelegateBridge __Hotfix0__VerifyTargetInternal; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override Boolean extendable { get; set; }
	public Boolean skipAdvancedValidateWithCondition { get; }

	// RVA: 0x1b8edc8 VA: 0x75941a6dc8
	public override Boolean get_extendable() { }
	// RVA: 0x1b8ee2c VA: 0x75941a6e2c
	public override Void set_extendable(Boolean value) { }
	// RVA: 0x1b8eea4 VA: 0x75941a6ea4
	public Boolean get_skipAdvancedValidateWithCondition() { }
	// RVA: 0x1b8ef0c VA: 0x75941a6f0c
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b8f118 VA: 0x75941a7118
	public override List`1 FindTiles(Vector2 mapPos, Func`2 validator) { }
	// RVA: 0x1b8f584 VA: 0x75941a7584
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b8ff98 VA: 0x75941a7f98
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b9001c VA: 0x75941a801c
	protected override Void UpdateExtend(FP extend, Boolean force) { }
	// RVA: 0x1b8fdd4 VA: 0x75941a7dd4
	private Boolean _VerifyTargetInternal(Entity unit, ReusableList`1 candidates, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b9009c VA: 0x75941a809c
	public Void .ctor() { }
}
```