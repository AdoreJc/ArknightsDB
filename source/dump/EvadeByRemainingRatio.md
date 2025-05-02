# EvadeByRemainingRatio

**Namespace:** ` `


## Fields

- `DamageTypeMask _damageMask`

- `SourceApplyWay _applyWayFilter`


## Methods

- `Boolean _VerifyModifier(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EvadeByRemainingRatio : ActionNode
{
	private DamageTypeMask _damageMask; // 0x10
	private SourceApplyWay _applyWayFilter; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__VerifyModifier; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0f6d0 VA: 0x75945276d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0f738 VA: 0x7594527738
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0fa28 VA: 0x7594527a28
	private Boolean _VerifyModifier(ref Modifier modifier) { }
	// RVA: 0x1f0fb48 VA: 0x7594527b48
	public Void .ctor() { }
}
```