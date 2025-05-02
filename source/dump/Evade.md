# Evade

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
public class Evade : ActionNode
{
	private DamageTypeMask _damageMask; // 0x10
	private SourceApplyWay _applyWayFilter; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__VerifyModifier; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0f258 VA: 0x7594527258
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0f2c0 VA: 0x75945272c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0f534 VA: 0x7594527534
	private Boolean _VerifyModifier(ref Modifier modifier) { }
	// RVA: 0x1f0f654 VA: 0x7594527654
	public Void .ctor() { }
}
```