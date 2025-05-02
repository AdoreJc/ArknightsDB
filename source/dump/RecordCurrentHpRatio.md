# RecordCurrentHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _recordKey`

- `Boolean _needOffset`

- `RecordType _recordType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RecordCurrentHpRatio : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _recordKey; // 0x18
	private Boolean _needOffset; // 0x20
	private RecordType _recordType; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc76bc VA: 0x75945df6bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc7724 VA: 0x75945df724
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc797c VA: 0x75945df97c
	public Void .ctor() { }
}
```