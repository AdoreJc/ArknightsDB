# FinishSpecifiedTileHoldingEffect

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _effectKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishSpecifiedTileHoldingEffect : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _effectKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe4640 VA: 0x75945fc640
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe46a8 VA: 0x75945fc6a8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe47f4 VA: 0x75945fc7f4
	public Void .ctor() { }
}
```