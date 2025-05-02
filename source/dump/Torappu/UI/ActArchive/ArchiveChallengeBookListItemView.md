# ArchiveChallengeBookListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Button _button`

- `GameObject _lockedPanel`

- `GameObject _normalPanel`

- `GameObject _newPanel`

- `CanvasGroup _unselectedGroup`

- `CanvasGroup _selectedGroup`

- `Boolean m_hasInited`

- `ArchiveChallengeBookListItemSwitchTween m_switchTween`

- `ChallengeBookItemModel m_cachedItem`

- `ArchiveChallengeBookController <controller>k__BackingField`


## Properties

- `ArchiveChallengeBookController controller`


## Methods

- `ArchiveChallengeBookController get_controller()`

- `Void set_controller(ArchiveChallengeBookController)`

- `Void ItemClickEvent()`

- `Void Render(ChallengeBookItemModel, Boolean, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChallengeBookListItemView : MonoBehaviour, IHotfixable
{
	private Text[] _nameTexts; // 0x18
	private Button _button; // 0x20
	private GameObject _lockedPanel; // 0x28
	private GameObject _normalPanel; // 0x30
	private GameObject _newPanel; // 0x38
	private CanvasGroup _unselectedGroup; // 0x40
	private CanvasGroup _selectedGroup; // 0x48
	private Boolean m_hasInited; // 0x50
	private ArchiveChallengeBookListItemSwitchTween m_switchTween; // 0x58
	private ChallengeBookItemModel m_cachedItem; // 0x60
	private ArchiveChallengeBookController <controller>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_ItemClickEvent; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ArchiveChallengeBookController controller { get; set; }

	// RVA: 0x303e144 VA: 0x7595656144
	private ArchiveChallengeBookController get_controller() { }
	// RVA: 0x303df1c VA: 0x7595655f1c
	public Void set_controller(ArchiveChallengeBookController value) { }
	// RVA: 0x303e1ac VA: 0x75956561ac
	public Void ItemClickEvent() { }
	// RVA: 0x303dfa0 VA: 0x7595655fa0
	public Void Render(ChallengeBookItemModel itemModel, Boolean selected, Boolean showSwitchTween) { }
	// RVA: 0x303e2b4 VA: 0x75956562b4
	private Void _InitIfNot() { }
	// RVA: 0x303e404 VA: 0x7595656404
	public Void .ctor() { }
}
```