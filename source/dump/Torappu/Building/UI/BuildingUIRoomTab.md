# BuildingUIRoomTab

**Namespace:** `Torappu.Building.UI`


## Fields

- `SimpleLayoutContent _levelLayout`

- `GameObject _panelActive`

- `GameObject _panelLocked`

- `GameObject _panelTrackPoint`

- `GameObject _panelUpgrading`

- `GameObject _panelHotspot`

- `Text _textIndex`

- `TwoStateToggle _tglSelected`

- `BuildingRoomLevelView _levelView`

- `Color _colorTextSelected`

- `Color _colorTextUnselected`

- `Boolean m_isInited`

- `CacheStatus m_status`


## Methods

- `Void Render(BasicRoomInfoModel, Boolean)`

- `Void OnTabClicked()`

- `Void _RenderActive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUIRoomTab : MonoBehaviour, IHotfixable
{
	private const String LEVEL_ICON_NAME; // 0x0
	private SimpleLayoutContent _levelLayout; // 0x18
	private GameObject _panelActive; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelTrackPoint; // 0x30
	private GameObject _panelUpgrading; // 0x38
	private GameObject _panelHotspot; // 0x40
	private Text _textIndex; // 0x48
	private TwoStateToggle _tglSelected; // 0x50
	private BuildingRoomLevelView _levelView; // 0x58
	private Color _colorTextSelected; // 0x60
	private Color _colorTextUnselected; // 0x70
	private Boolean m_isInited; // 0x80
	private CacheStatus m_status; // 0x88
	public Action`1 onRoomSelected; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnTabClicked; // 0x8
	private static DelegateBridge __Hotfix0__RenderActive; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d436b8 VA: 0x759635b6b8
	public Void Render(BasicRoomInfoModel basicModel, Boolean isSelected) { }
	// RVA: 0x3d43ab4 VA: 0x759635bab4
	public Void OnTabClicked() { }
	// RVA: 0x3d43900 VA: 0x759635b900
	private Void _RenderActive() { }
	// RVA: 0x3d43b3c VA: 0x759635bb3c
	public Void .ctor() { }
}
```