# LogExtraBattleInfoInstId

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoInstId : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eeba44 VA: 0x7594503a44
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eebaac VA: 0x7594503aac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eebd74 VA: 0x7594503d74
	public Void .ctor() { }
}
```