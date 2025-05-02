# Act25sideResearchAreaItemView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Text _areaName`

- `Text _areaProgress`

- `GameObject _panelNew`

- `GameObject _panelComplete`

- `GameObject _panelProgress`

- `GameObject _panelSelect`

- `GameObject _panelUnselect`

- `GameObject _panelLocked`

- `UIAnimationLocation _selectAnim`

- `UICommonTrackPoint _commonTrackPoint`

- `Boolean m_isInited`

- `Act25sideAreaViewModel m_cachedViewModel`

- `AnimationSwitchTween m_switchTween`

- `UIStateFinder m_stateFinder`

- `TrackPointViewProperty m_trackPointProperty`


## Methods

- `Void Render(Act25sideAreaViewModel, String)`

- `Void _InitIfNot()`

- `Void OnItemSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchAreaItemView : MonoBehaviour, IHotfixable
{
	private Text _areaName; // 0x18
	private Text _areaProgress; // 0x20
	private GameObject _panelNew; // 0x28
	private GameObject _panelComplete; // 0x30
	private GameObject _panelProgress; // 0x38
	private GameObject _panelSelect; // 0x40
	private GameObject _panelUnselect; // 0x48
	private GameObject _panelLocked; // 0x50
	private UIAnimationLocation _selectAnim; // 0x58
	private UICommonTrackPoint _commonTrackPoint; // 0x68
	private Boolean m_isInited; // 0x70
	private Act25sideAreaViewModel m_cachedViewModel; // 0x78
	private AnimationSwitchTween m_switchTween; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private TrackPointViewProperty m_trackPointProperty; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnItemSelect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3282398 VA: 0x759589a398
	public Void Render(Act25sideAreaViewModel viewModel, String selectedArea) { }
	// RVA: 0x3282658 VA: 0x759589a658
	private Void _InitIfNot() { }
	// RVA: 0x3282ad8 VA: 0x759589aad8
	public Void OnItemSelect() { }
	// RVA: 0x3282db0 VA: 0x759589adb0
	public Void .ctor() { }
}
```