# HomeThemeItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _imgThemePreview`

- `Text _textThemeName`

- `GameObject _objPanelLockedNormal`

- `GameObject _objPanelSelected`

- `GameObject _objPanelLockSelected`

- `UICommonTrackPoint _newTrackPoint`

- `String m_cachedId`

- `HomeThemeItemModel m_dataModel`

- `TrackPointViewProperty m_homeNewTrackProp`

- `Boolean m_isInited`


## Methods

- `Void set_selectChanged(Action`1)`

- `Void _InitIfNot()`

- `Void Flush(HomeThemeItemModel)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeThemeItemView : MonoBehaviour, IHotfixable
{
	private Image _imgThemePreview; // 0x18
	private Text _textThemeName; // 0x20
	private GameObject _objPanelLockedNormal; // 0x28
	private GameObject _objPanelSelected; // 0x30
	private GameObject _objPanelLockSelected; // 0x38
	private UICommonTrackPoint _newTrackPoint; // 0x40
	private String m_cachedId; // 0x48
	private HomeThemeItemModel m_dataModel; // 0x50
	private TrackPointViewProperty m_homeNewTrackProp; // 0x58
	private Boolean m_isInited; // 0x60
	private Action`1 m_selectChanged; // 0x68
	private static DelegateBridge __Hotfix0_set_selectChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Flush; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 selectChanged { set; }

	// RVA: 0x2840534 VA: 0x7594e58534
	public Void set_selectChanged(Action`1 value) { }
	// RVA: 0x28405b8 VA: 0x7594e585b8
	private Void _InitIfNot() { }
	// RVA: 0x2840660 VA: 0x7594e58660
	public Void Flush(HomeThemeItemModel themeModel) { }
	// RVA: 0x2840824 VA: 0x7594e58824
	public Void EventOnClick() { }
	// RVA: 0x28408d8 VA: 0x7594e588d8
	public Void .ctor() { }
}
```