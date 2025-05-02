# BossRushRelicViewModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String actId`

- `Int32 tokenCount`

- `String tokenName`

- `String selectingRelicId`

- `Boolean selectingChange`

- `String relicUpgradeItemId`

- `Int32 enterAnimTick`


## Methods

- `Void LoadData(String)`

- `Void UpdateByPlayerData(Boolean)`

- `RelicInfo _GetPlayerRelicData()`

- `Void SetRelic(String)`

- `Boolean CompletedRelicUpgrade()`

- `BossRushRelicNodeModel GetRelicNodeModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 tokenCount; // 0x18
	public String tokenName; // 0x20
	public String selectingRelicId; // 0x28
	public Boolean selectingChange; // 0x30
	public ListDict`2 nodeViewModelDic; // 0x38
	public String relicUpgradeItemId; // 0x40
	public Int32 enterAnimTick; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateByPlayerData; // 0x8
	private static DelegateBridge __Hotfix0__GetPlayerRelicData; // 0x10
	private static DelegateBridge __Hotfix0_SetRelic; // 0x18
	private static DelegateBridge __Hotfix0_CompletedRelicUpgrade; // 0x20
	private static DelegateBridge __Hotfix0_GetRelicNodeModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2e60e60 VA: 0x7595478e60
	public Void LoadData(String actId) { }
	// RVA: 0x2e6148c VA: 0x759547948c
	public Void UpdateByPlayerData(Boolean refreshSelect) { }
	// RVA: 0x2e6165c VA: 0x759547965c
	private RelicInfo _GetPlayerRelicData() { }
	// RVA: 0x2e617fc VA: 0x75954797fc
	public Void SetRelic(String sRelicId) { }
	// RVA: 0x2e60448 VA: 0x7595478448
	public Boolean CompletedRelicUpgrade() { }
	// RVA: 0x2e619d0 VA: 0x75954799d0
	public BossRushRelicNodeModel GetRelicNodeModel(String relicId) { }
	// RVA: 0x2e61af8 VA: 0x7595479af8
	public Void .ctor() { }
}
```