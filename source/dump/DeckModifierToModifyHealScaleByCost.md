# DeckModifierToModifyHealScaleByCost

**Namespace:** ` `


## Fields

- `Int32 m_maxCost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeckModifierToModifyHealScaleByCost : DeckModifier
{
	private IList`1 m_deckBuffs; // 0x20
	private Int32 m_maxCost; // 0x28


	// RVA: 0x1b7a130 VA: 0x7594192130
	public Void .ctor(Card sourceCard, IList`1 deckBuffs, Int32 maxCost) { }
	// RVA: 0x1b7a258 VA: 0x7594192258
	public override Boolean TryGetDeckBuff(Card card, out IList`1 buffs) { }
}
```