# CreateBuffOnTileInRange

**Namespace:** ` `


## Fields

- `TargetOptions _targetOptions`

- `String _rangeId`

- `SideType _side`

- `Boolean _hasSource`

- `ActionTargetType _buffSourceType`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffOnTileInRange : ActionNode, IBuffSource
{
	private TargetOptions _targetOptions; // 0x10
	private String _rangeId; // 0x70
	private BuffData[] _buffs; // 0x78
	private SideType _side; // 0x80
	private Boolean _hasSource; // 0x84
	private ActionTargetType _buffSourceType; // 0x88
	private List`1 m_excludeTargets; // 0x90
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f049dc VA: 0x759451c9dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f04a44 VA: 0x759451ca44
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f05118 VA: 0x759451d118
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f051cc VA: 0x759451d1cc
	public Void .ctor() { }
}
```