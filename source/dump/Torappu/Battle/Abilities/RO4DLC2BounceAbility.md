# RO4DLC2BounceAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _velocityDecayFactorKey`

- `Single _velocityDecayFactor`

- `String _collisionEffect`

- `String _sealCharBuffKey`

- `String _sealEnemyBuffKey`

- `String _bossBuffKey`

- `Boolean _dealTileCollision`

- `BuffData _buff`

- `Single _colliderRadius`

- `Single _frameInterval`

- `Collider2D m_collider`

- `Single m_velocityDecayFactor`


## Methods

- `Void _DealCollisionWithSealedEnemy(Collider2D)`

- `Void _DealCollisionWithSealedCharacter(Collider2D)`

- `Void _DealCollisionWithTile(Collider2D)`

- `Void _ApplyCollision(Collider2D, Vector2, Entity)`

- `Void _PlayEffect(Entity)`

- `Void OnTriggerStay2D(Collider2D)`

- `Void OnTriggerEnter2D(Collider2D)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RO4DLC2BounceAbility : EmptyAbility
{
	public const Single COLLISION_PARALLEL_DOT_THRESHOLD; // 0x0
	public const Single ZERO_VELOCITY_MARGIN; // 0x0
	private String _velocityDecayFactorKey; // 0x108
	private Single _velocityDecayFactor; // 0x110
	private String _collisionEffect; // 0x118
	private String _sealCharBuffKey; // 0x120
	private String _sealEnemyBuffKey; // 0x128
	private String _bossBuffKey; // 0x130
	private Boolean _dealTileCollision; // 0x138
	private BuffData _buff; // 0x140
	private Single _colliderRadius; // 0x148
	private Single _frameInterval; // 0x14c
	private ObjectPtr`1 m_bounceEnemy; // 0x150
	private Collider2D m_collider; // 0x160
	private ContactPoint2D[] m_contact2DList; // 0x168
	private Single m_velocityDecayFactor; // 0x170
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0__DealCollisionWithSealedEnemy; // 0x18
	private static DelegateBridge __Hotfix0__DealCollisionWithSealedCharacter; // 0x20
	private static DelegateBridge __Hotfix0__DealCollisionWithTile; // 0x28
	private static DelegateBridge __Hotfix0__ApplyCollision; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge __Hotfix0__PlayEffect; // 0x40
	private static DelegateBridge __Hotfix0_OnTriggerStay2D; // 0x48
	private static DelegateBridge __Hotfix0_OnTriggerEnter2D; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x1e4f4dc VA: 0x75944674dc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e4f66c VA: 0x759446766c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e4f754 VA: 0x7594467754
	protected override Void DoDetach() { }
	// RVA: 0x1e4f820 VA: 0x7594467820
	private Void _DealCollisionWithSealedEnemy(Collider2D collision) { }
	// RVA: 0x1e500f8 VA: 0x75944680f8
	private Void _DealCollisionWithSealedCharacter(Collider2D collision) { }
	// RVA: 0x1e50268 VA: 0x7594468268
	private Void _DealCollisionWithTile(Collider2D collision) { }
	// RVA: 0x1e4f9a4 VA: 0x75944679a4
	private Void _ApplyCollision(Collider2D collision, Vector2 targetMapPos, Entity source) { }
	// RVA: 0x1e50414 VA: 0x7594468414
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e4ff50 VA: 0x7594467f50
	private Void _PlayEffect(Entity target) { }
	// RVA: 0x1e50538 VA: 0x7594468538
	private Void OnTriggerStay2D(Collider2D collision) { }
	// RVA: 0x1e506fc VA: 0x75944686fc
	private Void OnTriggerEnter2D(Collider2D collision) { }
	// RVA: 0x1e50860 VA: 0x7594468860
	public Void .ctor() { }
	// RVA: 0x1e50988 VA: 0x7594468988
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e509b0 VA: 0x75944689b0
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e509b8 VA: 0x75944689b8
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e509c0 VA: 0x75944689c0
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```