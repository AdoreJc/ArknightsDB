# IfBossRushBattleArea

**Namespace:** ` `


## Fields

- `Boolean _isFirstOnTheLeft`

- `Boolean _isFirstOnTheRight`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfBossRushBattleArea : ActionNode
{
	private Boolean _isFirstOnTheLeft; // 0x10
	private Boolean _isFirstOnTheRight; // 0x11
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef58dc VA: 0x759450d8dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef5944 VA: 0x759450d944
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef5b0c VA: 0x759450db0c
	public Void .ctor() { }
}
```