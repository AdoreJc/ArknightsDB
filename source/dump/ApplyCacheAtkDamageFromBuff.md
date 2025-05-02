# ApplyCacheAtkDamageFromBuff

**Namespace:** ` `


## Fields

- `String _damageScaleKey`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyCacheAtkDamageFromBuff : ApplyDamage
{
	private String _damageScaleKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f3ac04 VA: 0x7594552c04
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3ac6c VA: 0x7594552c6c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3af0c VA: 0x7594552f0c
	public Void .ctor() { }
	// RVA: 0x1f3afa8 VA: 0x7594552fa8
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f3afac VA: 0x7594552fac
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```