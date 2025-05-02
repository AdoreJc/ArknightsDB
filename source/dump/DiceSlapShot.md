# DiceSlapShot

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DiceSlapShot : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f5001c VA: 0x759456801c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f50084 VA: 0x7594568084
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f501fc VA: 0x75945681fc
	public Void .ctor() { }
}
```