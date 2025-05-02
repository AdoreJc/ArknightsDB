# GlobalAudio

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _signal`

- `Vector3 _position`


## Methods

- `Void GatherAudio(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class GlobalAudio : OperaNode, IAudioSource
{
	private String _signal; // 0x18
	private Vector3 _position; // 0x20
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c5fd28 VA: 0x7594277d28
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c5fd8c VA: 0x7594277d8c
	protected override Void DoExecute() { }
	// RVA: 0x1c5fe68 VA: 0x7594277e68
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x1c5ff5c VA: 0x7594277f5c
	public Void .ctor() { }
}
```