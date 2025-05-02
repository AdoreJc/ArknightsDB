# AssignCertainSideContainsBuffUnitsCntToBlackboard

**Namespace:** ` `


## Fields

- `SideType _sideMask`

- `Boolean _filterProfessionMask`

- `String _buffKey`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignCertainSideContainsBuffUnitsCntToBlackboard : ActionNode
{
	private SideType _sideMask; // 0x10
	private Boolean _filterProfessionMask; // 0x14
	private String _buffKey; // 0x18
	private String _blackboardKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef367c VA: 0x759450b67c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef36e4 VA: 0x759450b6e4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef3b80 VA: 0x759450bb80
	public Void .ctor() { }
}
```