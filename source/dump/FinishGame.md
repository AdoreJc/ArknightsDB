# FinishGame

**Namespace:** ` `


## Fields

- `GameResult _gameResult`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishGame : ActionNode
{
	private GameResult _gameResult; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fce2ec VA: 0x75945e62ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fce354 VA: 0x75945e6354
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fce424 VA: 0x75945e6424
	public Void .ctor() { }
}
```