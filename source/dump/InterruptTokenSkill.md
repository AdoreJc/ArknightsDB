# InterruptTokenSkill

**Namespace:** ` `


## Fields

- `ActionTargetType _hostType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptTokenSkill : ActionNode
{
	private ActionTargetType _hostType; // 0x10
	private List`1 m_tokens; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8d828 VA: 0x75945a5828
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8d890 VA: 0x75945a5890
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8db70 VA: 0x75945a5b70
	public Void .ctor() { }
}
```