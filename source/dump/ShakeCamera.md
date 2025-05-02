# ShakeCamera

**Namespace:** ` `


## Fields

- `Single _duration`

- `Vector3 _strength`

- `Int32 _vibrato`

- `Single _randomness`

- `Boolean _allowNoSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShakeCamera : ActionNode
{
	private Single _duration; // 0x10
	private Vector3 _strength; // 0x14
	private Int32 _vibrato; // 0x20
	private Single _randomness; // 0x24
	private Boolean _allowNoSource; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f99f58 VA: 0x75945b1f58
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f99fc0 VA: 0x75945b1fc0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9a0e0 VA: 0x75945b20e0
	public Void .ctor() { }
}
```