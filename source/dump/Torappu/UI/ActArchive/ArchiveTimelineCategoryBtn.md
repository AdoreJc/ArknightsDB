# ArchiveTimelineCategoryBtn

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _btnNormal`

- `GameObject _btnLocked`

- `ActArchiveType _archiveType`

- `Image _imgNormal`

- `Image _imgLocked`

- `Boolean m_cachedLocked`

- `ArchiveTimelineController m_controller`


## Properties

- `ArchiveTimelineController controller`


## Methods

- `ArchiveTimelineController get_controller()`

- `Void set_controller(ArchiveTimelineController)`

- `Void ApplyData(Boolean)`

- `Void EventOnBtnNormalClicked()`

- `Void EventOnBtnLockedClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTimelineCategoryBtn : MonoBehaviour, IHotfixable
{
	private GameObject _btnNormal; // 0x18
	private GameObject _btnLocked; // 0x20
	private ActArchiveType _archiveType; // 0x28
	private Image _imgNormal; // 0x30
	private Image _imgLocked; // 0x38
	private Boolean m_cachedLocked; // 0x40
	private ArchiveTimelineController m_controller; // 0x48
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnNormalClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBtnLockedClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ArchiveTimelineController controller { get; set; }

	// RVA: 0x3083a98 VA: 0x759569ba98
	public ArchiveTimelineController get_controller() { }
	// RVA: 0x3083b00 VA: 0x759569bb00
	public Void set_controller(ArchiveTimelineController value) { }
	// RVA: 0x3084038 VA: 0x759569c038
	public Void ApplyData(Boolean locked) { }
	// RVA: 0x30840f8 VA: 0x759569c0f8
	public Void EventOnBtnNormalClicked() { }
	// RVA: 0x30841f4 VA: 0x759569c1f4
	public Void EventOnBtnLockedClicked() { }
	// RVA: 0x3084258 VA: 0x759569c258
	public Void .ctor() { }
}
```