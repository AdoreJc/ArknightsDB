# LogExtraBattleInfoForBossRush

**Namespace:** ` `


## Fields

- `InfoType _infoType`

- `String _key`

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoForBossRush : ActionNode
{
	private InfoType _infoType; // 0x10
	private String _key; // 0x18
	private ActionTargetType _target; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef5fe8 VA: 0x759450dfe8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef6050 VA: 0x759450e050
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef65bc VA: 0x759450e5bc
	public Void .ctor() { }
}
```