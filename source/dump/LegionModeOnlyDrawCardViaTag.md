# LegionModeOnlyDrawCardViaTag

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _cardType`

- `Int32 _count`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyDrawCardViaTag : ActionNode
{
	private LegionCardLibraryType _cardType; // 0x10
	private String[] _tags; // 0x18
	private Int32 _count; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f68140 VA: 0x7594580140
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f681a8 VA: 0x75945801a8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f68310 VA: 0x7594580310
	public Void .ctor() { }
}
```