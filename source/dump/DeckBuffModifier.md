# DeckBuffModifier

**Namespace:** ` `


## Fields

- `Options m_options`

- `Boolean m_isTriggered`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeckBuffModifier : DeckModifier
{
	private IList`1 m_deckBuffs; // 0x20
	private Options m_options; // 0x28
	private Boolean m_isTriggered; // 0x30


	// RVA: 0x1b781c0 VA: 0x75941901c0
	public Void .ctor(Card sourceCard, IList`1 deckBuffs, Options options) { }
	// RVA: 0x1b78494 VA: 0x7594190494
	public override Void Preprocess(Deck deck) { }
	// RVA: 0x1b7858c VA: 0x759419058c
	public override Boolean TryGetDeckBuff(Card card, out IList`1 buffs) { }
}
```