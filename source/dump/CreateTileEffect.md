# CreateTileEffect

**Namespace:** ` `


## Fields

- `String _effectKey`

- `Boolean _holdIt`

- `Boolean _verifyBeforeCreate`

- `Boolean _hasSource`

- `ActionTargetType _sourceType`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateTileEffect : ActionNode, IEffectSource
{
	private String _effectKey; // 0x10
	private Boolean _holdIt; // 0x18
	private Boolean _verifyBeforeCreate; // 0x19
	private Boolean _hasSource; // 0x1a
	private ActionTargetType _sourceType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe3734 VA: 0x75945fb734
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe379c VA: 0x75945fb79c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1fe38b0 VA: 0x75945fb8b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe3b40 VA: 0x75945fbb40
	public Void .ctor() { }
}
```