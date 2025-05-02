# CoopReplaceActionKey

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `String _defaultKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CoopReplaceActionKey : ActionNode
{
	private String _blackboardKey; // 0x10
	private String _defaultKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f39518 VA: 0x7594551518
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f39580 VA: 0x7594551580
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f396d8 VA: 0x75945516d8
	public Void .ctor() { }
}
```