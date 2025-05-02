# DeckModifierToAddCardCost

**Namespace:** ` `


## Fields

- `DeckSelector m_selector`

- `Int32 m_cost`

- `String m_overrideKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeckModifierToAddCardCost : DeckModifier
{
	private DeckSelector m_selector; // 0x20
	private Int32 m_cost; // 0x50
	private String m_overrideKey; // 0x58

	public override String overrideKey { get; }
	public override FP overridePriority { get; }

	// RVA: 0x1b799f4 VA: 0x75941919f4
	public override String get_overrideKey() { }
	// RVA: 0x1b799fc VA: 0x75941919fc
	public override FP get_overridePriority() { }
	// RVA: 0x1b79864 VA: 0x7594191864
	public Void .ctor(Card sourceCard, DeckSelector selector, Int32 cost, String overrideKey) { }
	// RVA: 0x1b79a90 VA: 0x7594191a90
	public override Boolean TryGetCardCostDelta(Card card, out Int32 costDelta) { }
}
```