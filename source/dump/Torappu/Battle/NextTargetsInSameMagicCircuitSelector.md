# NextTargetsInSameMagicCircuitSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxTargetNum`

- `Boolean _isBackward`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class NextTargetsInSameMagicCircuitSelector : TargetSelector
{
	private Int32 _maxTargetNum; // 0x30
	private Boolean _isBackward; // 0x34
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x0
	private static DelegateBridge __Hotfix0_FindTiles; // 0x8
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1bb4194 VA: 0x75941cc194
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bb4554 VA: 0x75941cc554
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1bb45d4 VA: 0x75941cc5d4
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bb4650 VA: 0x75941cc650
	public Void .ctor() { }
}
```