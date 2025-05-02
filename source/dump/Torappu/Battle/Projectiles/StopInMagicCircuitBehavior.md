# StopInMagicCircuitBehavior

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _stopEffectKey`

- `Single _delayStop`

- `Single _delayCheck`

- `Tile m_currentTile`

- `Boolean m_hasStopInMagicCircuit`

- `FP m_delayCheckTicker`


## Methods

- `Void _StopInMagicCircuit()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class StopInMagicCircuitBehavior : Behaviour
{
	private String _stopEffectKey; // 0x28
	private Single _delayStop; // 0x30
	private Single _delayCheck; // 0x34
	private Tile m_currentTile; // 0x38
	private Boolean m_hasStopInMagicCircuit; // 0x40
	private FP m_delayCheckTicker; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__StopInMagicCircuit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d78088 VA: 0x7594390088
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d78180 VA: 0x7594390180
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d78484 VA: 0x7594390484
	private Void _StopInMagicCircuit() { }
	// RVA: 0x1d78580 VA: 0x7594390580
	public Void .ctor() { }
	// RVA: 0x1d78628 VA: 0x7594390628
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d78630 VA: 0x7594390630
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```