# CheckBuffRemainingTime

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Boolean _useSnapshotBuff`

- `String _buffKey`

- `CompareType _condType`

- `Single _checkTime`


## Methods

- `Boolean NotUseSnapshotBuff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBuffRemainingTime : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Boolean _useSnapshotBuff; // 0x14
	private String _buffKey; // 0x18
	private CompareType _condType; // 0x20
	private Single _checkTime; // 0x24
	private static DelegateBridge __Hotfix0_NotUseSnapshotBuff; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f25e28 VA: 0x759453de28
	private Boolean NotUseSnapshotBuff() { }
	// RVA: 0x1f25e98 VA: 0x759453de98
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f25f00 VA: 0x759453df00
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f26150 VA: 0x759453e150
	public Void .ctor() { }
}
```