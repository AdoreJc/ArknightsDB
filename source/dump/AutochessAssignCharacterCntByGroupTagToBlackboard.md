# AutochessAssignCharacterCntByGroupTagToBlackboard

**Namespace:** ` `


## Fields

- `String _groupTag`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessAssignCharacterCntByGroupTagToBlackboard : ActionNode
{
	private String _groupTag; // 0x10
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee3eec VA: 0x75944fbeec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee3f54 VA: 0x75944fbf54
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee412c VA: 0x75944fc12c
	public Void .ctor() { }
}
```