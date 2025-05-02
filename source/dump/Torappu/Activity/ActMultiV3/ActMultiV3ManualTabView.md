# ActMultiV3ManualTabView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _hotspotObj`

- `UIAnimationLocation _selectAnimLocation`

- `ActMultiV3TabContentAbstractView _view`

- `ManualTabType _tabType`

- `Transform _trackPointContainer`

- `GameObject _trackPointObj`

- `Boolean m_inited`

- `Int32 m_cachedInitSeqNum`

- `UIStateFinder m_stateFinder`

- `UISwitchTween m_selectTween`

- `GameObject m_trackPoint`


## Methods

- `Void Render(ActMultiV3ManualViewModel)`

- `Void OnClickTab()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualTabView : MonoBehaviour, IHotfixable
{
	private GameObject _hotspotObj; // 0x18
	private UIAnimationLocation _selectAnimLocation; // 0x20
	private ActMultiV3TabContentAbstractView _view; // 0x30
	private ManualTabType _tabType; // 0x38
	private Transform _trackPointContainer; // 0x40
	private GameObject _trackPointObj; // 0x48
	private Boolean m_inited; // 0x50
	private Int32 m_cachedInitSeqNum; // 0x54
	private UIStateFinder m_stateFinder; // 0x58
	private UISwitchTween m_selectTween; // 0x68
	private GameObject m_trackPoint; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickTab; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30fc17c VA: 0x759571417c
	public Void Render(ActMultiV3ManualViewModel model) { }
	// RVA: 0x30fc470 VA: 0x7595714470
	public Void OnClickTab() { }
	// RVA: 0x30fc2f8 VA: 0x75957142f8
	private Void _InitIfNot() { }
	// RVA: 0x30fc560 VA: 0x7595714560
	public Void .ctor() { }
}
```