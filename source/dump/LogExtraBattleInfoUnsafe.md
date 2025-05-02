# LogExtraBattleInfoUnsafe

**Namespace:** ` `


## Fields

- `LogType _logType`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoUnsafe : ActionNode
{
	private LogType _logType; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eea4b4 VA: 0x75945024b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eea51c VA: 0x759450251c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eea6bc VA: 0x75945026bc
	public Void .ctor() { }
}
```