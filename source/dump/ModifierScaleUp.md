# ModifierScaleUp

**Namespace:** ` `


## Fields

- `String _scaleKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifierScaleUp : ActionNode
{
	private String _scaleKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f72508 VA: 0x759458a508
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f72570 VA: 0x759458a570
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f72780 VA: 0x759458a780
	public Void .ctor() { }
}
```