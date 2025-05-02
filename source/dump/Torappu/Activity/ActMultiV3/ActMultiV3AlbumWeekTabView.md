# ActMultiV3AlbumWeekTabView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIAnimationLocation _selectAnimLocation`

- `TwoStateToggle _lockToggle`

- `GameObject _selectHotspotGo`

- `TwoStateToggle _markToggle`

- `Text _titleNumberText`

- `Text _lockedTitleDescText`

- `Text _titleDescText`

- `Transform _trackPointContainer`

- `GameObject _trackPointObj`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `UISwitchTween m_selectTween`

- `Int32 m_cachedTabIndex`

- `GameObject m_trackPoint`


## Methods

- `Void Render(ActMultiV3WeekAlbumViewModel, Int32, Boolean)`

- `Void OnClickTab()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3AlbumWeekTabView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _selectAnimLocation; // 0x18
	private TwoStateToggle _lockToggle; // 0x28
	private GameObject _selectHotspotGo; // 0x30
	private TwoStateToggle _markToggle; // 0x38
	private Text _titleNumberText; // 0x40
	private Text _lockedTitleDescText; // 0x48
	private Text _titleDescText; // 0x50
	private Transform _trackPointContainer; // 0x58
	private GameObject _trackPointObj; // 0x60
	private Boolean m_inited; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private UISwitchTween m_selectTween; // 0x80
	private Int32 m_cachedTabIndex; // 0x88
	private GameObject m_trackPoint; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickTab; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31197b0 VA: 0x75957317b0
	public Void Render(ActMultiV3WeekAlbumViewModel model, Int32 selectedTabIdx, Boolean isFirstUpdate) { }
	// RVA: 0x311a160 VA: 0x7595732160
	public Void OnClickTab() { }
	// RVA: 0x3119fe8 VA: 0x7595731fe8
	private Void _InitIfNot() { }
	// RVA: 0x311a250 VA: 0x7595732250
	public Void .ctor() { }
}
```