# ManagedCardBuff

**Namespace:** ` `


## Fields

- `Card owner`

- `CardBuff cardBuff`


## Methods

- `Void AddCardBuffToOwner()`

- `Void RemoveCardBuffFromOwner()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ManagedCardBuff : IHotfixable
{
	public Card owner; // 0x10
	public CardBuff cardBuff; // 0x18
	private static DelegateBridge __Hotfix0_AddCardBuffToOwner; // 0x0
	private static DelegateBridge __Hotfix0_RemoveCardBuffFromOwner; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3fb8b10 VA: 0x75965d0b10
	public Void AddCardBuffToOwner() { }
	// RVA: 0x3fb8d10 VA: 0x75965d0d10
	public Void RemoveCardBuffFromOwner() { }
	// RVA: 0x3fb83fc VA: 0x75965d03fc
	public Void .ctor() { }
}
```