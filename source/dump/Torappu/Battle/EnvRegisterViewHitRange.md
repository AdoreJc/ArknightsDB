# EnvRegisterViewHitRange

**Namespace:** `Torappu.Battle`


## Fields

- `String _statusView`

- `String _statusNotView`

- `Single _tileViewRadius`

- `TargetOptions _selectedSourceOptions`

- `ViewHitRangeProvider m_hitRangeProvider`


## Methods

- `Void _DoRegisterUnit(Unit, String)`

- `Void _InitProvider()`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Void <>xLuaBaseProxy_OnEnvChanged(String, Entity, Entity)`

- `Void <>xLuaBaseProxy_OnEnvChangedOnDummy(Unit, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvRegisterViewHitRange : EnvEventExecutor
{
	public const String BLOCK_VIEW_TAG; // 0x0
	private String _statusView; // 0x28
	private String _statusNotView; // 0x30
	private Single _tileViewRadius; // 0x38
	private TargetOptions _selectedSourceOptions; // 0x40
	private List`1 _specialAllowedTag; // 0xa0
	private List`1 _specialUnviewedBuffKey; // 0xa8
	private ViewHitRangeProvider m_hitRangeProvider; // 0xb0
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnEnvChangedOnDummy; // 0x10
	private static DelegateBridge __Hotfix0__DoRegisterUnit; // 0x18
	private static DelegateBridge __Hotfix0__InitProvider; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x4025efc VA: 0x759663defc
	public override Void OnPostInit() { }
	// RVA: 0x4026118 VA: 0x759663e118
	public override Void OnEnvChanged(String status, Entity target, Entity sourceNullable) { }
	// RVA: 0x402635c VA: 0x759663e35c
	public override Void OnEnvChangedOnDummy(Unit unit, String status) { }
	// RVA: 0x4026264 VA: 0x759663e264
	private Void _DoRegisterUnit(Unit unit, String status) { }
	// RVA: 0x4026000 VA: 0x759663e000
	private Void _InitProvider() { }
	// RVA: 0x4026474 VA: 0x759663e474
	private Void OnDestroy() { }
	// RVA: 0x4026594 VA: 0x759663e594
	public Void .ctor() { }
	// RVA: 0x402674c VA: 0x759663e74c
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x4026750 VA: 0x759663e750
	private Void <>xLuaBaseProxy_OnEnvChanged(String P0, Entity P1, Entity P2) { }
	// RVA: 0x4026754 VA: 0x759663e754
	private Void <>xLuaBaseProxy_OnEnvChangedOnDummy(Unit P0, String P1) { }
}
```