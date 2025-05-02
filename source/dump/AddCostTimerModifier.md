# AddCostTimerModifier

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Single _value`

- `String _blackboardKey`

- `Int32 _priority`

- `Boolean _costAddLocked`

- `String _costAddLockedBB`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddCostTimerModifier : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Single _value; // 0x14
	private String _blackboardKey; // 0x18
	private Int32 _priority; // 0x20
	private Boolean _costAddLocked; // 0x24
	private String _costAddLockedBB; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0be30 VA: 0x7594523e30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0be98 VA: 0x7594523e98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0c07c VA: 0x759452407c
	public Void .ctor() { }
}
```