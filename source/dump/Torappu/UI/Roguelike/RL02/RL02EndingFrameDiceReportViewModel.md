# RL02EndingFrameDiceReportViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Int32 diceRollTotalTimes`

- `DiceResultInfo bestDiceResultInfo`

- `DiceResultInfo worstDiceResultInfo`

- `DiceResultType diceResultType`


## Methods

- `Int32 _Compare(DiceResultInfo, DiceResultInfo)`

- `Int32 <LoadData>b__9_0(DiceResultInfo, DiceResultInfo)`

- `Int32 <LoadData>b__9_1(DiceResultInfo, DiceResultInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02EndingFrameDiceReportViewModel : RL02EndingFrameReportViewModel
{
	public Int32[] diceRollTimes; // 0x18
	public Int32 diceRollTotalTimes; // 0x20
	public DiceResultInfo bestDiceResultInfo; // 0x28
	public DiceResultInfo worstDiceResultInfo; // 0x50
	public DiceResultType diceResultType; // 0x78
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__Compare; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override ReportViewType viewType { get; }

	// RVA: 0x2b68934 VA: 0x7595180934
	public override ReportViewType get_viewType() { }
	// RVA: 0x2b6899c VA: 0x759518099c
	protected override Boolean LoadData(String topicId, RL02EndingFrameViewModel dataSource) { }
	// RVA: 0x2b690bc VA: 0x75951810bc
	private Int32 _Compare(DiceResultInfo lhs, DiceResultInfo rhs) { }
	// RVA: 0x2b691e8 VA: 0x75951811e8
	public Void .ctor() { }
	// RVA: 0x2b69290 VA: 0x7595181290
	private Int32 <LoadData>b__9_0(DiceResultInfo lhs, DiceResultInfo rhs) { }
	// RVA: 0x2b692d0 VA: 0x75951812d0
	private Int32 <LoadData>b__9_1(DiceResultInfo lhs, DiceResultInfo rhs) { }
}
```