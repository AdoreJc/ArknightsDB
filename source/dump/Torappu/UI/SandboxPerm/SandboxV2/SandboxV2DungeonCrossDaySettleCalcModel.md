# SandboxV2DungeonCrossDaySettleCalcModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String surviveTitle`

- `String surviveDayBetween`

- `Int32 startDay`

- `Int32 endDay`

- `String scoreTotalTitle`

- `Int32 scoreTotal`

- `Int32 techCurRoundScore`

- `Boolean isTechHasReachMax`

- `Single techProgressBefore`

- `Single techProgressCurRound`

- `Int32 shopCurRoundScore`

- `Boolean isShopReachMaxScore`


## Methods

- `Void LoadData(SandboxV2Data, Dungeon, Tech)`

- `Void _RefreshTechInfo(SandboxV2Data, Tech, ReportSettle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDaySettleCalcModel : IHotfixable
{
	public String surviveTitle; // 0x10
	public String surviveDayBetween; // 0x18
	public Int32 startDay; // 0x20
	public Int32 endDay; // 0x24
	public String scoreTotalTitle; // 0x28
	public Int32 scoreTotal; // 0x30
	public Int32 techCurRoundScore; // 0x34
	public Boolean isTechHasReachMax; // 0x38
	public Single techProgressBefore; // 0x3c
	public Single techProgressCurRound; // 0x40
	public Int32 shopCurRoundScore; // 0x44
	public Boolean isShopReachMaxScore; // 0x48
	private const String DAY_BETWEEN_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__RefreshTechInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2523e6c VA: 0x7594b3be6c
	public Void LoadData(SandboxV2Data topicDetailData, Dungeon playerDungeonData, Tech techData) { }
	// RVA: 0x2525b98 VA: 0x7594b3db98
	private Void _RefreshTechInfo(SandboxV2Data topicDetailData, Tech techData, ReportSettle settle) { }
	// RVA: 0x2523dfc VA: 0x7594b3bdfc
	public Void .ctor() { }
}
```