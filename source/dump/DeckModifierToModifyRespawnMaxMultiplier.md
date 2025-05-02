# DeckModifierToModifyRespawnMaxMultiplier

**Namespace:** ` `


## Fields

- `DeckSelector m_selector`

- `FP m_maxMultiplier`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeckModifierToModifyRespawnMaxMultiplier : DeckModifier
{
	private DeckSelector m_selector; // 0x20
	private FP m_maxMultiplier; // 0x50


	// RVA: 0x1b7a554 VA: 0x7594192554
	public Void .ctor(Card sourceCard, DeckSelector selector, FP maxMultiplier) { }
	// RVA: 0x1b7a640 VA: 0x7594192640
	public override Boolean TryHookMaxMultiplier(Card card, out FP respawnCostMaxMultiplier) { }
}
```