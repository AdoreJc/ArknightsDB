# CampaignWorldViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String curRotateStageId`

- `String curTrainingGroupId`

- `String curTrainingAllOpenGroupId`

- `String briefId`

- `String focusStartStageId`

- `String focusTargetStageId`

- `String focusTargetRegionId`

- `Boolean needFocus`

- `Boolean needPlayFogDisappear`

- `Boolean needShowBrief`


## Methods

- `Void LoadData()`

- `Void _PostProcessData()`

- `String _CalcBriefId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldViewModel : IHotfixable
{
	public String curRotateStageId; // 0x10
	public String curTrainingGroupId; // 0x18
	public String curTrainingAllOpenGroupId; // 0x20
	public String briefId; // 0x28
	public String focusStartStageId; // 0x30
	public String focusTargetStageId; // 0x38
	public String focusTargetRegionId; // 0x40
	public Boolean needFocus; // 0x48
	public Boolean needPlayFogDisappear; // 0x49
	public Boolean needShowBrief; // 0x4a
	public List`1 worldMapPieceSprites; // 0x50
	public List`1 regionModels; // 0x58
	public List`1 zoneModels; // 0x60
	public List`1 stageModels; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__PostProcessData; // 0x8
	private static DelegateBridge __Hotfix0__CalcBriefId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2dd83d4 VA: 0x75953f03d4
	public Void LoadData() { }
	// RVA: 0x2dd96b4 VA: 0x75953f16b4
	private Void _PostProcessData() { }
	// RVA: 0x2dda050 VA: 0x75953f2050
	private String _CalcBriefId() { }
	// RVA: 0x2dda148 VA: 0x75953f2148
	public Void .ctor() { }
}
```