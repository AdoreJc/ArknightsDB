# PanelActivityViewController

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _breakingNewsImage`

- `ScrollViewPager _viewPager`

- `UIWrappedScrollRect _scrollRect`

- `HomeActivityView _activityProto`

- `RectTransform _activityContainer`

- `ToggleGroup _toggleGroup`

- `Toggle _toggleProto`

- `Sprite _defaultBreakingNews`

- `Boolean m_isInited`

- `Single m_switchCountDown`

- `Boolean m_autoToggleSwitch`


## Methods

- `Void OnToggleChanged(Boolean)`

- `Void Render()`

- `Void _TryTweenToPage(Int32)`

- `Void _PageSwitchCallback(Int32)`

- `Void Awake()`

- `Void OnDestroy()`

- `Void Update()`

- `ActivityViewEntry _AchieveBackupDefaultEntry()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class PanelActivityViewController : MonoBehaviour
{
	private const Single PAUSE_DURATION_WHEN_ACTION; // 0x0
	private const Single SWITCH_PAGE_PERIOD; // 0x0
	private Image _breakingNewsImage; // 0x18
	private ScrollViewPager _viewPager; // 0x20
	private UIWrappedScrollRect _scrollRect; // 0x28
	private HomeActivityView _activityProto; // 0x30
	private RectTransform _activityContainer; // 0x38
	private ToggleGroup _toggleGroup; // 0x40
	private Toggle _toggleProto; // 0x48
	private Sprite _defaultBreakingNews; // 0x50
	private ActivityViewEntryProvider[] _activityViewEntryProviders; // 0x58
	private Boolean m_isInited; // 0x60
	private List`1 m_viewCache; // 0x68
	private List`1 m_switchToggles; // 0x70
	private List`1 m_sharedEntryList; // 0x78
	private Single m_switchCountDown; // 0x80
	private Boolean m_autoToggleSwitch; // 0x84


	// RVA: 0x28477f8 VA: 0x7594e5f7f8
	public Void OnToggleChanged(Boolean isSelected) { }
	// RVA: 0x2847918 VA: 0x7594e5f918
	public Void Render() { }
	// RVA: 0x28478b8 VA: 0x7594e5f8b8
	private Void _TryTweenToPage(Int32 pageIndex) { }
	// RVA: 0x2848310 VA: 0x7594e60310
	private Void _PageSwitchCallback(Int32 index) { }
	// RVA: 0x28483b8 VA: 0x7594e603b8
	private Void Awake() { }
	// RVA: 0x284848c VA: 0x7594e6048c
	private Void OnDestroy() { }
	// RVA: 0x2848560 VA: 0x7594e60560
	private Void Update() { }
	// RVA: 0x2848640 VA: 0x7594e60640
	public static SpriteHub LoadBannerImageHub(String path) { }
	// RVA: 0x28482a0 VA: 0x7594e602a0
	private ActivityViewEntry _AchieveBackupDefaultEntry() { }
	// RVA: 0x2848734 VA: 0x7594e60734
	private static Int32 _EvalActivityEntryType(ActivityEntryType type) { }
	// RVA: 0x2848758 VA: 0x7594e60758
	public Void .ctor() { }
}
```