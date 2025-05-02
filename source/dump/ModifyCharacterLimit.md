# ModifyCharacterLimit

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _blackboardKey`

- `Boolean _isMins`

- `Boolean _getPlayerSideSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCharacterLimit : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _blackboardKey; // 0x18
	private Boolean _isMins; // 0x20
	private Boolean _getPlayerSideSource; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0c8bc VA: 0x75945248bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0c924 VA: 0x7594524924
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0cc28 VA: 0x7594524c28
	public Void .ctor() { }
}
```