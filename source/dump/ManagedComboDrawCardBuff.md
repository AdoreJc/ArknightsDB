# ManagedComboDrawCardBuff

**Namespace:** ` `


## Fields

- `DeckSelector selector`

- `Boolean excludeTokenAndTrap`

- `Boolean m_isActive`


## Methods

- `Void OnCardDrawn(Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ManagedComboDrawCardBuff : ManagedCardBuff
{
	public DeckSelector selector; // 0x20
	public Boolean excludeTokenAndTrap; // 0x50
	private Boolean m_isActive; // 0x51
	private static DelegateBridge __Hotfix0_OnCardDrawn; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3fb8824 VA: 0x75965d0824
	public Void OnCardDrawn(Card card) { }
	// RVA: 0x3fb8628 VA: 0x75965d0628
	public Void .ctor() { }
}
```