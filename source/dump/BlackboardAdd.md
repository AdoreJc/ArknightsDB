# BlackboardAdd

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Int32 _addition`

- `String _additionKey`

- `Boolean _isFloat`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlackboardAdd : ActionNode
{
	private String _blackboardKey; // 0x10
	private Int32 _addition; // 0x18
	private String _additionKey; // 0x20
	private Boolean _isFloat; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eefe10 VA: 0x7594507e10
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eefe78 VA: 0x7594507e78
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef0004 VA: 0x7594508004
	public Void .ctor() { }
}
```