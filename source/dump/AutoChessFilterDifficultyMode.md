# AutoChessFilterDifficultyMode

**Namespace:** ` `


## Fields

- `Act1VAutoChessModeType _mode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessFilterDifficultyMode : ActionNode
{
	private Act1VAutoChessModeType _mode; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee75f4 VA: 0x75944ff5f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee765c VA: 0x75944ff65c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee7724 VA: 0x75944ff724
	public Void .ctor() { }
}
```