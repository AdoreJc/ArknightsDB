# CampaignZoneMapJumpItem

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Image _zoneIcon`

- `Text _stageCode`

- `Text _stageName`

- `Text _stageType`

- `GameObject _commonBack`

- `GameObject _alreadyFinishBack`

- `GameObject _newBack`

- `Transform _trackPoint`

- `RectTransform _trackPointHolder`

- `CampaignZoneJumpEvent onClick`

- `GameObject m_trackPoint`

- `CampaignZoneJumpViewModel m_cacheJumpViewModel`


## Methods

- `Void Render(CampaignZoneJumpViewModel)`

- `Void OnClick()`

- `Void _RenderTrackPoint(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapJumpItem : MonoBehaviour, IHotfixable
{
	private Image _zoneIcon; // 0x18
	private Text _stageCode; // 0x20
	private Text _stageName; // 0x28
	private Text _stageType; // 0x30
	private GameObject _commonBack; // 0x38
	private GameObject _alreadyFinishBack; // 0x40
	private GameObject _newBack; // 0x48
	private Transform _trackPoint; // 0x50
	private RectTransform _trackPointHolder; // 0x58
	public CampaignZoneJumpEvent onClick; // 0x60
	private GameObject m_trackPoint; // 0x68
	private CampaignZoneJumpViewModel m_cacheJumpViewModel; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__RenderTrackPoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2e4c2c0 VA: 0x75954642c0
	public Void Render(CampaignZoneJumpViewModel jumpViewModel) { }
	// RVA: 0x2e4c6fc VA: 0x75954646fc
	public Void OnClick() { }
	// RVA: 0x2e4c4f8 VA: 0x75954644f8
	private Void _RenderTrackPoint(Boolean hasUnconfirmed) { }
	// RVA: 0x2e4c794 VA: 0x7595464794
	public Void .ctor() { }
}
```