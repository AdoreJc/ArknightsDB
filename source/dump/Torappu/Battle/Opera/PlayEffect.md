# PlayEffect

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `String _effectKey`

- `Boolean _holdByTile`

- `PostprocessMask _postProcessType`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class PlayEffect : OperaNode, IOperaEffectSource
{
	private String _effectKey; // 0x18
	private Boolean _holdByTile; // 0x20
	private PostprocessMask _postProcessType; // 0x21
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c60378 VA: 0x7594278378
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c603dc VA: 0x75942783dc
	protected override Void DoExecute() { }
	// RVA: 0x1c60724 VA: 0x7594278724
	public Void GatherEffects(List`1 results) { }
	// RVA: 0x1c60818 VA: 0x7594278818
	public Void .ctor() { }
}
```