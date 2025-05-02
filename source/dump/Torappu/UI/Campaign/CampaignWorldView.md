# CampaignWorldView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Boolean m_inited`

- `Action <onViewInited>k__BackingField`


## Properties

- `Action onViewInited`

- `Boolean inited`


## Methods

- `Action get_onViewInited()`

- `Void set_onViewInited(Action)`

- `Void set_onZoneClicked(Action`1)`

- `Boolean get_inited()`

- `Void StopEffect()`

- `CampaignWorldRegionView GetRegionView(String)`

- `CampaignWorldZoneView GetZoneView(String)`

- `CampaignWorldStageView GetStageView(String)`

- `Void _InitIfNot()`

- `CampaignWorldRegionHolder _GetRegionHolder(String)`

- `CampaignWorldZoneHolder _GetZoneHolder(String)`

- `CampaignWorldStageHolder _GetStageHolder(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldView : DataBinder`1
{
	private List`1 _imageMapPieces; // 0x20
	private Boolean m_inited; // 0x28
	private List`1 m_regionHolders; // 0x30
	private List`1 m_zoneHolders; // 0x38
	private List`1 m_stageHolders; // 0x40
	private Action <onViewInited>k__BackingField; // 0x48
	private Action`1 <onZoneClicked>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onViewInited; // 0x0
	private static DelegateBridge __Hotfix0_set_onViewInited; // 0x8
	private static DelegateBridge __Hotfix0_get_onZoneClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onZoneClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_inited; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_StopEffect; // 0x30
	private static DelegateBridge __Hotfix0_GetRegionView; // 0x38
	private static DelegateBridge __Hotfix0_GetZoneView; // 0x40
	private static DelegateBridge __Hotfix0_GetStageView; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__GetRegionHolder; // 0x58
	private static DelegateBridge __Hotfix0__GetZoneHolder; // 0x60
	private static DelegateBridge __Hotfix0__GetStageHolder; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Action onViewInited { get; set; }
	public Action`1 onZoneClicked { get; set; }
	public Boolean inited { get; }

	// RVA: 0x2dd5b44 VA: 0x75953edb44
	public Action get_onViewInited() { }
	// RVA: 0x2dd5bac VA: 0x75953edbac
	public Void set_onViewInited(Action value) { }
	// RVA: 0x2dd5c30 VA: 0x75953edc30
	public Action`1 get_onZoneClicked() { }
	// RVA: 0x2dd5c98 VA: 0x75953edc98
	public Void set_onZoneClicked(Action`1 value) { }
	// RVA: 0x2dd5d1c VA: 0x75953edd1c
	public Boolean get_inited() { }
	// RVA: 0x2dd5d84 VA: 0x75953edd84
	public override Void OnValueChanged(CampaignWorldViewProperty property) { }
	// RVA: 0x2dd723c VA: 0x75953ef23c
	public Void StopEffect() { }
	// RVA: 0x2dd7630 VA: 0x75953ef630
	public CampaignWorldRegionView GetRegionView(String regionId) { }
	// RVA: 0x2dd77a8 VA: 0x75953ef7a8
	public CampaignWorldZoneView GetZoneView(String zoneId) { }
	// RVA: 0x2dd7920 VA: 0x75953ef920
	public CampaignWorldStageView GetStageView(String stageId) { }
	// RVA: 0x2dd6564 VA: 0x75953ee564
	private Void _InitIfNot() { }
	// RVA: 0x2dd6904 VA: 0x75953ee904
	private CampaignWorldRegionHolder _GetRegionHolder(String regionId) { }
	// RVA: 0x2dd6acc VA: 0x75953eeacc
	private CampaignWorldZoneHolder _GetZoneHolder(String zoneId) { }
	// RVA: 0x2dd7074 VA: 0x75953ef074
	private CampaignWorldStageHolder _GetStageHolder(String stageId) { }
	// RVA: 0x2dd7a98 VA: 0x75953efa98
	public Void .ctor() { }
}
```