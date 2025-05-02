# RoguelikeLogExpUseSerializedTrapID

**Namespace:** ` `


## Fields

- `String _expKey`

- `String _trapID`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeLogExpUseSerializedTrapID : ActionNode
{
	private String _expKey; // 0x10
	private String _trapID; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7f5e4 VA: 0x75945975e4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7f64c VA: 0x759459764c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7f7bc VA: 0x75945977bc
	public Void .ctor() { }
}
```