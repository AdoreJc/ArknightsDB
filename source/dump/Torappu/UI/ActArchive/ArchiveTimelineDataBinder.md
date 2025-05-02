# ArchiveTimelineDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SimpleLayoutContent _viewContainer`

- `Image _imgBkg`

- `AutoFocusScrollView _scrollView`

- `ArchiveTimelineAdapter m_listAdapter`

- `ArchiveTimelineModel m_cachedModel`

- `Boolean m_hasInited`

- `ArchiveTimelineController m_controller`


## Properties

- `ArchiveTimelineController controller`


## Methods

- `Void _InitIfNot()`

- `ArchiveTimelineController get_controller()`

- `Void set_controller(ArchiveTimelineController)`

- `IEnumerator FocusOnLastUncheckedItem(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTimelineDataBinder : DataBinder`1
{
	private SimpleLayoutContent _viewContainer; // 0x20
	private Image _imgBkg; // 0x28
	private AutoFocusScrollView _scrollView; // 0x30
	private ArchiveTimelineAdapter m_listAdapter; // 0x38
	private ArchiveTimelineModel m_cachedModel; // 0x40
	private Boolean m_hasInited; // 0x48
	private ArchiveTimelineController m_controller; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_controller; // 0x8
	private static DelegateBridge __Hotfix0_set_controller; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_FocusOnLastUncheckedItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ArchiveTimelineController controller { get; set; }

	// RVA: 0x3084c84 VA: 0x759569cc84
	private Void _InitIfNot() { }
	// RVA: 0x3084e3c VA: 0x759569ce3c
	public ArchiveTimelineController get_controller() { }
	// RVA: 0x30844e4 VA: 0x759569c4e4
	public Void set_controller(ArchiveTimelineController value) { }
	// RVA: 0x3084ea4 VA: 0x759569cea4
	public override Void OnValueChanged(TimelineProperty property) { }
	// RVA: 0x3084b54 VA: 0x759569cb54
	public IEnumerator FocusOnLastUncheckedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x3084fc8 VA: 0x759569cfc8
	public Void .ctor() { }
}
```