# EnvTileMarkInRangeBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Range _rangeToLoad`

- `String _rangeId`

- `Int32 _valueToMark`

- `String _timeBlackboardKey`

- `String _envSystemKey`

- `Boolean m_initedRange`


## Methods

- `Boolean ValidateTile(Tile)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class EnvTileMarkInRangeBehaviour : Behaviour
{
	private Range _rangeToLoad; // 0x28
	private String _rangeId; // 0x30
	private Int32 _valueToMark; // 0x38
	private String _timeBlackboardKey; // 0x40
	private String _envSystemKey; // 0x48
	private Boolean m_initedRange; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x8
	private static DelegateBridge __Hotfix0_ValidateTile; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d63a00 VA: 0x759437ba00
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d63b98 VA: 0x759437bb98
	public override Void OnProjectileReached() { }
	// RVA: 0x1d63eec VA: 0x759437beec
	private Boolean ValidateTile(Tile tile) { }
	// RVA: 0x1d63f68 VA: 0x759437bf68
	public Void .ctor() { }
	// RVA: 0x1d63fe0 VA: 0x759437bfe0
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d63fe8 VA: 0x759437bfe8
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
}
```