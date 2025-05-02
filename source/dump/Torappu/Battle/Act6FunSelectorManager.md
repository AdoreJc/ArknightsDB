# Act6FunSelectorManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _pivotEffect`

- `Single _pivotMoveSpeed`

- `Single _pivotEffectOffset`

- `Single _startOffsetX`

- `Single _preDelay`

- `Effect m_pivotEffect`

- `Single m_preDelay`

- `Vector3 m_originPivotPos`

- `Vector3 m_targetPivotPos`

- `Single m_pivotMoveSpeed`


## Methods

- `Boolean _VerifyTargetPosition(Entity)`

- `Boolean _VerifyTargetContainsBuff(Entity)`

- `Void _UpdatePivotEffectPosition(FP)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_SelectTargets(List`1)`

- `Boolean <>xLuaBaseProxy_VerifyTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act6FunSelectorManager : EnvSelectorManager
{
	private String _pivotEffect; // 0xc8
	private Single _pivotMoveSpeed; // 0xd0
	private Single _pivotEffectOffset; // 0xd4
	private Single _startOffsetX; // 0xd8
	private Single _preDelay; // 0xdc
	private String[] _additionalTargetsWithBuffKeys; // 0xe0
	private Effect m_pivotEffect; // 0xe8
	private Single m_preDelay; // 0xf0
	private Vector3 m_originPivotPos; // 0xf4
	private Vector3 m_targetPivotPos; // 0x100
	private Single m_pivotMoveSpeed; // 0x10c
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_SelectTargets; // 0x18
	private static DelegateBridge __Hotfix0_VerifyTarget; // 0x20
	private static DelegateBridge __Hotfix0__VerifyTargetPosition; // 0x28
	private static DelegateBridge __Hotfix0__VerifyTargetContainsBuff; // 0x30
	private static DelegateBridge __Hotfix0__UpdatePivotEffectPosition; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x4043288 VA: 0x759665b288
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x40433ac VA: 0x759665b3ac
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x40436a0 VA: 0x759665b6a0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4043bfc VA: 0x759665bbfc
	protected override Void SelectTargets(List`1 candidates) { }
	// RVA: 0x4043fa4 VA: 0x759665bfa4
	protected override Boolean VerifyTarget(Entity entity) { }
	// RVA: 0x4044250 VA: 0x759665c250
	private Boolean _VerifyTargetPosition(Entity entity) { }
	// RVA: 0x404418c VA: 0x759665c18c
	private Boolean _VerifyTargetContainsBuff(Entity entity) { }
	// RVA: 0x4043a40 VA: 0x759665ba40
	private Void _UpdatePivotEffectPosition(FP deltaTime) { }
	// RVA: 0x40443a4 VA: 0x759665c3a4
	public Void .ctor() { }
	// RVA: 0x404455c VA: 0x759665c55c
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x4044564 VA: 0x759665c564
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4044568 VA: 0x759665c568
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x404456c VA: 0x759665c56c
	private Void <>xLuaBaseProxy_SelectTargets(List`1 P0) { }
	// RVA: 0x4044918 VA: 0x759665c918
	private Boolean <>xLuaBaseProxy_VerifyTarget(Entity P0) { }
}
```