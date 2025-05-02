# SetCameraMoveDirectlyDisableState

**Namespace:** ` `


## Fields

- `Boolean disableCameraMoveDirectly`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetCameraMoveDirectlyDisableState : ActionNode
{
	private Boolean disableCameraMoveDirectly; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fda04c VA: 0x75945f204c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fda0b4 VA: 0x75945f20b4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fda17c VA: 0x75945f217c
	public Void .ctor() { }
}
```