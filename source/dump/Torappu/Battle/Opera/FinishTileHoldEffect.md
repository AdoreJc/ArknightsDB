# FinishTileHoldEffect

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _effectKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class FinishTileHoldEffect : OperaNode
{
	private String _effectKey; // 0x18
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c612b4 VA: 0x75942792b4
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c61318 VA: 0x7594279318
	protected override Void DoExecute() { }
	// RVA: 0x1c614b0 VA: 0x75942794b0
	public Void .ctor() { }
}
```