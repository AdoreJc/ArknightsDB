# ChangeAnimatorMeshRenderer

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Int32 _rendererIndex`

- `Boolean _enable`

- `Boolean _exclusive`

- `Boolean _rendererCurModeIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeAnimatorMeshRenderer : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Int32 _rendererIndex; // 0x14
	private Boolean _enable; // 0x18
	private Boolean _exclusive; // 0x19
	private Boolean _rendererCurModeIndex; // 0x1a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc8b74 VA: 0x75945e0b74
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc8bdc VA: 0x75945e0bdc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc8e7c VA: 0x75945e0e7c
	public Void .ctor() { }
}
```