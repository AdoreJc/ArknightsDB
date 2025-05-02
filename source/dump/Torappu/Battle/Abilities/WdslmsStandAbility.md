# WdslmsStandAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isHost`

- `Enemy m_host`


## Properties

- `Boolean isHost`

- `Enemy host`


## Methods

- `Boolean get_isHost()`

- `Enemy get_host()`

- `Void SetIsHost(Boolean)`

- `Void RegisterHost(Enemy)`

- `Void RegisterStand(Enemy)`

- `Void CopyStandList(WdslmsStandAbility)`

- `Boolean RunActions(ActionsTargetType, ActionNode[], SourceType, Blackboard)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class WdslmsStandAbility : EmptyAbility
{
	private Boolean _isHost; // 0x107
	private Enemy m_host; // 0x108
	private List`1 m_stands; // 0x110
	private List`1 m_actionTargets; // 0x118
	private static DelegateBridge __Hotfix0_get_isHost; // 0x0
	private static DelegateBridge __Hotfix0_get_host; // 0x8
	private static DelegateBridge __Hotfix0_get_stands; // 0x10
	private static DelegateBridge __Hotfix0_SetIsHost; // 0x18
	private static DelegateBridge __Hotfix0_RegisterHost; // 0x20
	private static DelegateBridge __Hotfix0_RegisterStand; // 0x28
	private static DelegateBridge __Hotfix0_CopyStandList; // 0x30
	private static DelegateBridge __Hotfix0_RunActions; // 0x38
	private static DelegateBridge __Hotfix0_DoSetData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean isHost { get; }
	public Enemy host { get; }
	public List`1 stands { get; }

	// RVA: 0x1eb6c14 VA: 0x75944cec14
	public Boolean get_isHost() { }
	// RVA: 0x1eb6c7c VA: 0x75944cec7c
	public Enemy get_host() { }
	// RVA: 0x1eb6ce4 VA: 0x75944cece4
	public List`1 get_stands() { }
	// RVA: 0x1eb6d4c VA: 0x75944ced4c
	public Void SetIsHost(Boolean value) { }
	// RVA: 0x1eb6dcc VA: 0x75944cedcc
	public Void RegisterHost(Enemy host) { }
	// RVA: 0x1eb6e68 VA: 0x75944cee68
	public Void RegisterStand(Enemy stand) { }
	// RVA: 0x1eb6f64 VA: 0x75944cef64
	public Void CopyStandList(WdslmsStandAbility hostAbility) { }
	// RVA: 0x1eb704c VA: 0x75944cf04c
	public Boolean RunActions(ActionsTargetType targetType, ActionNode[] actions, SourceType sourceType, Blackboard blackboard) { }
	// RVA: 0x1eb79e8 VA: 0x75944cf9e8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1eb7b04 VA: 0x75944cfb04
	public Void .ctor() { }
	// RVA: 0x1eb7bfc VA: 0x75944cfbfc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
}
```