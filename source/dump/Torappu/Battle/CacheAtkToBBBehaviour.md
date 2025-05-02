# CacheAtkToBBBehaviour

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _increaseByTime`

- `Boolean _onlyIncreaseReached`

- `Single _interval`

- `Single _firstIntervalOffset`

- `String _intervalKey`

- `Single _increaseValue`

- `String _increaseValueKey`

- `Single _maxIncreaseValue`

- `String _maxIncreaseValueKey`

- `Boolean m_isReached`

- `FP m_originAtk`

- `FP m_originAtkScale`

- `FP m_interval`

- `FP m_increaseValue`

- `FP m_maxIncreaseValue`

- `PeriodicTimer m_timer`


## Properties

- `Boolean increaseByTime`


## Methods

- `Boolean get_increaseByTime()`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CacheAtkToBBBehaviour : Behaviour
{
	private Boolean _increaseByTime; // 0x24
	private Boolean _onlyIncreaseReached; // 0x25
	private Single _interval; // 0x28
	private Single _firstIntervalOffset; // 0x2c
	private String _intervalKey; // 0x30
	private Single _increaseValue; // 0x38
	private String _increaseValueKey; // 0x40
	private Single _maxIncreaseValue; // 0x48
	private String _maxIncreaseValueKey; // 0x50
	private Boolean m_isReached; // 0x58
	private FP m_originAtk; // 0x60
	private FP m_originAtkScale; // 0x68
	private FP m_interval; // 0x70
	private FP m_increaseValue; // 0x78
	private FP m_maxIncreaseValue; // 0x80
	private PeriodicTimer m_timer; // 0x88
	private static DelegateBridge __Hotfix0_get_increaseByTime; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Boolean increaseByTime { get; }

	// RVA: 0x40a2cb8 VA: 0x75966bacb8
	private Boolean get_increaseByTime() { }
	// RVA: 0x40a2d20 VA: 0x75966bad20
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x40a3254 VA: 0x75966bb254
	public override Void OnProjectileReached() { }
	// RVA: 0x40a333c VA: 0x75966bb33c
	public override Void OnProjectileStop() { }
	// RVA: 0x40a33e8 VA: 0x75966bb3e8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40a3594 VA: 0x75966bb594
	public Void .ctor() { }
	// RVA: 0x40a3668 VA: 0x75966bb668
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x40a3670 VA: 0x75966bb670
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x40a3678 VA: 0x75966bb678
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x40a3680 VA: 0x75966bb680
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```