# CreateEffectToSurroundingTiles

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _effectKey`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateEffectToSurroundingTiles : ActionNode, IEffectSource
{
	private ActionTargetType _targetType; // 0x10
	private String _effectKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f10c30 VA: 0x7594528c30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f10c98 VA: 0x7594528c98
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f10dac VA: 0x7594528dac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f11148 VA: 0x7594529148
	public Void .ctor() { }
}
```