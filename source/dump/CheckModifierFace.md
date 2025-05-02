# CheckModifierFace

**Namespace:** ` `


## Fields

- `Single _angle`

- `Boolean _backward`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckModifierFace : ActionNode
{
	private Single _angle; // 0x10
	private Boolean _backward; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f72a38 VA: 0x759458aa38
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f72aa0 VA: 0x759458aaa0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f72e90 VA: 0x759458ae90
	public Void .ctor() { }
}
```