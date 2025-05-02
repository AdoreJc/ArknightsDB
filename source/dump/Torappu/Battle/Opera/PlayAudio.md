# PlayAudio

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _signal`


## Methods

- `Void GatherAudio(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class PlayAudio : OperaNode, IAudioSource
{
	private String _signal; // 0x18
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c5ffc8 VA: 0x7594277fc8
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c6002c VA: 0x759427802c
	protected override Void DoExecute() { }
	// RVA: 0x1c60218 VA: 0x7594278218
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x1c6030c VA: 0x759427830c
	public Void .ctor() { }
}
```