# PlayCameraEffect

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _effectKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class PlayCameraEffect : OperaNode
{
	private String _effectKey; // 0x18
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c60b48 VA: 0x7594278b48
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c60bac VA: 0x7594278bac
	protected override Void DoExecute() { }
	// RVA: 0x1c60c3c VA: 0x7594278c3c
	public Void .ctor() { }
}
```