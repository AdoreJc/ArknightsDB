# CampaignZoneMapJumpView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `GameObject _rotateGameObject`

- `Transform _rotateContainer`

- `SimpleLayoutContent _permContent`

- `SimpleLayoutContent _trainContent`

- `CampaignZoneMapJumpItem _jumpItem`

- `CampaignZoneJumpEvent _jumpEvent`

- `Text _rotateRemainText`

- `Text _trainRemainText`

- `GameObject _trainCommonPart`

- `GameObject _trainAllOpenPart`

- `Image _clockIcon`

- `CampaignZoneMapJumpItem m_rotateJumpItem`

- `Adapter m_permAdapter`

- `Adapter m_trainAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderView(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapJumpView : MonoBehaviour, IHotfixable
{
	private GameObject _rotateGameObject; // 0x18
	private Transform _rotateContainer; // 0x20
	private SimpleLayoutContent _permContent; // 0x28
	private SimpleLayoutContent _trainContent; // 0x30
	private CampaignZoneMapJumpItem _jumpItem; // 0x38
	private CampaignZoneJumpEvent _jumpEvent; // 0x40
	private Text _rotateRemainText; // 0x48
	private Text _trainRemainText; // 0x50
	private GameObject _trainCommonPart; // 0x58
	private GameObject _trainAllOpenPart; // 0x60
	private Image _clockIcon; // 0x68
	private CampaignZoneMapJumpItem m_rotateJumpItem; // 0x70
	private Adapter m_permAdapter; // 0x78
	private Adapter m_trainAdapter; // 0x80
	private Boolean m_isInited; // 0x88
	public const String GRAY_COLOR; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e4d9a0 VA: 0x75954659a0
	private Void _InitIfNot() { }
	// RVA: 0x2e4cf04 VA: 0x7595464f04
	public Void RenderView(List`1 viewModelList) { }
	// RVA: 0x2e4dbc0 VA: 0x7595465bc0
	public Void .ctor() { }
}
```