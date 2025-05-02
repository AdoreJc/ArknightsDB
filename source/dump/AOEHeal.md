# AOEHeal

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `TargetOptions _targetOptions`

- `Boolean _excludeTarget`

- `String _rangeId`

- `Boolean _useAttackRange`

- `Boolean _ignoreHealFree`

- `Boolean _createEffect`

- `String _healEffectKey`

- `String _healScale`

- `SideType _sourceSideType`

- `FP m_cachedAtk`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AOEHeal : ActionNode, IEffectSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private TargetOptions _targetOptions; // 0x18
	private Boolean _excludeTarget; // 0x78
	private String _rangeId; // 0x80
	private Boolean _useAttackRange; // 0x88
	private Boolean _ignoreHealFree; // 0x89
	private Boolean _createEffect; // 0x8a
	private String _healEffectKey; // 0x90
	private String _healScale; // 0x98
	private SideType _sourceSideType; // 0xa0
	private FP m_cachedAtk; // 0xa8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f5c264 VA: 0x7594574264
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5c2cc VA: 0x75945742cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5cad8 VA: 0x7594574ad8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f5cbec VA: 0x7594574bec
	public Void .ctor() { }
}
```