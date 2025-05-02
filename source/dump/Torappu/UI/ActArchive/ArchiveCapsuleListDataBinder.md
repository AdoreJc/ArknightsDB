# ArchiveCapsuleListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveCapsuleRecycleAdapter _adapter`

- `Text _textTitle`

- `Text _textUnlockTitle`

- `Image _imgItem`

- `Text _textUsage`

- `Text _textDesc`

- `Text _textEnglishName`

- `Boolean m_hasInited`

- `ArchiveCapsuleController <controller>k__BackingField`


## Properties

- `ArchiveCapsuleController controller`


## Methods

- `ArchiveCapsuleController get_controller()`

- `Void set_controller(ArchiveCapsuleController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveCapsuleListDataBinder : DataBinder`1
{
	private const String UNLOCK_CAPSULE_DETAIL_TITLE; // 0x0
	private const String UNLOCK_CAPSULE_ENGLISH_TITLE; // 0x0
	public const String UNKNOWN_CAPSULE_ICON_ID; // 0x0
	private ArchiveCapsuleRecycleAdapter _adapter; // 0x20
	private Text _textTitle; // 0x28
	private Text _textUnlockTitle; // 0x30
	private Image _imgItem; // 0x38
	private Text _textUsage; // 0x40
	private Text _textDesc; // 0x48
	private Text _textEnglishName; // 0x50
	private Boolean m_hasInited; // 0x58
	private ArchiveCapsuleController <controller>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveCapsuleController controller { get; set; }

	// RVA: 0x303ac14 VA: 0x7595652c14
	private ArchiveCapsuleController get_controller() { }
	// RVA: 0x303aa5c VA: 0x7595652a5c
	public Void set_controller(ArchiveCapsuleController value) { }
	// RVA: 0x303ac7c VA: 0x7595652c7c
	private Void _InitIfNot() { }
	// RVA: 0x303ad9c VA: 0x7595652d9c
	public override Void OnValueChanged(CapsuleProperty property) { }
	// RVA: 0x303b4d4 VA: 0x75956534d4
	public Void .ctor() { }
}
```