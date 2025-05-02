# CreateEffect

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `String _effectKey`

- `Boolean _useSourceFaceVactor`

- `Boolean _useSourceToTargetDirection`

- `Boolean _useAttackPlaybackSpeed`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateEffect : ActionNode, IEffectSource
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private String _effectKey; // 0x18
	private Boolean _useSourceFaceVactor; // 0x20
	private Boolean _useSourceToTargetDirection; // 0x21
	private Boolean _useAttackPlaybackSpeed; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_TryHookEffect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0fbc4 VA: 0x7594527bc4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0fc2c VA: 0x7594527c2c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f0fd40 VA: 0x7594527d40
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f101d0 VA: 0x75945281d0
	protected virtual String TryHookEffect(ref Snapshot snapshot, String originalEffect) { }
	// RVA: 0x1f10254 VA: 0x7594528254
	public Void .ctor() { }
}
```