# Act38SideFilterFireworkCondition

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `Boolean _checkType`

- `FireworkType _fireworkType`

- `Boolean _checkLevel`

- `Int32 _fireworkLevel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act38SideFilterFireworkCondition : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private Boolean _checkType; // 0x1c
	private FireworkType _fireworkType; // 0x20
	private Boolean _checkLevel; // 0x24
	private Int32 _fireworkLevel; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee0d14 VA: 0x75944f8d14
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee0d7c VA: 0x75944f8d7c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee0f4c VA: 0x75944f8f4c
	public Void .ctor() { }
}
```