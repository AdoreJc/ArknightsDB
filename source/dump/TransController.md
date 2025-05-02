# TransController

**Namespace:** ` `


## Fields

- `RoguelikeTransitionView m_closure`


## Methods

- `Object GetSubTransParam(SubTransType, TransOptions)`

- `ISubTransition GetSubTransInst(SubTransType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TransController : IHotfixable
{
	private RoguelikeTransitionView m_closure; // 0x10
	private ListDict`2 m_prefabMap; // 0x18
	private ListDict`2 m_instMap; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetSubTransList; // 0x8
	private static DelegateBridge __Hotfix0_GetSubTransParam; // 0x10
	private static DelegateBridge __Hotfix0_GetSubTransInst; // 0x18
	private static DelegateBridge __Hotfix0_GetActiveSubTransList; // 0x20


	// RVA: 0x2a16c6c VA: 0x759502ec6c
	public Void .ctor(RoguelikeTransitionView closure) { }
	// RVA: 0x2a177d4 VA: 0x759502f7d4
	public IEnumerable`1 GetSubTransList() { }
	// RVA: 0x2a178c4 VA: 0x759502f8c4
	public Object GetSubTransParam(SubTransType type, TransOptions transOptions) { }
	// RVA: 0x2a17a48 VA: 0x759502fa48
	public ISubTransition GetSubTransInst(SubTransType type) { }
	// RVA: 0x2a174d4 VA: 0x759502f4d4
	public IEnumerator`1 GetActiveSubTransList() { }
}
```