# UpdateObjectScaleViaRemainingRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Single _minScale`

- `Single _maxScale`

- `MountPointType _mountPointType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateObjectScaleViaRemainingRatio : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Single _minScale; // 0x14
	private Single _maxScale; // 0x18
	private MountPointType _mountPointType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f56be8 VA: 0x759456ebe8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f56c50 VA: 0x759456ec50
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f56e54 VA: 0x759456ee54
	public Void .ctor() { }
}
```