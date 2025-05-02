# LogExtraBattleInfoForCurrentPlayTime

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoForCurrentPlayTime : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eeadc8 VA: 0x7594502dc8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eeae30 VA: 0x7594502e30
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eeb0e8 VA: 0x75945030e8
	public Void .ctor() { }
}
```