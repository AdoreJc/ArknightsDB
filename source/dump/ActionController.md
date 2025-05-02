# ActionController

**Namespace:** ` `


## Fields

- `Boolean _detachBuffsWhenTargetLeave`

- `Boolean _detachAllBuffsWhenStopped`

- `Boolean _onlyAddBuffsToTraceTarget`

- `Boolean _onlyAddBuffsToTargetOnce`

- `Boolean _dontAddBuffs`

- `Boolean _useExtraBuffsWhenStopHit`

- `Boolean _addExtraBuffsWhenReached`

- `Boolean _detachAllExtraBuffsWhenStopped`

- `Int32 m_addBuffsToTargetCnt`

- `Blackboard <blackboard>k__BackingField`

- `Projectile <projectile>k__BackingField`


## Properties

- `Blackboard blackboard`

- `Projectile projectile`

- `Boolean hasExtraBuffsInTheEnd`


## Methods

- `Blackboard get_blackboard()`

- `Void set_blackboard(Blackboard)`

- `Projectile get_projectile()`

- `Void set_projectile(Projectile)`

- `Boolean get_hasExtraBuffsInTheEnd()`

- `Void Init(Ability, Projectile)`

- `Void InitFromProjectile(Projectile, Projectile)`

- `Void RegisterActions(Event, IList`1, Boolean)`

- `Void RegisterBuffs(IList`1, Boolean)`

- `Void RegisterExtraBlackboard(Blackboard, Boolean)`

- `Void OnHitTarget(Entity)`

- `Void OnHitTargetLeft(Entity)`

- `Void OnProjectileStop()`

- `Void OnProjectileReached()`

- `Void ReplaceActionNodes(Event, List`1)`

- `Void _RunActions(Event, Entity)`

- `Void _AttachBuffs(IList`1, Entity)`

- `Void _AttachExtraBuffWhenStopHit(Entity)`

- `Void _AttachExtraBuffWhenStop()`

- `Void _AttachExtraBuffWhenReached(Entity)`

- `Void AttachExtraBuffsToTargetMap(Entity, Buff)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ActionController
{
	private Boolean _detachBuffsWhenTargetLeave; // 0x10
	private Boolean _detachAllBuffsWhenStopped; // 0x11
	private Boolean _onlyAddBuffsToTraceTarget; // 0x12
	private Boolean _onlyAddBuffsToTargetOnce; // 0x13
	private Boolean _dontAddBuffs; // 0x14
	private BuffData[] _extraBuffsInTheEnd; // 0x18
	private Boolean _useExtraBuffsWhenStopHit; // 0x20
	private Boolean _addExtraBuffsWhenReached; // 0x21
	private Boolean _detachAllExtraBuffsWhenStopped; // 0x22
	private Int32 m_addBuffsToTargetCnt; // 0x24
	private List`1[] m_actionsToAttach; // 0x28
	private List`1 m_buffsToAttach; // 0x30
	private IList`1 m_attachmentsToAttach; // 0x38
	private Dictionary`2 m_attachedBuffsForTargetMap; // 0x40
	private Dictionary`2 m_attachedExtraBuffsForTargetMap; // 0x48
	private Blackboard <blackboard>k__BackingField; // 0x50
	private Projectile <projectile>k__BackingField; // 0x58

	public Blackboard blackboard { get; set; }
	public Projectile projectile { get; set; }
	public BuffData[] extraBuffsInTheEnd { get; }
	public Boolean hasExtraBuffsInTheEnd { get; }
	public List`1[] actionsToAttach { get; }

	// RVA: 0x40b38d8 VA: 0x75966cb8d8
	public Blackboard get_blackboard() { }
	// RVA: 0x40b38e0 VA: 0x75966cb8e0
	private Void set_blackboard(Blackboard value) { }
	// RVA: 0x40b38e8 VA: 0x75966cb8e8
	public Projectile get_projectile() { }
	// RVA: 0x40b38f0 VA: 0x75966cb8f0
	private Void set_projectile(Projectile value) { }
	// RVA: 0x40b38f8 VA: 0x75966cb8f8
	public BuffData[] get_extraBuffsInTheEnd() { }
	// RVA: 0x40b3900 VA: 0x75966cb900
	public Boolean get_hasExtraBuffsInTheEnd() { }
	// RVA: 0x40b3954 VA: 0x75966cb954
	public List`1[] get_actionsToAttach() { }
	// RVA: 0x40b395c VA: 0x75966cb95c
	public Void Init(Ability ability, Projectile projectile) { }
	// RVA: 0x40b3dbc VA: 0x75966cbdbc
	public Void InitFromProjectile(Projectile sourceProjectile, Projectile projectile) { }
	// RVA: 0x40b3c08 VA: 0x75966cbc08
	public Void RegisterActions(Event ev, IList`1 actions, Boolean additive) { }
	// RVA: 0x40b3ae0 VA: 0x75966cbae0
	public Void RegisterBuffs(IList`1 buffDataList, Boolean additive) { }
	// RVA: 0x40b3f18 VA: 0x75966cbf18
	public Void RegisterExtraBlackboard(Blackboard extraBlackboard, Boolean additive) { }
	// RVA: 0x40b3fe0 VA: 0x75966cbfe0
	public Void OnHitTarget(Entity target) { }
	// RVA: 0x40b4b28 VA: 0x75966ccb28
	public Void OnHitTargetLeft(Entity target) { }
	// RVA: 0x40b4c0c VA: 0x75966ccc0c
	public Void OnProjectileStop() { }
	// RVA: 0x40b50d0 VA: 0x75966cd0d0
	public Void OnProjectileReached() { }
	// RVA: 0x40b5254 VA: 0x75966cd254
	public IList`1 GetActionNodes(Event ev) { }
	// RVA: 0x40b5284 VA: 0x75966cd284
	public Void ReplaceActionNodes(Event ev, List`1 newActionNodes) { }
	// RVA: 0x40b4800 VA: 0x75966cc800
	private Void _RunActions(Event ev, Entity rewriteTarget) { }
	// RVA: 0x40b528c VA: 0x75966cd28c
	internal Void RunActionsOnTile(Event ev, Tile tile) { }
	// RVA: 0x40b4134 VA: 0x75966cc134
	private Void _AttachBuffs(IList`1 buffs, Entity target) { }
	// RVA: 0x40b46b4 VA: 0x75966cc6b4
	private Void _AttachExtraBuffWhenStopHit(Entity target) { }
	// RVA: 0x40b4f50 VA: 0x75966ccf50
	private Void _AttachExtraBuffWhenStop() { }
	// RVA: 0x40b5108 VA: 0x75966cd108
	private Void _AttachExtraBuffWhenReached(Entity target) { }
	// RVA: 0x40b558c VA: 0x75966cd58c
	private Void AttachExtraBuffsToTargetMap(Entity target, Buff buff) { }
	// RVA: 0x40b572c VA: 0x75966cd72c
	public Void .ctor() { }
}
```