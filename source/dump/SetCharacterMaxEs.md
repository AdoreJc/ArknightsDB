# SetCharacterMaxEs

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _blackboardKey`

- `Single _maxEsRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetCharacterMaxEs : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _blackboardKey; // 0x18
	private Single _maxEsRatio; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f12814 VA: 0x759452a814
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1287c VA: 0x759452a87c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f12a7c VA: 0x759452aa7c
	public Void .ctor() { }
}
```