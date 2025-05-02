# AddHeightOffsetToSpine

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Single _offset`

- `Boolean _instant`

- `String _blackboardKey`

- `Boolean isSet`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddHeightOffsetToSpine : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Single _offset; // 0x14
	private Boolean _instant; // 0x18
	private String _blackboardKey; // 0x20
	private Boolean isSet; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc49ec VA: 0x75945dc9ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc4a54 VA: 0x75945dca54
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc4c08 VA: 0x75945dcc08
	public Void .ctor() { }
}
```