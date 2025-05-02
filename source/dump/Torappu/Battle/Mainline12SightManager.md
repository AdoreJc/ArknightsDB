# Mainline12SightManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _inSight`

- `String _outOfSight`

- `String _notViewed`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitFinish(Object)`

- `Void _UpdateTileByDiff()`

- `Void _MarkInView(Boolean, Tile)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTrigger(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Mainline12SightManager : EnvManager
{
	private String _inSight; // 0x28
	private String _outOfSight; // 0x30
	private String _notViewed; // 0x38
	private ListDict`2 m_unitModeIndexCache; // 0x40
	private ListDict`2 m_tileInUnitAttackRangeBefore; // 0x48
	private List`1 m_newInViewTile; // 0x50
	private Int32[,] m_cacheTileStatus; // 0x58
	private Int32[,] m_tileStatus; // 0x60
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x10
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x18
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x20
	private static DelegateBridge __Hotfix0__UpdateTileByDiff; // 0x28
	private static DelegateBridge __Hotfix0__MarkInView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x404d940 VA: 0x7596665940
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x404dc4c VA: 0x7596665c4c
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x404de80 VA: 0x7596665e80
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x404e080 VA: 0x7596666080
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x404e688 VA: 0x7596666688
	public override Void OnTrigger(Object param) { }
	// RVA: 0x404e430 VA: 0x7596666430
	private Void _UpdateTileByDiff() { }
	// RVA: 0x404e33c VA: 0x759666633c
	private Void _MarkInView(Boolean inCharView, Tile tile) { }
	// RVA: 0x404eba8 VA: 0x7596666ba8
	public Void .ctor() { }
	// RVA: 0x404ed0c VA: 0x7596666d0c
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x404ed14 VA: 0x7596666d14
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x404ed1c VA: 0x7596666d1c
	private Void <>xLuaBaseProxy_OnTrigger(Object P0) { }
}
```