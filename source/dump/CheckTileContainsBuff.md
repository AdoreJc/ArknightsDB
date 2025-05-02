# CheckTileContainsBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _tileEffectKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTileContainsBuff : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _tileEffectKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1cfd0 VA: 0x7594534fd0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1d038 VA: 0x7594535038
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1d1bc VA: 0x75945351bc
	public Void .ctor() { }
}
```