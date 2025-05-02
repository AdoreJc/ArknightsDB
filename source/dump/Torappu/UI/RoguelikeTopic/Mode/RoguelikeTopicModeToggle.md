# RoguelikeTopicModeToggle

**Namespace:** `Torappu.UI.RoguelikeTopic.Mode`


## Fields

- `SerializeTabID _tabType`

- `Button _button`

- `GameObject _selectedObj`

- `GameObject _unselectedObj`

- `GameObject _disableObj`

- `Boolean m_isUnlocked`

- `Boolean m_interactable`

- `Boolean m_isOpened`

- `SerializeTabID m_curType`

- `Boolean m_isInited`

- `String m_topicId`


## Properties

- `Boolean interactable`

- `Boolean isUnlock`

- `Boolean isOpened`

- `SerializeTabID tabType`


## Methods

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Boolean get_isUnlock()`

- `Void set_isUnlock(Boolean)`

- `Boolean get_isOpened()`

- `Void set_isOpened(Boolean)`

- `SerializeTabID get_tabType()`

- `Void _InitIfNot()`

- `Void UpdateStatus(String, SerializeTabID)`

- `Void _RefreshTabStatus()`

- `Void _OnTabClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Mode
public class RoguelikeTopicModeToggle : MonoBehaviour, IHotfixable
{
	private SerializeTabID _tabType; // 0x18
	private Button _button; // 0x20
	private GameObject _selectedObj; // 0x28
	private GameObject _unselectedObj; // 0x30
	private GameObject _disableObj; // 0x38
	private Boolean m_isUnlocked; // 0x40
	private Boolean m_interactable; // 0x41
	private Boolean m_isOpened; // 0x42
	private SerializeTabID m_curType; // 0x44
	private Boolean m_isInited; // 0x48
	private String m_topicId; // 0x50
	public Action`1 onTabClicked; // 0x58
	private static DelegateBridge __Hotfix0_get_interactable; // 0x0
	private static DelegateBridge __Hotfix0_set_interactable; // 0x8
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x10
	private static DelegateBridge __Hotfix0_set_isUnlock; // 0x18
	private static DelegateBridge __Hotfix0_get_isOpened; // 0x20
	private static DelegateBridge __Hotfix0_set_isOpened; // 0x28
	private static DelegateBridge __Hotfix0_get_tabType; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x40
	private static DelegateBridge __Hotfix0__RefreshTabStatus; // 0x48
	private static DelegateBridge __Hotfix0__OnTabClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean interactable { get; set; }
	public Boolean isUnlock { get; set; }
	public Boolean isOpened { get; set; }
	public SerializeTabID tabType { get; }

	// RVA: 0x26d7ab8 VA: 0x7594cefab8
	public Boolean get_interactable() { }
	// RVA: 0x26d66cc VA: 0x7594cee6cc
	public Void set_interactable(Boolean value) { }
	// RVA: 0x26d7cc4 VA: 0x7594cefcc4
	public Boolean get_isUnlock() { }
	// RVA: 0x26d6750 VA: 0x7594cee750
	public Void set_isUnlock(Boolean value) { }
	// RVA: 0x26d7d2c VA: 0x7594cefd2c
	public Boolean get_isOpened() { }
	// RVA: 0x26d67d4 VA: 0x7594cee7d4
	public Void set_isOpened(Boolean value) { }
	// RVA: 0x26d65ec VA: 0x7594cee5ec
	public SerializeTabID get_tabType() { }
	// RVA: 0x26d7d94 VA: 0x7594cefd94
	private Void _InitIfNot() { }
	// RVA: 0x26d6528 VA: 0x7594cee528
	public Void UpdateStatus(String topicId, SerializeTabID selectedType) { }
	// RVA: 0x26d7b20 VA: 0x7594cefb20
	private Void _RefreshTabStatus() { }
	// RVA: 0x26d7eb4 VA: 0x7594cefeb4
	private Void _OnTabClicked() { }
	// RVA: 0x26d808c VA: 0x7594cf008c
	public Void .ctor() { }
}
```