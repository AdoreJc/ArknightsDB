# Act25SideExtraManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _ristarMove`

- `Int32 _movingCursorIndex`

- `EnemyRistar m_ristar`


## Methods

- `Void _OnTileClicked(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _CreateEffectIfNot(Tile)`

- `Void _FinishEffectIfNot()`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTrigger(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act25SideExtraManager : EnvManager, IEffectSource
{
	private String _ristarMove; // 0x28
	private Int32 _movingCursorIndex; // 0x30
	private String[] _cantMoveMark; // 0x38
	private List`1 _tileKeyList; // 0x40
	private List`1 _effects; // 0x48
	private ObjectPtr`1 m_effect; // 0x50
	private EnemyRistar m_ristar; // 0x60
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OnTileClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x18
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x20
	private static DelegateBridge __Hotfix0__CreateEffectIfNot; // 0x28
	private static DelegateBridge __Hotfix0__FinishEffectIfNot; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x402a6e4 VA: 0x75966426e4
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x402a850 VA: 0x7596642850
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x402a978 VA: 0x7596642978
	private Void _OnTileClicked(Object arg) { }
	// RVA: 0x402b138 VA: 0x7596643138
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x402b2c8 VA: 0x75966432c8
	public override Void OnTrigger(Object param) { }
	// RVA: 0x402ae24 VA: 0x7596642e24
	private Void _CreateEffectIfNot(Tile tile) { }
	// RVA: 0x402b344 VA: 0x7596643344
	private Void _FinishEffectIfNot() { }
	// RVA: 0x402b43c VA: 0x759664343c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x402b654 VA: 0x7596643654
	public Void .ctor() { }
	// RVA: 0x402b6c0 VA: 0x75966436c0
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x402b6c4 VA: 0x75966436c4
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x402b6c8 VA: 0x75966436c8
	private Void <>xLuaBaseProxy_OnTrigger(Object P0) { }
}
```