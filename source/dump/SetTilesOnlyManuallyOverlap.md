# SetTilesOnlyManuallyOverlap

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _onlyManuallyOverlap`

- `Boolean _onlyRootTile`

- `Boolean _allTilesExceptRootTile`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetTilesOnlyManuallyOverlap : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _onlyManuallyOverlap; // 0x14
	private Boolean _onlyRootTile; // 0x15
	private Boolean _allTilesExceptRootTile; // 0x16
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe6c6c VA: 0x75945fec6c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe6cd4 VA: 0x75945fecd4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe6f48 VA: 0x75945fef48
	public Void .ctor() { }
}
```