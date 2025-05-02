# RO4DLC2TriggerBossSealTileSkill

**Namespace:** ` `


## Fields

- `String _evnSysKey`

- `String _startColKey`

- `String _endColKey`

- `String _intervalKey`

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RO4DLC2TriggerBossSealTileSkill : ActionNode
{
	private String _evnSysKey; // 0x10
	private String _startColKey; // 0x18
	private String _endColKey; // 0x20
	private String _intervalKey; // 0x28
	private ActionTargetType _target; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd34d0 VA: 0x75945eb4d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd3538 VA: 0x75945eb538
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd3794 VA: 0x75945eb794
	public Void .ctor() { }
}
```