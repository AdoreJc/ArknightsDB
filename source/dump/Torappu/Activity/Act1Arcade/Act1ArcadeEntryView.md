# Act1ArcadeEntryView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Text _allZoneScoreTxt`

- `GameObject _badgeBookEntryTrackpointObj`

- `Act1ArcadeToast _notifyToastPrefab`

- `Act1ArcadeEntryViewModel m_viewModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _NotifyToast(String)`

- `Void EventOnBadgeEntryClick()`

- `Void EventOnMileStoneClick()`

- `Void EventOnMedalClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeEntryView : DataBinder`1
{
	private const Int32 SCORE_NUM_DIGIT_CNT; // 0x0
	private Act1ArcadeEntryGameEntryItemView[] _itemViews; // 0x20
	private Text _allZoneScoreTxt; // 0x28
	private GameObject[] _badgeBookEntryOpenIconObjs; // 0x30
	private GameObject[] _badgeBookEntryCloseIconObjs; // 0x38
	private GameObject _badgeBookEntryTrackpointObj; // 0x40
	private Act1ArcadeToast _notifyToastPrefab; // 0x48
	private Act1ArcadeEntryViewModel m_viewModel; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private static DelegateBridge __Hotfix0__NotifyToast; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBadgeEntryClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnMileStoneClick; // 0x18
	private static DelegateBridge __Hotfix0_EventOnMedalClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x340017c VA: 0x7595a1817c
	private Void _NotifyToast(String toastStr) { }
	// RVA: 0x3400274 VA: 0x7595a18274
	public override Void OnValueChanged(Act1ArcadeEntryProperty property) { }
	// RVA: 0x3400714 VA: 0x7595a18714
	public Void EventOnBadgeEntryClick() { }
	// RVA: 0x34007b8 VA: 0x7595a187b8
	public Void EventOnMileStoneClick() { }
	// RVA: 0x340085c VA: 0x7595a1885c
	public Void EventOnMedalClick() { }
	// RVA: 0x3400900 VA: 0x7595a18900
	public Void .ctor() { }
}
```