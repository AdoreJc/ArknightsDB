# CampaignWorldZoneView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Color _colorNormalCircle1`

- `Color _colorRotateCircle1`

- `Image _imageCircle1`

- `Image _imageCircle2`

- `GameObject _effectCircle`

- `Image _imageLocked`

- `RectTransform _panelInfo`

- `Image _imageIcon`

- `Image _imageIconShadow`

- `Text _textName`

- `Text _textNameShadow`

- `RectTransform _panelCountDown`

- `Text _textCountDown`

- `Image _imageCountDownShadow`

- `Transform _trackPointContainerLeft`

- `Transform _trackPointContainerRight`

- `Button _hotspotRect`

- `Button _hotspotCircle`

- `CampaignWorldZoneViewModel m_cacheModel`

- `GameObject m_trackPoint`

- `PanelInfoAlignment m_panelInfoAlignment`


## Properties

- `Bounds worldBounds`

- `Button hotspotCircle`


## Methods

- `Void set_onClicked(Action`1)`

- `Bounds get_worldBounds()`

- `Button get_hotspotCircle()`

- `Void Render(CampaignWorldZoneViewModel)`

- `Void StopEffect()`

- `Void EventOnClicked()`

- `Void _ApplyHolderConfig()`

- `Void _ApplyPanelInfoAlignment(RectTransform)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldZoneView : MonoBehaviour, IHotfixable
{
	private Color _colorNormalCircle1; // 0x18
	private Color _colorRotateCircle1; // 0x28
	private Image _imageCircle1; // 0x38
	private Image _imageCircle2; // 0x40
	private GameObject _effectCircle; // 0x48
	private Image _imageLocked; // 0x50
	private RectTransform _panelInfo; // 0x58
	private List`1 _panelInfoAlignRectTrans; // 0x60
	private Image _imageIcon; // 0x68
	private Image _imageIconShadow; // 0x70
	private Text _textName; // 0x78
	private Text _textNameShadow; // 0x80
	private RectTransform _panelCountDown; // 0x88
	private Text _textCountDown; // 0x90
	private Image _imageCountDownShadow; // 0x98
	private Transform _trackPointContainerLeft; // 0xa0
	private Transform _trackPointContainerRight; // 0xa8
	private Button _hotspotRect; // 0xb0
	private Button _hotspotCircle; // 0xb8
	private CampaignWorldZoneViewModel m_cacheModel; // 0xc0
	private GameObject m_trackPoint; // 0xc8
	private PanelInfoAlignment m_panelInfoAlignment; // 0xd0
	private Action`1 <onClicked>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_worldBounds; // 0x10
	private static DelegateBridge __Hotfix0_get_hotspotCircle; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_StopEffect; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x30
	private static DelegateBridge __Hotfix0__ApplyHolderConfig; // 0x38
	private static DelegateBridge __Hotfix0__ApplyPanelInfoAlignment; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Action`1 onClicked { get; set; }
	public Bounds worldBounds { get; }
	public Button hotspotCircle { get; }

	// RVA: 0x2dd7c1c VA: 0x75953efc1c
	public Action`1 get_onClicked() { }
	// RVA: 0x2dd6ff0 VA: 0x75953eeff0
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2dd7c84 VA: 0x75953efc84
	public Bounds get_worldBounds() { }
	// RVA: 0x2dd7d5c VA: 0x75953efd5c
	public Button get_hotspotCircle() { }
	// RVA: 0x2dd6c94 VA: 0x75953eec94
	public Void Render(CampaignWorldZoneViewModel viewModel) { }
	// RVA: 0x2dd75c0 VA: 0x75953ef5c0
	public Void StopEffect() { }
	// RVA: 0x2dd7dc4 VA: 0x75953efdc4
	public Void EventOnClicked() { }
	// RVA: 0x2dd7e64 VA: 0x75953efe64
	private Void _ApplyHolderConfig() { }
	// RVA: 0x2dd8128 VA: 0x75953f0128
	private Void _ApplyPanelInfoAlignment(RectTransform rectTrans) { }
	// RVA: 0x2dd82fc VA: 0x75953f02fc
	public Void Awake() { }
	// RVA: 0x2dd8364 VA: 0x75953f0364
	public Void .ctor() { }
}
```