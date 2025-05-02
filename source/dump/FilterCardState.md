# FilterCardState

**Namespace:** ` `


## Fields

- `State _cardState`

- `ActionTargetType _target`

- `Boolean _filterTokenOrHostCard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterCardState : ActionNode
{
	private State _cardState; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _filterTokenOrHostCard; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f33984 VA: 0x759454b984
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f339ec VA: 0x759454b9ec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f33bd4 VA: 0x759454bbd4
	public Void .ctor() { }
}
```