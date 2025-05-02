# CharacterInfoSpCharInfoViewController

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _imageFavor`

- `GameObject _panelSpCharInfo`

- `GameObject _panelPopup`

- `GameObject _panelSpCharInfoMission`

- `GameObject _panelSpCharInfoMissionComplete`

- `Text _textSpCharNames`

- `Text _textMissionDesc`

- `Text _textMissionInProgress`

- `GameObject _panelMission`

- `GameObject _panelMissionInProgress`

- `GameObject _panelMissionHasReward`

- `UICommonTrackPoint _missionTrackPoint`

- `Boolean m_inited`

- `SpCharInfoViewModel m_cacheModel`

- `TrackPointViewProperty m_missionTrackPointProp`


## Methods

- `Void OnFavorShow()`

- `Void OnFavorDisable()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSpCharInfoViewController : DataBinder`1
{
	private Image _imageFavor; // 0x20
	private GameObject _panelSpCharInfo; // 0x28
	private GameObject _panelPopup; // 0x30
	private GameObject _panelSpCharInfoMission; // 0x38
	private GameObject _panelSpCharInfoMissionComplete; // 0x40
	private Text _textSpCharNames; // 0x48
	private Text _textMissionDesc; // 0x50
	private Text _textMissionInProgress; // 0x58
	private GameObject _panelMission; // 0x60
	private GameObject _panelMissionInProgress; // 0x68
	private GameObject _panelMissionHasReward; // 0x70
	private UICommonTrackPoint _missionTrackPoint; // 0x78
	private Boolean m_inited; // 0x80
	private SpCharInfoViewModel m_cacheModel; // 0x88
	private TrackPointViewProperty m_missionTrackPointProp; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnFavorShow; // 0x8
	private static DelegateBridge __Hotfix0_OnFavorDisable; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d68f78 VA: 0x7595380f78
	public override Void OnValueChanged(CharInfoGroupProperty property) { }
	// RVA: 0x2d693b4 VA: 0x75953813b4
	public Void OnFavorShow() { }
	// RVA: 0x2d6946c VA: 0x759538146c
	public Void OnFavorDisable() { }
	// RVA: 0x2d6930c VA: 0x759538130c
	private Void _InitIfNot() { }
	// RVA: 0x2d69508 VA: 0x7595381508
	public Void .ctor() { }
}
```