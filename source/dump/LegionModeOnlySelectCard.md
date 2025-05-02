# LegionModeOnlySelectCard

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _cardType`

- `String _rangeNumKey`

- `String _canSelectNumKey`

- `String _goldNumWhenSellCard`

- `Boolean _discardUnselected`

- `Boolean _putInPendingIfHandFull`

- `LegionSelectCardType _selectCardType`


## Properties

- `ProfessionCategory professionGroup`


## Methods

- `ProfessionCategory get_professionGroup()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlySelectCard : ActionNode
{
	private LegionCardLibraryType _cardType; // 0x10
	private String _rangeNumKey; // 0x18
	private String _canSelectNumKey; // 0x20
	private String _goldNumWhenSellCard; // 0x28
	private Boolean _discardUnselected; // 0x30
	private Boolean _putInPendingIfHandFull; // 0x31
	private LegionSelectCardType _selectCardType; // 0x34
	private String[] _specificCardKeys; // 0x38
	private ProfessionCategory[] _profession; // 0x40
	private static DelegateBridge __Hotfix0_get_professionGroup; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ProfessionCategory professionGroup { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f63548 VA: 0x759457b548
	private ProfessionCategory get_professionGroup() { }
	// RVA: 0x1f63624 VA: 0x759457b624
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6368c VA: 0x759457b68c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f63914 VA: 0x759457b914
	public Void .ctor() { }
}
```