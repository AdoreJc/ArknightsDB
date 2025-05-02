# ResetCardRespawnTime

**Namespace:** ` `


## Fields

- `String _blackBoardKey`

- `Boolean _waitFirstPeriod`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ResetCardRespawnTime : ActionNode
{
	private String _blackBoardKey; // 0x10
	private Boolean _waitFirstPeriod; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4ecac VA: 0x7594566cac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4ed14 VA: 0x7594566d14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4ee48 VA: 0x7594566e48
	public Void .ctor() { }
}
```