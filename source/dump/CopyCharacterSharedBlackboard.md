# CopyCharacterSharedBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _blackboardKey`

- `Boolean _copyToSharedBlackboard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CopyCharacterSharedBlackboard : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _blackboardKey; // 0x18
	private Boolean _copyToSharedBlackboard; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1376c VA: 0x759452b76c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f137d4 VA: 0x759452b7d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f139bc VA: 0x759452b9bc
	public Void .ctor() { }
}
```