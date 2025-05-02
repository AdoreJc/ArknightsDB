# WriteBossrushWaveCntToBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class WriteBossrushWaveCntToBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef6634 VA: 0x759450e634
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef669c VA: 0x759450e69c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef67dc VA: 0x759450e7dc
	public Void .ctor() { }
}
```