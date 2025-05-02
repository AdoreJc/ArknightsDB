# ActMultiV3StageListView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIAnimationLocation _modeAnim`

- `ActMultiV3StageListRowView _rowViewPrefab`

- `UIRecycleVerticalLayoutGroup _layout`

- `GameObject _pnlClose`

- `ViewMode m_cachedViewMode`

- `ActMultiV3StageListViewModel m_cachedViewModel`

- `Boolean m_inited`

- `Adapter m_adapter`

- `ActMultiV3MapDiffType m_cachedDiffType`

- `Int32 m_cachedInitSeqNum`

- `Tween m_diffAnimTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `UIAnimationLocation _GetDiffAnim(ActMultiV3MapDiffType)`

- `Void OnBackBtnClicked()`

- `Void OnInfoBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListView : DataBinder`1
{
	private UIAnimationLocation _modeAnim; // 0x20
	private ActMultiV3StageListRowView _rowViewPrefab; // 0x30
	private UIRecycleVerticalLayoutGroup _layout; // 0x38
	private ActMultiV3StageListTabView[] _tabViews; // 0x40
	private GameObject _pnlClose; // 0x48
	private AnimConfig[] _animConfigs; // 0x50
	private ViewMode m_cachedViewMode; // 0x58
	private ActMultiV3StageListViewModel m_cachedViewModel; // 0x60
	private Boolean m_inited; // 0x68
	private Adapter m_adapter; // 0x70
	private ActMultiV3MapDiffType m_cachedDiffType; // 0x78
	private Int32 m_cachedInitSeqNum; // 0x7c
	private Tween m_diffAnimTween; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__GetDiffAnim; // 0x10
	private static DelegateBridge __Hotfix0_OnBackBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnInfoBtnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x314f88c VA: 0x759576788c
	private Void _InitIfNot() { }
	// RVA: 0x314f9ec VA: 0x75957679ec
	public override Void OnValueChanged(ActMultiV3StageListProperty property) { }
	// RVA: 0x314fd80 VA: 0x7595767d80
	private UIAnimationLocation _GetDiffAnim(ActMultiV3MapDiffType diffType) { }
	// RVA: 0x314ff64 VA: 0x7595767f64
	public Void OnBackBtnClicked() { }
	// RVA: 0x3150018 VA: 0x7595768018
	public Void OnInfoBtnClicked() { }
	// RVA: 0x31500cc VA: 0x75957680cc
	public Void .ctor() { }
}
```