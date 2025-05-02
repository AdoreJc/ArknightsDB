# CreateEffectForUnitsFunLiveModeOnly

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _onlyCreateDangerousEffect`

- `BuffData _normalEffectBuff`

- `BuffData _rareEffectBuff`

- `BuffData _dangerousEffectBuff`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateEffectForUnitsFunLiveModeOnly : ActionNode, IBuffSource, ICreateBuffNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _onlyCreateDangerousEffect; // 0x14
	private BuffData _normalEffectBuff; // 0x18
	private BuffData _rareEffectBuff; // 0x20
	private BuffData _dangerousEffectBuff; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f52578 VA: 0x759456a578
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f525e0 VA: 0x759456a5e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f52b34 VA: 0x759456ab34
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f52ce0 VA: 0x759456ace0
	public Void .ctor() { }
}
```