# EnemyForceTracePosition

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Vector2 _reachOffset`

- `Boolean _randomOffset`

- `Boolean _useSelectorPosition`

- `Boolean _stopTraceWhenNoTarget`

- `Boolean _createBuffToTraceTarget`

- `BuffData _buffToTraceTarget`

- `Single _maxTraceDist`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyForceTracePosition : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Vector2 _reachOffset; // 0x18
	private Boolean _randomOffset; // 0x20
	private Boolean _useSelectorPosition; // 0x21
	private Boolean _stopTraceWhenNoTarget; // 0x22
	private Boolean _createBuffToTraceTarget; // 0x23
	private BuffData _buffToTraceTarget; // 0x28
	private Single _maxTraceDist; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9bf48 VA: 0x75945b3f48
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9bfb0 VA: 0x75945b3fb0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9c728 VA: 0x75945b4728
	public Void .ctor() { }
}
```