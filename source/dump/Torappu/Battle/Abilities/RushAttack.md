# RushAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Enemy m_enemy`

- `Single m_speed`

- `Boolean m_isRushing`

- `Vector2 m_targetMapPos`

- `Vector2 m_oriMapPos`

- `Entity m_target`

- `Vector2 m_direction`


## Properties

- `Vector2 faceDir`


## Methods

- `Vector2 get_faceDir()`

- `Void SetRush(Vector2, Entity)`

- `Void _moveByTarget(Single)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`

- `IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RushAttack : AbstractAnimatedAbility
{
	private Enemy m_enemy; // 0x1c0
	private Single m_speed; // 0x1c8
	private Boolean m_isRushing; // 0x1cc
	private Vector2 m_targetMapPos; // 0x1d0
	private Vector2 m_oriMapPos; // 0x1d8
	private Entity m_target; // 0x1e0
	private Vector2 m_direction; // 0x1e8
	private static DelegateBridge __Hotfix0_get_faceDir; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x20
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x28
	private static DelegateBridge __Hotfix0_OnWaitForPostDelay; // 0x30
	private static DelegateBridge __Hotfix0_SetRush; // 0x38
	private static DelegateBridge __Hotfix0__moveByTarget; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Vector2 faceDir { get; }

	// RVA: 0x1e1b8d4 VA: 0x75944338d4
	private Vector2 get_faceDir() { }
	// RVA: 0x1e1ba18 VA: 0x7594433a18
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e1bb04 VA: 0x7594433b04
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e1bb84 VA: 0x7594433b84
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e1bc6c VA: 0x7594433c6c
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e1bce4 VA: 0x7594433ce4
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e1c080 VA: 0x7594434080
	protected override IEnumerator OnWaitForPostDelay() { }
	// RVA: 0x1e1bdb8 VA: 0x7594433db8
	public Void SetRush(Vector2 targetPos, Entity target) { }
	// RVA: 0x1e1c154 VA: 0x7594434154
	private Void _moveByTarget(Single deltaTime) { }
	// RVA: 0x1e1c454 VA: 0x7594434454
	public Void .ctor() { }
	// RVA: 0x1e1c4cc VA: 0x75944344cc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1c4f4 VA: 0x75944344f4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1e1c4fc VA: 0x75944344fc
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e1c504 VA: 0x7594434504
	private IEnumerator <>xLuaBaseProxy_OnWaitForPostDelay() { }
}
```