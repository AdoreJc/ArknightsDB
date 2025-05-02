# CreateLineEffect

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `String _effectKey`

- `Boolean _useSourceFaceVactor`

- `Boolean _useAttackPlaybackSpeed`

- `Boolean _useHostAsTarget`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateLineEffect : ActionNode, IEffectSource
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private String _effectKey; // 0x18
	private Boolean _useSourceFaceVactor; // 0x20
	private Boolean _useAttackPlaybackSpeed; // 0x21
	private Boolean _useHostAsTarget; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f104c8 VA: 0x75945284c8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f10530 VA: 0x7594528530
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f10644 VA: 0x7594528644
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f10b80 VA: 0x7594528b80
	public Void .ctor() { }
}
```