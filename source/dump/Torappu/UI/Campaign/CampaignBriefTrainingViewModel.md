# CampaignBriefTrainingViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String groupId`

- `Boolean isNext`

- `Boolean isAllOpen`

- `String remainTimeStr`


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `Void LoadData(String, Boolean, Boolean)`

- `Void Clear()`

- `Void _AddStageInfo(String)`

- `StageInfoViewModel _GetStageInfoViewModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignBriefTrainingViewModel : IHotfixable
{
	public String groupId; // 0x10
	public Boolean isNext; // 0x18
	public Boolean isAllOpen; // 0x19
	public String remainTimeStr; // 0x20
	public List`1 stageInfoModels; // 0x28
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_Clear; // 0x10
	private static DelegateBridge __Hotfix0__AddStageInfo; // 0x18
	private static DelegateBridge __Hotfix0__GetStageInfoViewModel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isValid { get; }

	// RVA: 0x2dc53c0 VA: 0x75953dd3c0
	public Boolean get_isValid() { }
	// RVA: 0x2dc5438 VA: 0x75953dd438
	public Void LoadData(String groupId, Boolean isNext, Boolean isAllOpen) { }
	// RVA: 0x2dc5c6c VA: 0x75953ddc6c
	public Void Clear() { }
	// RVA: 0x2dc5a78 VA: 0x75953dda78
	private Void _AddStageInfo(String stageId) { }
	// RVA: 0x2dc5cf8 VA: 0x75953ddcf8
	private StageInfoViewModel _GetStageInfoViewModel(String zoneId) { }
	// RVA: 0x2dc5f90 VA: 0x75953ddf90
	public Void .ctor() { }
}
```