# ApplyCacheAtkDamageByBuffBlackBoardCnt

**Namespace:** ` `


## Fields

- `String _damageScaleKey`

- `String _buffCnt`

- `String _buffMaxCnt`

- `Boolean _forceDisplayDamageNum`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyCacheAtkDamageByBuffBlackBoardCnt : ApplyDamage
{
	private String _damageScaleKey; // 0x30
	private String _buffCnt; // 0x38
	private String _buffMaxCnt; // 0x40
	private Boolean _forceDisplayDamageNum; // 0x48
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f3afb0 VA: 0x7594552fb0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3b018 VA: 0x7594553018
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3b360 VA: 0x7594553360
	public Void .ctor() { }
	// RVA: 0x1f3b450 VA: 0x7594553450
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f3b454 VA: 0x7594553454
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```