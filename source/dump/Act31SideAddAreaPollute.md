# Act31SideAddAreaPollute

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _useSnapshotTile`

- `Int32 _addPolluteV`

- `Boolean _needCheckTile`

- `Single _rangeRadius`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideAddAreaPollute : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _useSnapshotTile; // 0x14
	private Int32 _addPolluteV; // 0x18
	private Boolean _needCheckTile; // 0x1c
	private Single _rangeRadius; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edcb90 VA: 0x75944f4b90
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edcbf8 VA: 0x75944f4bf8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edd0e4 VA: 0x75944f50e4
	public Void .ctor() { }
}
```