# FriendAssistItemFloatPanel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _panelFloat`

- `GameObject _floatBg`

- `CanvasGroup _panelFloatCanvasGroup`

- `Transform _skillContainer`

- `Transform _equipContainer`

- `SimpleLayoutContent _skillContent`

- `SimpleLayoutContent _equipContent`

- `GameObject m_cachedItemObject`

- `ItemType m_cachedShowType`

- `Int32 m_cachedIndex`

- `FriendAssistFloatSwitchTween m_switchTween`

- `Boolean m_isInited`

- `SkillAdapter m_skillAdapter`

- `EquipAdapter m_equipAdapter`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void Render(AssistItemOptions)`

- `Void _InitIfNot()`

- `Void _Render(AssistItemOptions)`

- `Void _ResetPanelPosition()`

- `Void _OnItemClick(String, ItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistItemFloatPanel : MonoBehaviour, IHotfixable
{
	private static Vector2 FLOAT_PANEL_OFFSET; // 0x0
	private GameObject _panelFloat; // 0x18
	private GameObject _floatBg; // 0x20
	private CanvasGroup _panelFloatCanvasGroup; // 0x28
	private Transform _skillContainer; // 0x30
	private Transform _equipContainer; // 0x38
	private SimpleLayoutContent _skillContent; // 0x40
	private SimpleLayoutContent _equipContent; // 0x48
	private GameObject m_cachedItemObject; // 0x50
	private ItemType m_cachedShowType; // 0x58
	private Int32 m_cachedIndex; // 0x5c
	private FriendAssistFloatSwitchTween m_switchTween; // 0x60
	private Boolean m_isInited; // 0x68
	private SkillAdapter m_skillAdapter; // 0x70
	private EquipAdapter m_equipAdapter; // 0x78
	public Action`3 onItemClicked; // 0x80
	private static DelegateBridge __Hotfix0_get_isShow; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0__ResetPanelPosition; // 0x28
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isShow { get; }

	// RVA: 0x28c8504 VA: 0x7594ee0504
	public Boolean get_isShow() { }
	// RVA: 0x28c8590 VA: 0x7594ee0590
	public Void Render(AssistItemOptions options) { }
	// RVA: 0x28c8668 VA: 0x7594ee0668
	private Void _InitIfNot() { }
	// RVA: 0x28c8824 VA: 0x7594ee0824
	private Void _Render(AssistItemOptions options) { }
	// RVA: 0x28c8b48 VA: 0x7594ee0b48
	private Void _ResetPanelPosition() { }
	// RVA: 0x28c8d94 VA: 0x7594ee0d94
	private Void _OnItemClick(String id, ItemType itemType) { }
	// RVA: 0x28c8e54 VA: 0x7594ee0e54
	public Void .ctor() { }
	// RVA: 0x28c8ed4 VA: 0x7594ee0ed4
	private static Void .cctor() { }
}
```