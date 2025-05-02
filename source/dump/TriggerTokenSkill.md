# TriggerTokenSkill

**Namespace:** ` `


## Fields

- `ActionTargetType _hostType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerTokenSkill : ActionNode
{
	private ActionTargetType _hostType; // 0x10
	private List`1 m_tokens; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8d464 VA: 0x75945a5464
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8d4cc VA: 0x75945a54cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8d75c VA: 0x75945a575c
	public Void .ctor() { }
}
```