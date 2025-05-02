# AirSupportLockEffectBehaviour

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _tileEffect`

- `Boolean m_effectCreated`

- `Effect m_tileEffect`


## Methods

- `Void _FinishEffect(Object)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AirSupportLockEffectBehaviour : AbstractEffectEmitter
{
	private String _tileEffect; // 0x20
	private Boolean m_effectCreated; // 0x28
	private Effect m_tileEffect; // 0x30
	private ObjectPtr`1 m_ownerEnemy; // 0x38
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0__FinishEffect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ec9a38 VA: 0x75944e1a38
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ec9c2c VA: 0x75944e1c2c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ec9f98 VA: 0x75944e1f98
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec9eb0 VA: 0x75944e1eb0
	private Void _FinishEffect(Object arg) { }
	// RVA: 0x1eca0ac VA: 0x75944e20ac
	public Void .ctor() { }
	// RVA: 0x1eca11c VA: 0x75944e211c
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1eca124 VA: 0x75944e2124
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```