# DeckManagedCardBuffController

**Namespace:** ` `


## Methods

- `Void RegisterCardBuff(Card, CardBuff)`

- `Void RegisterComboDrawCardBuff(Card, CardBuff, DeckSelector, Boolean)`

- `Void OnCardDrawn(Card)`

- `Void Init()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DeckManagedCardBuffController : IHotfixable
{
	private readonly List`1 m_allTimeCardBuffs; // 0x10
	private readonly List`1 m_comboDrawCardBuffs; // 0x18
	private static DelegateBridge __Hotfix0_RegisterCardBuff; // 0x0
	private static DelegateBridge __Hotfix0_RegisterComboDrawCardBuff; // 0x8
	private static DelegateBridge __Hotfix0_OnCardDrawn; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3fb82b0 VA: 0x75965d02b0
	public Void RegisterCardBuff(Card card, CardBuff cardBuff) { }
	// RVA: 0x3fb846c VA: 0x75965d046c
	public Void RegisterComboDrawCardBuff(Card card, CardBuff cardBuff, DeckSelector selector, Boolean excludeTokenAndTrap) { }
	// RVA: 0x3fb8694 VA: 0x75965d0694
	public Void OnCardDrawn(Card card) { }
	// RVA: 0x3fb8994 VA: 0x75965d0994
	public Void Init() { }
	// RVA: 0x3fb8b88 VA: 0x75965d0b88
	public Void .ctor() { }
}
```