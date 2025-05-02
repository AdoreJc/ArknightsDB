# PlayScreenEffect

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _effectKey`

- `Boolean _holdEffect`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class PlayScreenEffect : OperaNode, IOperaEffectSource
{
	private String _effectKey; // 0x18
	private Boolean _holdEffect; // 0x20
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c60884 VA: 0x7594278884
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c608e8 VA: 0x75942788e8
	protected override Void DoExecute() { }
	// RVA: 0x1c609e8 VA: 0x75942789e8
	public Void GatherEffects(List`1 results) { }
	// RVA: 0x1c60adc VA: 0x7594278adc
	public Void .ctor() { }
}
```