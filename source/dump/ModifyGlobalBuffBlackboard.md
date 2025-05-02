# ModifyGlobalBuffBlackboard

**Namespace:** ` `


## Fields

- `String _globalBuffKey`

- `String _blackboardKey`

- `Single _addition`

- `String _maxValKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyGlobalBuffBlackboard : ActionNode
{
	private String _globalBuffKey; // 0x10
	private String _blackboardKey; // 0x18
	private Single _addition; // 0x20
	private String _maxValKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7e210 VA: 0x7594596210
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7e278 VA: 0x7594596278
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7e50c VA: 0x759459650c
	public Void .ctor() { }
}
```