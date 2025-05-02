# CreateBuffInArea

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `GridPosition _min`

- `GridPosition _max`

- `BuffData _buff`


## Methods

- `Void GatherBuffs(List`1)`

- `Boolean _CheckInArea(GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class CreateBuffInArea : OperaNode, IBuffSource
{
	private GridPosition _min; // 0x14
	private GridPosition _max; // 0x1c
	private BuffData _buff; // 0x28
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0__CheckInArea; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c61900 VA: 0x7594279900
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c61964 VA: 0x7594279964
	protected override Void DoExecute() { }
	// RVA: 0x1c61e7c VA: 0x7594279e7c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1c61d28 VA: 0x7594279d28
	private Boolean _CheckInArea(GridPosition grid) { }
	// RVA: 0x1c61f70 VA: 0x7594279f70
	public Void .ctor() { }
}
```