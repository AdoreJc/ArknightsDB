# ForceCharacterFaceDefaultDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _force`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ForceCharacterFaceDefaultDirection : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _force; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f560f8 VA: 0x759456e0f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f56160 VA: 0x759456e160
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f562d8 VA: 0x759456e2d8
	public Void .ctor() { }
}
```