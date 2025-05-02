# FinishDeckBuffByKey

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _deckBuffKey`

- `Boolean _removeFromAllCard`


## Methods

- `Void <Execute>b__5_0(Card[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishDeckBuffByKey : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _deckBuffKey; // 0x18
	private Boolean _removeFromAllCard; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4e410 VA: 0x7594566410
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4e478 VA: 0x7594566478
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4e830 VA: 0x7594566830
	public Void .ctor() { }
	// RVA: 0x1f4e8a0 VA: 0x75945668a0
	private Void <Execute>b__5_0(Card[] cards) { }
}
```