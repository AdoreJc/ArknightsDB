# CampaignZoneViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Int32 campaignTotalFee`

- `Int32 campaignCurrentFee`

- `CampaignGroupViewModel currentActiveGroup`


## Methods

- `Boolean ContainsCampaignStage(String)`

- `Void RefreshData()`

- `Void _LoadCampaignCommonData()`

- `Void _LoadCampaignInstanceData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class CampaignZoneViewModel : ZoneViewModel
{
	public ListDict`2 campaigns; // 0x90
	public Int32 campaignTotalFee; // 0x98
	public Int32 campaignCurrentFee; // 0x9c
	public CampaignGroupViewModel currentActiveGroup; // 0xa0


	// RVA: 0x2fcac78 VA: 0x75955e2c78
	public override Int32 CompareTo(ZoneViewModel otherModel) { }
	// RVA: 0x2fcad48 VA: 0x75955e2d48
	public Boolean ContainsCampaignStage(String stageId) { }
	// RVA: 0x2fcada0 VA: 0x75955e2da0
	public override Void LoadExtraData(String zoneId) { }
	// RVA: 0x2fcaeb4 VA: 0x75955e2eb4
	public override Void LateInitAfterStageLoaded() { }
	// RVA: 0x2fcb0bc VA: 0x75955e30bc
	public Void RefreshData() { }
	// RVA: 0x2fcada4 VA: 0x75955e2da4
	private Void _LoadCampaignCommonData() { }
	// RVA: 0x2fcaeb8 VA: 0x75955e2eb8
	private Void _LoadCampaignInstanceData() { }
	// RVA: 0x2fcb0dc VA: 0x75955e30dc
	public Void .ctor() { }
}
```