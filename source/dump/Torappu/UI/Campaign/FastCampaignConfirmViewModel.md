# FastCampaignConfirmViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Int32 sweepCount`

- `Int32 curShard`

- `Int32 shardLimit`

- `Int32 gainShard`

- `Boolean mayUseLowerGainLadder`


## Methods

- `Void LoadData(String, CampaignStageType)`

- `ConsumableInfo GetNextTicketToCost()`

- `Single GetCurShardProgress()`

- `Single GetGainShardProgress()`

- `Int32 GetGainTargetShard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class FastCampaignConfirmViewModel : IHotfixable
{
	public Int32 sweepCount; // 0x10
	public Int32 curShard; // 0x14
	public Int32 shardLimit; // 0x18
	public Int32 gainShard; // 0x1c
	public Boolean mayUseLowerGainLadder; // 0x20
	public List`1 tktList; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetNextTicketToCost; // 0x8
	private static DelegateBridge __Hotfix0__SortSweepTicket; // 0x10
	private static DelegateBridge __Hotfix0_GetCurShardProgress; // 0x18
	private static DelegateBridge __Hotfix0_GetGainShardProgress; // 0x20
	private static DelegateBridge __Hotfix0_GetGainTargetShard; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ddd684 VA: 0x75953f5684
	public Void LoadData(String stageId, CampaignStageType stageType) { }
	// RVA: 0x2ddd914 VA: 0x75953f5914
	public ConsumableInfo GetNextTicketToCost() { }
	// RVA: 0x2ddda9c VA: 0x75953f5a9c
	private static Int32 _SortSweepTicket(ConsumableInfo lhs, ConsumableInfo rhs) { }
	// RVA: 0x2ddbbcc VA: 0x75953f3bcc
	public Single GetCurShardProgress() { }
	// RVA: 0x2ddbc50 VA: 0x75953f3c50
	public Single GetGainShardProgress() { }
	// RVA: 0x2ddbcdc VA: 0x75953f3cdc
	public Int32 GetGainTargetShard() { }
	// RVA: 0x2ddd9d8 VA: 0x75953f59d8
	public Void .ctor() { }
}
```