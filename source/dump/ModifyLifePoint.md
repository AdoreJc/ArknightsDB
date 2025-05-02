# ModifyLifePoint

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _isSub`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyLifePoint : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _isSub; // 0x14
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0ccd0 VA: 0x7594524cd0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0cd38 VA: 0x7594524d38
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0cf30 VA: 0x7594524f30
	public Void .ctor() { }
}
```