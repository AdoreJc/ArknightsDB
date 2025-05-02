# FinishCurrentWave

**Namespace:** ` `


## Fields

- `Boolean _trackSourceAtNextWave`

- `Int32 _trackSourceAtWaveDelta`

- `Boolean _trackAllManagedEnemiesAtNextWave`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishCurrentWave : ActionNode
{
	private Boolean _trackSourceAtNextWave; // 0x10
	private Int32 _trackSourceAtWaveDelta; // 0x14
	private Boolean _trackAllManagedEnemiesAtNextWave; // 0x18
	private ActionTargetType _sourceType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f96204 VA: 0x75945ae204
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9626c VA: 0x75945ae26c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f965a0 VA: 0x75945ae5a0
	public Void .ctor() { }
}
```