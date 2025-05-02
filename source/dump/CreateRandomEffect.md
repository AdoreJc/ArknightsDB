# CreateRandomEffect

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _sourceType`

- `Boolean _useSourceFaceVector`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateRandomEffect : ActionNode, IEffectSource
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private String[] _effectKeys; // 0x18
	private Boolean _useSourceFaceVector; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f115d8 VA: 0x75945295d8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f11640 VA: 0x7594529640
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f11718 VA: 0x7594529718
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f119fc VA: 0x75945299fc
	public Void .ctor() { }
}
```