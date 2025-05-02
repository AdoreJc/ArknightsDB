# ArchiveCapsuleListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _imgIcon`

- `GameObject _panelSelected`

- `CanvasGroup _canvasSelected`

- `GameObject _panelNew`

- `CapsuleItemModel m_cachedModel`

- `Boolean m_hasInited`

- `ArchiveCapsuleListItemSwitchTween m_switchTween`

- `ArchiveCapsuleController <controller>k__BackingField`


## Properties

- `ArchiveCapsuleController controller`


## Methods

- `ArchiveCapsuleController get_controller()`

- `Void set_controller(ArchiveCapsuleController)`

- `Void _InitIfNot()`

- `Void OnCapsuleItemClicked()`

- `Void Render(CapsuleItemModel, Sprite, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveCapsuleListItemView : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private GameObject _panelSelected; // 0x20
	private CanvasGroup _canvasSelected; // 0x28
	private GameObject _panelNew; // 0x30
	private CapsuleItemModel m_cachedModel; // 0x38
	private Boolean m_hasInited; // 0x40
	private ArchiveCapsuleListItemSwitchTween m_switchTween; // 0x48
	private ArchiveCapsuleController <controller>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnCapsuleItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ArchiveCapsuleController controller { get; set; }

	// RVA: 0x303b564 VA: 0x7595653564
	private ArchiveCapsuleController get_controller() { }
	// RVA: 0x303b5cc VA: 0x75956535cc
	public Void set_controller(ArchiveCapsuleController value) { }
	// RVA: 0x303b650 VA: 0x7595653650
	private Void _InitIfNot() { }
	// RVA: 0x303b7b4 VA: 0x75956537b4
	public Void OnCapsuleItemClicked() { }
	// RVA: 0x303b898 VA: 0x7595653898
	public Void Render(CapsuleItemModel itemModel, Sprite itemIcon, String selectItemId) { }
	// RVA: 0x303b9b8 VA: 0x75956539b8
	public Void .ctor() { }
}
```