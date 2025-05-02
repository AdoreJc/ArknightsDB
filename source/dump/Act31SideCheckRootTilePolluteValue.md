# Act31SideCheckRootTilePolluteValue

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `CompareType _condType`

- `String _checkValueKey`

- `Int32 _checkValue`

- `Boolean _checkSourceBehindTile`

- `Boolean _needAreaPV`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideCheckRootTilePolluteValue : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private CompareType _condType; // 0x14
	private String _checkValueKey; // 0x18
	private Int32 _checkValue; // 0x20
	private Boolean _checkSourceBehindTile; // 0x24
	private Boolean _needAreaPV; // 0x25
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edc1c0 VA: 0x75944f41c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edc228 VA: 0x75944f4228
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edc55c VA: 0x75944f455c
	public Void .ctor() { }
}
```