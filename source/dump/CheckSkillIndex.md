# CheckSkillIndex

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Int32 _skillIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckSkillIndex : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Int32 _skillIndex; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f297c0 VA: 0x75945417c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f29828 VA: 0x7594541828
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f29a34 VA: 0x7594541a34
	public Void .ctor() { }
}
```