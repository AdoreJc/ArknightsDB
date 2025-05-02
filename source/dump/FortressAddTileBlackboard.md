# FortressAddTileBlackboard

**Namespace:** ` `


## Fields

- `String _blackboardKey`

- `Boolean _clearBlackboard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FortressAddTileBlackboard : ActionNode
{
	private String _blackboardKey; // 0x10
	private Boolean _clearBlackboard; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f38b5c VA: 0x7594550b5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f38bc4 VA: 0x7594550bc4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f38e7c VA: 0x7594550e7c
	public Void .ctor() { }
}
```