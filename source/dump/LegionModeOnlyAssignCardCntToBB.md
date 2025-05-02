# LegionModeOnlyAssignCardCntToBB

**Namespace:** ` `


## Fields

- `String _cardKey`

- `String _cardId`

- `Boolean _onlyInHand`

- `LegionCardLibraryType _cardLibraryType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAssignCardCntToBB : ActionNode
{
	private String _cardKey; // 0x10
	private String _cardId; // 0x18
	private Boolean _onlyInHand; // 0x20
	private LegionCardLibraryType _cardLibraryType; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f62e9c VA: 0x759457ae9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f62f04 VA: 0x759457af04
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f631ec VA: 0x759457b1ec
	public Void .ctor() { }
}
```