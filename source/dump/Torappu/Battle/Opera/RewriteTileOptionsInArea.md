# RewriteTileOptionsInArea

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `GridPosition _min`

- `GridPosition _max`

- `BuildableType _buildableType`

- `Boolean _restoreOptions`


## Methods

- `Boolean _CheckInArea(GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class RewriteTileOptionsInArea : OperaNode
{
	private GridPosition _min; // 0x14
	private GridPosition _max; // 0x1c
	private BuildableType _buildableType; // 0x24
	private Boolean _restoreOptions; // 0x28
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0__CheckInArea; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c6151c VA: 0x759427951c
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c61580 VA: 0x7594279580
	protected override Void DoExecute() { }
	// RVA: 0x1c61740 VA: 0x7594279740
	private Boolean _CheckInArea(GridPosition grid) { }
	// RVA: 0x1c61894 VA: 0x7594279894
	public Void .ctor() { }
}
```