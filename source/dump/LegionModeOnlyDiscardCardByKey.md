# LegionModeOnlyDiscardCardByKey

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _cardType`

- `String _cardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyDiscardCardByKey : ActionNode
{
	private LegionCardLibraryType _cardType; // 0x10
	private String _cardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6c7d4 VA: 0x75945847d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6c83c VA: 0x759458483c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6ca7c VA: 0x7594584a7c
	public Void .ctor() { }
}
```