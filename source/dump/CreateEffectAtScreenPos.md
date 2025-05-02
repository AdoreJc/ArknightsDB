# CreateEffectAtScreenPos

**Namespace:** ` `


## Fields

- `String _effectKey`

- `Single _screenWidthRatio`

- `Single _screenheightRatio`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateEffectAtScreenPos : ActionNode, IEffectSource
{
	private String _effectKey; // 0x10
	private Single _screenWidthRatio; // 0x18
	private Single _screenheightRatio; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f111f0 VA: 0x75945291f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f11258 VA: 0x7594529258
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1f1136c VA: 0x759452936c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f11530 VA: 0x7594529530
	public Void .ctor() { }
}
```