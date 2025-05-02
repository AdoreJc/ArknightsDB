# CheckCurrentTileKey

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isExclude`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCurrentTileKey : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private List`1 _tileKey; // 0x18
	private Boolean _isExclude; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2bc4c VA: 0x7594543c4c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2bcb4 VA: 0x7594543cb4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2be30 VA: 0x7594543e30
	public Void .ctor() { }
}
```