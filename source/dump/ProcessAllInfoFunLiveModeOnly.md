# ProcessAllInfoFunLiveModeOnly

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ProcessAllInfoFunLiveModeOnly : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f522a8 VA: 0x759456a2a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f52310 VA: 0x759456a310
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f52500 VA: 0x759456a500
	public Void .ctor() { }
}
```