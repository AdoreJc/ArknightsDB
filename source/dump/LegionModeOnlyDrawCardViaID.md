# LegionModeOnlyDrawCardViaID

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _cardType`

- `String _id`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyDrawCardViaID : ActionNode
{
	private LegionCardLibraryType _cardType; // 0x10
	private String _id; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f687ec VA: 0x75945807ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f68854 VA: 0x7594580854
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f689c8 VA: 0x75945809c8
	public Void .ctor() { }
}
```