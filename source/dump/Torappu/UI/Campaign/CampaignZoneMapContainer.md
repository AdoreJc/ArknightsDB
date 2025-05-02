# CampaignZoneMapContainer

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Transform _container`

- `UIStringEvent _onStageClick`

- `Image _icon`

- `Text _zoneName`

- `Text _zoneNameShadow`

- `RectTransform _trackPointContainer`

- `CampaignTemplateZoneMap m_map`

- `GameObject m_trackPoint`

- `String m_cacheSelectId`


## Methods

- `Void RenderFirstTime(CampaignZoneMapViewModel)`

- `Void RefreshViewModel(CampaignZoneMapViewModel)`

- `Void ApplySelectState(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapContainer : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private UIStringEvent _onStageClick; // 0x20
	private Image _icon; // 0x28
	private Text _zoneName; // 0x30
	private Text _zoneNameShadow; // 0x38
	private RectTransform _trackPointContainer; // 0x40
	private CampaignTemplateZoneMap m_map; // 0x48
	private GameObject m_trackPoint; // 0x50
	private String m_cacheSelectId; // 0x58
	private static DelegateBridge __Hotfix0_RenderFirstTime; // 0x0
	private static DelegateBridge __Hotfix0_RefreshViewModel; // 0x8
	private static DelegateBridge __Hotfix0_ApplySelectState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2e4bd4c VA: 0x7595463d4c
	public Void RenderFirstTime(CampaignZoneMapViewModel zoneViewModel) { }
	// RVA: 0x2e4c034 VA: 0x7595464034
	public Void RefreshViewModel(CampaignZoneMapViewModel zoneViewModel) { }
	// RVA: 0x2e4c16c VA: 0x759546416c
	public Void ApplySelectState(String stageId) { }
	// RVA: 0x2e4c250 VA: 0x7595464250
	public Void .ctor() { }
}
```