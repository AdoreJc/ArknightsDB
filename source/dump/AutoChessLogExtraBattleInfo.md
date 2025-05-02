# AutoChessLogExtraBattleInfo

**Namespace:** ` `


## Fields

- `String _key`

- `ActionTargetType _targetType`

- `LogType _logType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessLogExtraBattleInfo : ActionNode
{
	private String _key; // 0x10
	private ActionTargetType _targetType; // 0x18
	private LogType _logType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee4e94 VA: 0x75944fce94
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee4efc VA: 0x75944fcefc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee51b8 VA: 0x75944fd1b8
	public Void .ctor() { }
}
```