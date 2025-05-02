# ArchiveTimelineItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `TimelineLineView _lineView`

- `TimelineMusicItemView _musicItemView`

- `TimelinePicItemView _picItemView`

- `TimelineAvgItemView _avgItemView`

- `TimelineStoryItemView _storyItemView`

- `TimelineNewsItemView _newsItemView`

- `Text _timelineDesc`

- `Image _timelineTitle`

- `Boolean m_hasInited`

- `TimelineItemModel m_cachedModel`

- `ArchiveTimelineController m_controller`


## Properties

- `ArchiveTimelineController controller`


## Methods

- `ArchiveTimelineController get_controller()`

- `Void set_controller(ArchiveTimelineController)`

- `Void ApplyData(TimelineItemModel)`

- `Void EventOnMusicClicked()`

- `Void EventOnPicClicked()`

- `Void EventOnAvgClicked()`

- `Void EventOnStoryClicked()`

- `Void EventOnNewsClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTimelineItemView : MonoBehaviour, IHotfixable
{
	private TimelineLineView _lineView; // 0x18
	private TimelineMusicItemView _musicItemView; // 0x20
	private TimelinePicItemView _picItemView; // 0x28
	private TimelineAvgItemView _avgItemView; // 0x30
	private TimelineStoryItemView _storyItemView; // 0x38
	private TimelineNewsItemView _newsItemView; // 0x40
	private Text _timelineDesc; // 0x48
	private Image _timelineTitle; // 0x50
	private Boolean m_hasInited; // 0x58
	private TimelineItemModel m_cachedModel; // 0x60
	private ArchiveTimelineController m_controller; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_EventOnMusicClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnPicClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnAvgClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnNewsClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public ArchiveTimelineController controller { get; set; }

	// RVA: 0x3085c20 VA: 0x759569dc20
	public ArchiveTimelineController get_controller() { }
	// RVA: 0x30852a4 VA: 0x759569d2a4
	public Void set_controller(ArchiveTimelineController value) { }
	// RVA: 0x30853f8 VA: 0x759569d3f8
	public Void ApplyData(TimelineItemModel timelineItemModel) { }
	// RVA: 0x3085e0c VA: 0x759569de0c
	public Void EventOnMusicClicked() { }
	// RVA: 0x3085fa4 VA: 0x759569dfa4
	public Void EventOnPicClicked() { }
	// RVA: 0x308613c VA: 0x759569e13c
	public Void EventOnAvgClicked() { }
	// RVA: 0x30862d4 VA: 0x759569e2d4
	public Void EventOnStoryClicked() { }
	// RVA: 0x308646c VA: 0x759569e46c
	public Void EventOnNewsClicked() { }
	// RVA: 0x3086604 VA: 0x759569e604
	public Void .ctor() { }
}
```