# TrackEnemyInLaterWave

**Namespace:** ` `


## Fields

- `Int32 _nextWaveStride`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TrackEnemyInLaterWave : ActionNode
{
	private Int32 _nextWaveStride; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f968ec VA: 0x75945ae8ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f96954 VA: 0x75945ae954
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f96b18 VA: 0x75945aeb18
	public Void .ctor() { }
}
```