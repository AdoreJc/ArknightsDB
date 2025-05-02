# LegionModeOnlyCreateCardBuffToOneCardByCost

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _cardLibraryType`

- `Boolean _filterMinCost`

- `Boolean _createDeckBuff`

- `DeckBuff _deckBuff`


## Properties

- `LegionGameMode legionMode`


## Methods

- `LegionGameMode get_legionMode()`

- `Boolean _CheckInCardLibrary(Card)`

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCreateCardBuffToOneCardByCost : BaseCreateCardBuff
{
	private LegionCardLibraryType _cardLibraryType; // 0x20
	private Boolean _filterMinCost; // 0x24
	private Boolean _createDeckBuff; // 0x25
	private DeckBuff _deckBuff; // 0x28
	private static DelegateBridge __Hotfix0_get_legionMode; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0__CheckInCardLibrary; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private LegionGameMode legionMode { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f6b230 VA: 0x7594583230
	private LegionGameMode get_legionMode() { }
	// RVA: 0x1f6b30c VA: 0x759458330c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6b374 VA: 0x7594583374
	private Boolean _CheckInCardLibrary(Card card) { }
	// RVA: 0x1f6b424 VA: 0x7594583424
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6b754 VA: 0x7594583754
	public Void .ctor() { }
	// RVA: 0x1f6b7c4 VA: 0x75945837c4
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f6b7cc VA: 0x75945837cc
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```