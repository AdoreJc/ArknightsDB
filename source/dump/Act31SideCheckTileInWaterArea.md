# Act31SideCheckTileInWaterArea

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _checkSourceBehindTile`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideCheckTileInWaterArea : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _checkSourceBehindTile; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edbe88 VA: 0x75944f3e88
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edbef0 VA: 0x75944f3ef0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edc14c VA: 0x75944f414c
	public Void .ctor() { }
}
```