# SetTilesEnableOverlap

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _isEnable`

- `Boolean _onlyRootTile`

- `Boolean _allTilesExceptRootTile`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetTilesEnableOverlap : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _isEnable; // 0x14
	private Boolean _onlyRootTile; // 0x15
	private Boolean _allTilesExceptRootTile; // 0x16
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe65c4 VA: 0x75945fe5c4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe662c VA: 0x75945fe62c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe68a0 VA: 0x75945fe8a0
	public Void .ctor() { }
}
```