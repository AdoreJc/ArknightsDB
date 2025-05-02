# ModifyGraphicHolderHeight

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Single _offset`

- `String _OffsetKey`

- `Single _duration`

- `String _durationKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyGraphicHolderHeight : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Single _offset; // 0x14
	private String _OffsetKey; // 0x18
	private Single _duration; // 0x20
	private String _durationKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc4ca8 VA: 0x75945dcca8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc4d10 VA: 0x75945dcd10
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc4ef8 VA: 0x75945dcef8
	public Void .ctor() { }
}
```