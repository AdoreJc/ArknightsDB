# FinishCardBuffsByKey

**Namespace:** ` `


## Fields

- `String _cardBuffKey`

- `Boolean _findAllCard`

- `Boolean _ignoreOwner`

- `Boolean _onlyOwner`


## Methods

- `Void <Execute>b__6_0(Deck)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishCardBuffsByKey : ActionNode
{
	private String _cardBuffKey; // 0x10
	private Boolean _findAllCard; // 0x18
	private Boolean _ignoreOwner; // 0x19
	private Boolean _onlyOwner; // 0x1a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f08550 VA: 0x7594520550
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f085b8 VA: 0x75945205b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f08898 VA: 0x7594520898
	public Void .ctor() { }
	// RVA: 0x1f08908 VA: 0x7594520908
	private Void <Execute>b__6_0(Deck deck) { }
}
```