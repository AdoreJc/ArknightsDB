# NoTargetRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _loadFromBlackboard`

- `Boolean _isSectorProjectileMovement`

- `Single _startRotateAngleZ`

- `Single _endRotateAngleZ`

- `Int32 _projectileNum`

- `Direction _mainDirction`

- `Single _perOffset`

- `Single _startOffset`


## Properties

- `Boolean isSectorProjectileMovement`


## Methods

- `Boolean get_isSectorProjectileMovement()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class NoTargetRangedAttack : MultiRangedAttack
{
	private Boolean _loadFromBlackboard; // 0x2c8
	private Boolean _isSectorProjectileMovement; // 0x2c9
	private Single _startRotateAngleZ; // 0x2cc
	private Single _endRotateAngleZ; // 0x2d0
	private Int32 _projectileNum; // 0x2d4
	private Direction _mainDirction; // 0x2d8
	private Single _perOffset; // 0x2dc
	public static Single UP; // 0x0
	public static Single RIGHT; // 0x4
	public static Single DOWN; // 0x8
	public static Single LEFT; // 0xc
	public static Single[] DirectionAngle; // 0x10
	private List`1 m_sectorProjectileRotateDirections; // 0x2e0
	private Single _startOffset; // 0x2e8
	private static DelegateBridge __Hotfix0_get_isSectorProjectileMovement; // 0x18
	private static DelegateBridge __Hotfix0_DoSetData; // 0x20
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isSectorProjectileMovement { get; }

	// RVA: 0x1e16208 VA: 0x759442e208
	public Boolean get_isSectorProjectileMovement() { }
	// RVA: 0x1e16280 VA: 0x759442e280
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e16578 VA: 0x759442e578
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e16c2c VA: 0x759442ec2c
	public Void .ctor() { }
	// RVA: 0x1e16d0c VA: 0x759442ed0c
	private static Void .cctor() { }
	// RVA: 0x1e16dd8 VA: 0x759442edd8
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e16dfc VA: 0x759442edfc
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
}
```