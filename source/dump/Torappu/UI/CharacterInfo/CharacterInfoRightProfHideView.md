# CharacterInfoRightProfHideView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _subProfImg`

- `Text _subProfName`

- `GameObject _noUniequipPart`

- `GameObject _haveUniequipPart`

- `GameObject _lockedUniequipPart`

- `UICommonEquipTypeIcon _commonIcon`

- `Transform _commonIconContainer`

- `Text _uniequipLevel`

- `CharacterInfoTalentGroup _contentGroup`

- `UICommonTrackPoint _trackPoint`

- `TrackPointViewProperty m_missionTrackPointProp`

- `UICommonEquipTypeIcon m_icon`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightProfHideView : MonoBehaviour, IHotfixable
{
	private Image _subProfImg; // 0x18
	private Text _subProfName; // 0x20
	private GameObject _noUniequipPart; // 0x28
	private GameObject _haveUniequipPart; // 0x30
	private GameObject _lockedUniequipPart; // 0x38
	private UICommonEquipTypeIcon _commonIcon; // 0x40
	private Transform _commonIconContainer; // 0x48
	private Text _uniequipLevel; // 0x50
	private CharacterInfoTalentGroup _contentGroup; // 0x58
	private UICommonTrackPoint _trackPoint; // 0x60
	private TrackPointViewProperty m_missionTrackPointProp; // 0x68
	private UICommonEquipTypeIcon m_icon; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d828dc VA: 0x759539a8dc
	private Void _InitIfNot() { }
	// RVA: 0x2d829f4 VA: 0x759539a9f4
	public Void Render(CharViewModel viewModel) { }
	// RVA: 0x2d82f50 VA: 0x759539af50
	public Void .ctor() { }
}
```