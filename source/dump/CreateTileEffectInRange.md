# CreateTileEffectInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _rangeId`

- `String _effectKey`

- `Boolean _holdIt`

- `Boolean _verifyBeforeCreate`

- `Boolean _specifyBuildType`

- `BuildableType _buildableType`

- `Boolean _useAttackRange`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateTileEffectInRange : ActionNode, IEffectSource
{
	private ActionTargetType _sourceType; // 0x10
	private String _rangeId; // 0x18
	private String _effectKey; // 0x20
	private Boolean _holdIt; // 0x28
	private Boolean _verifyBeforeCreate; // 0x29
	private Boolean _specifyBuildType; // 0x2a
	private BuildableType _buildableType; // 0x2c
	private Boolean _useAttackRange; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe3bf0 VA: 0x75945fbbf0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe3c58 VA: 0x75945fbc58
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1fe3d6c VA: 0x75945fbd6c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe43a4 VA: 0x75945fc3a4
	public Void .ctor() { }
}
```