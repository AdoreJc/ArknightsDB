# DecklikeRuntimeCostModifier

**Namespace:** ` `


## Fields

- `Card m_sourceCard`

- `Int32 m_costDelta`

- `Options m_options`

- `Boolean m_isTriggered`


## Properties

- `Card sourceCard`


## Methods

- `Card get_sourceCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DecklikeRuntimeCostModifier : RuntimeCostModifier
{
	private Card m_sourceCard; // 0x28
	private Int32 m_costDelta; // 0x30
	private Options m_options; // 0x38
	private Boolean m_isTriggered; // 0x40

	public Card sourceCard { get; }
	public override String cardBuffKey { get; }
	public override String overrideKey { get; }
	public override FP overridePriority { get; }

	// RVA: 0x1b78988 VA: 0x7594190988
	public Card get_sourceCard() { }
	// RVA: 0x1b78990 VA: 0x7594190990
	public override String get_cardBuffKey() { }
	// RVA: 0x1b78a08 VA: 0x7594190a08
	public override String get_overrideKey() { }
	// RVA: 0x1b78a80 VA: 0x7594190a80
	public override FP get_overridePriority() { }
	// RVA: 0x1b78858 VA: 0x7594190858
	public Void .ctor(Card sourceCard, Int32 costDelta, Options options) { }
	// RVA: 0x1b78b14 VA: 0x7594190b14
	public override Void Preprocess(Deck deck) { }
	// RVA: 0x1b78bfc VA: 0x7594190bfc
	public override Boolean TryGetCostDelta(Card card, out Int32 costDelta) { }
}
```