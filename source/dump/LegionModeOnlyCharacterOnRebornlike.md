# LegionModeOnlyCharacterOnRebornlike

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _inheritProfessionBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCharacterOnRebornlike : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _inheritProfessionBuff; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f65418 VA: 0x759457d418
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f65480 VA: 0x759457d480
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f656d0 VA: 0x759457d6d0
	public Void .ctor() { }
}
```