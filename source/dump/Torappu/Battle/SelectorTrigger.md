# SelectorTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _keepTarget`

- `Int32 _minTargetNum`

- `Int32 _overrideSearchTargetTick`

- `TargetSelector m_selector`

- `CompoundPeriodicTicker m_findTargetTicker`


## Properties

- `Entity owner`


## Methods

- `Entity get_owner()`

- `Void FixedUpdate()`

- `TargetSelector <>xLuaBaseProxy_get_selector()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`

- `Void <>xLuaBaseProxy_OnAbilityExtendUpdated(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SelectorTrigger : TargetTrigger
{
	private const Int32 SEARCH_TARGET_TICK; // 0x0
	private Boolean _keepTarget; // 0x20
	private Int32 _minTargetNum; // 0x24
	private Int32 _overrideSearchTargetTick; // 0x28
	private TargetSelector m_selector; // 0x30
	private ObjectPtr`1 m_lastTarget; // 0x38
	private CompoundPeriodicTicker m_findTargetTicker; // 0x48
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_owner; // 0x8
	private static DelegateBridge __Hotfix0_get_selector; // 0x10
	private static DelegateBridge __Hotfix0_SetData; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_Search; // 0x28
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x30
	private static DelegateBridge __Hotfix0_OnAbilityExtendUpdated; // 0x38
	private static DelegateBridge __Hotfix0_Validator; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override Entity target { get; }
	protected Entity owner { get; }
	public override TargetSelector selector { get; }

	// RVA: 0x1bd95a0 VA: 0x75941f15a0
	public override Entity get_target() { }
	// RVA: 0x1bd7b20 VA: 0x75941efb20
	protected Entity get_owner() { }
	// RVA: 0x1bd9620 VA: 0x75941f1620
	public override TargetSelector get_selector() { }
	// RVA: 0x1bd9688 VA: 0x75941f1688
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bd4344 VA: 0x75941ec344
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd45d8 VA: 0x75941ec5d8
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd9728 VA: 0x75941f1728
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd97b8 VA: 0x75941f17b8
	public override Void OnAbilityExtendUpdated(FP extend) { }
	// RVA: 0x1bd64c8 VA: 0x75941ee4c8
	protected virtual Boolean Validator(Entity target) { }
	// RVA: 0x1bd91d8 VA: 0x75941f11d8
	protected virtual Void Awake() { }
	// RVA: 0x1bd98d0 VA: 0x75941f18d0
	private Void FixedUpdate() { }
	// RVA: 0x1bd4a04 VA: 0x75941eca04
	public Void .ctor() { }
	// RVA: 0x1bd9944 VA: 0x75941f1944
	private TargetSelector <>xLuaBaseProxy_get_selector() { }
	// RVA: 0x1bd9948 VA: 0x75941f1948
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1bd994c VA: 0x75941f194c
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
	// RVA: 0x1bd9950 VA: 0x75941f1950
	private Void <>xLuaBaseProxy_OnAbilityExtendUpdated(FP P0) { }
}
```