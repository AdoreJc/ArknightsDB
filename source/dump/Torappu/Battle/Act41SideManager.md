# Act41SideManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _inSight`

- `String _outOfSight`

- `Int32 _tickFrameCnt`

- `TargetOptions _targetOptions`

- `InRangeTilesManager m_tilesManager`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitFinish(Object)`

- `Void OnDestroy()`

- `Boolean _IsValidCharacter(Character)`

- `Void _MarkDirty(Object)`

- `Void _TickModeChanges()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act41SideManager : EnvManager
{
	private String _inSight; // 0x28
	private String _outOfSight; // 0x30
	private Int32 _tickFrameCnt; // 0x38
	private TargetOptions _targetOptions; // 0x40
	private String[] _specialAllowedTag; // 0xa0
	private ListDict`2 m_unitModeIndexCache; // 0xa8
	private InRangeTilesManager m_tilesManager; // 0xb0
	private HashSet`1 m_cachedInRangeTiles; // 0xb8
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x10
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__IsValidCharacter; // 0x30
	private static DelegateBridge __Hotfix0__MarkDirty; // 0x38
	private static DelegateBridge __Hotfix0__TickModeChanges; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4040e5c VA: 0x7596658e5c
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x40411fc VA: 0x75966591fc
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x4041354 VA: 0x7596659354
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x4041784 VA: 0x7596659784
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x4041aac VA: 0x7596659aac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40425bc VA: 0x759665a5bc
	private Void OnDestroy() { }
	// RVA: 0x40414d0 VA: 0x75966594d0
	private Boolean _IsValidCharacter(Character character) { }
	// RVA: 0x404269c VA: 0x759665a69c
	private Void _MarkDirty(Object param) { }
	// RVA: 0x4041e68 VA: 0x7596659e68
	private Void _TickModeChanges() { }
	// RVA: 0x4042984 VA: 0x759665a984
	public Void .ctor() { }
	// RVA: 0x4042c4c VA: 0x759665ac4c
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x4042c54 VA: 0x759665ac54
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4042c5c VA: 0x759665ac5c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```