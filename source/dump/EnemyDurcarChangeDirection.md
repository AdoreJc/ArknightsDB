# EnemyDurcarChangeDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _character`

- `ActionTargetType _enemy`

- `Single _endPosOffsetAlongDirection`

- `Boolean _setDirectByBB`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyDurcarChangeDirection : ActionNode
{
	private ActionTargetType _character; // 0x10
	private ActionTargetType _enemy; // 0x14
	private Single _endPosOffsetAlongDirection; // 0x18
	private Boolean _setDirectByBB; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f58008 VA: 0x7594570008
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f58070 VA: 0x7594570070
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f58668 VA: 0x7594570668
	public Void .ctor() { }
}
```