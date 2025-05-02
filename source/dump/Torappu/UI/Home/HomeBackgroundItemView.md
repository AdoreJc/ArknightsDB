# HomeBackgroundItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _imgBgPreview`

- `GameObject _objImgMusic`

- `Text _textBgName`

- `GameObject _objPanelLockedNormal`

- `GameObject _objPanelSelected`

- `GameObject _objPanelLockSelected`

- `UICommonTrackPoint _newTrackPoint`

- `String m_cachedId`

- `HomeBackgroundItemModel m_dataModel`

- `Boolean m_isInited`

- `TrackPointViewProperty m_backgroundNewTrackProp`


## Methods

- `Void set_selectChanged(Action`1)`

- `Void _InitIfNot()`

- `Void Flush(HomeBackgroundItemModel)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundItemView : MonoBehaviour, IHotfixable
{
	private Image _imgBgPreview; // 0x18
	private GameObject _objImgMusic; // 0x20
	private Text _textBgName; // 0x28
	private GameObject _objPanelLockedNormal; // 0x30
	private GameObject _objPanelSelected; // 0x38
	private GameObject _objPanelLockSelected; // 0x40
	private UICommonTrackPoint _newTrackPoint; // 0x48
	private String m_cachedId; // 0x50
	private HomeBackgroundItemModel m_dataModel; // 0x58
	private Boolean m_isInited; // 0x60
	private TrackPointViewProperty m_backgroundNewTrackProp; // 0x68
	private Action`1 m_selectChanged; // 0x70
	private static DelegateBridge __Hotfix0_set_selectChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Flush; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 selectChanged { set; }

	// RVA: 0x2834728 VA: 0x7594e4c728
	public Void set_selectChanged(Action`1 value) { }
	// RVA: 0x28347ac VA: 0x7594e4c7ac
	private Void _InitIfNot() { }
	// RVA: 0x2834854 VA: 0x7594e4c854
	public Void Flush(HomeBackgroundItemModel backgroundModel) { }
	// RVA: 0x2834b4c VA: 0x7594e4cb4c
	public Void EventOnClick() { }
	// RVA: 0x2834c00 VA: 0x7594e4cc00
	public Void .ctor() { }
}
```