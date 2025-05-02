# ArchiveLandmarkDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _imgItem`

- `Text _textTitle`

- `Text _textEngTitle`

- `Text _textItemDesc`

- `Sprite _imgListItemIcon`

- `ScrollRect _textScrollRect`

- `SimpleLayoutContent _viewContainer`

- `ArchiveLandmarkModel m_cachedModel`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `ActArchiveController <controller>k__BackingField`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveLandmarkDataBinder : DataBinder`1
{
	private Image _imgItem; // 0x20
	private Text _textTitle; // 0x28
	private Text _textEngTitle; // 0x30
	private Text _textItemDesc; // 0x38
	private Sprite _imgListItemIcon; // 0x40
	private ScrollRect _textScrollRect; // 0x48
	private SimpleLayoutContent _viewContainer; // 0x50
	private ArchiveLandmarkModel m_cachedModel; // 0x58
	private Adapter m_adapter; // 0x60
	private Boolean m_isInited; // 0x68
	private ActArchiveController <controller>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ActArchiveController controller { get; set; }

	// RVA: 0x305758c VA: 0x759566f58c
	private ActArchiveController get_controller() { }
	// RVA: 0x3057490 VA: 0x759566f490
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x30575f4 VA: 0x759566f5f4
	public override Void OnValueChanged(LandmarkProperty property) { }
	// RVA: 0x3057814 VA: 0x759566f814
	private Void _InitIfNot() { }
	// RVA: 0x30579fc VA: 0x759566f9fc
	public Void .ctor() { }
}
```