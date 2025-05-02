# PlayMapEffect

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _effectKey`

- `Boolean _holdByTile`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class PlayMapEffect : OperaNode, IOperaEffectSource
{
	private String _effectKey; // 0x18
	private Boolean _holdByTile; // 0x20
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c60ca8 VA: 0x7594278ca8
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c60d0c VA: 0x7594278d0c
	protected override Void DoExecute() { }
	// RVA: 0x1c60ff8 VA: 0x7594278ff8
	public Void GatherEffects(List`1 results) { }
	// RVA: 0x1c610ec VA: 0x75942790ec
	public Void .ctor() { }
}
```