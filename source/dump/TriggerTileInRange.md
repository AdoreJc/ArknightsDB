# TriggerTileInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _rangeId`

- `Boolean _isTriggerSpecificTiles`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerTileInRange : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _rangeId; // 0x18
	private Boolean _isTriggerSpecificTiles; // 0x20
	private String[] _tileKeys; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe7a8c VA: 0x75945ffa8c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe7af4 VA: 0x75945ffaf4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe7db0 VA: 0x75945ffdb0
	public Void .ctor() { }
}
```