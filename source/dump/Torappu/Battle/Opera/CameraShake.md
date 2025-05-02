# CameraShake

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `Single _duration`

- `Vector3 _strength`

- `Int32 _vibrato`

- `Single _randomness`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class CameraShake : OperaNode
{
	private Single _duration; // 0x14
	private Vector3 _strength; // 0x18
	private Int32 _vibrato; // 0x24
	private Single _randomness; // 0x28
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c5f268 VA: 0x7594277268
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c5f2cc VA: 0x75942772cc
	protected override Void DoExecute() { }
	// RVA: 0x1c5f368 VA: 0x7594277368
	public Void .ctor() { }
}
```