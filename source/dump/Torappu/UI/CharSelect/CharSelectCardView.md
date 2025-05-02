# CharSelectCardView

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `Transform _characterContainer`

- `GameObject _panelSelected`

- `Text _selectOrder`

- `Single _charCardScaler`

- `RectTransform _maskPluginContainer`

- `RectTransform _sortInfoContainer`

- `UICharacterSortInfoPanel _sortInfoPrefab`

- `String pageName`

- `UICharacterCardPanel m_cardPanel`

- `Boolean m_isInited`

- `CharacterCardViewModel m_cardModel`

- `Int32 m_pluginPrefabId`

- `CharSelectCardMaskPlugin m_pluginInst`

- `UICharacterSortInfoPanel m_sortInfoInst`


## Methods

- `Void RenderCard(Int32, CharacterCardViewModel, Boolean, CharacterSortType)`

- `Void RenderPlugin(CharSelectCardMaskPlugin, CharSelectStateBean, Object)`

- `Void set_onClick(Action`1)`

- `Void _InitIfNot()`

- `Void _InitPluginIfNot(CharSelectCardMaskPlugin, CharSelectStateBean, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectCardView : MonoBehaviour, IHotfixable
{
	private Transform _characterContainer; // 0x18
	private GameObject _panelSelected; // 0x20
	private Text _selectOrder; // 0x28
	private Single _charCardScaler; // 0x30
	private RectTransform _maskPluginContainer; // 0x38
	private RectTransform _sortInfoContainer; // 0x40
	private UICharacterSortInfoPanel _sortInfoPrefab; // 0x48
	public String pageName; // 0x50
	private UICharacterCardPanel m_cardPanel; // 0x58
	private Boolean m_isInited; // 0x60
	private CharacterCardViewModel m_cardModel; // 0x68
	private Int32 m_pluginPrefabId; // 0x70
	private CharSelectCardMaskPlugin m_pluginInst; // 0x78
	private UICharacterSortInfoPanel m_sortInfoInst; // 0x80
	private static DelegateBridge __Hotfix0_RenderCard; // 0x0
	private static DelegateBridge __Hotfix0_RenderPlugin; // 0x8
	private static DelegateBridge __Hotfix0_set_onClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__InitPluginIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Action`1 onClick { set; }

	// RVA: 0x2cf5ab8 VA: 0x759530dab8
	public Void RenderCard(Int32 selectedIndex, CharacterCardViewModel cardModel, Boolean showSelectOrder, CharacterSortType sortType) { }
	// RVA: 0x2cf5d6c VA: 0x759530dd6c
	public Void RenderPlugin(CharSelectCardMaskPlugin maskPluginPrefab, CharSelectStateBean stateBean, Object context) { }
	// RVA: 0x2cf5a24 VA: 0x759530da24
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2cf620c VA: 0x759530e20c
	private Void _InitIfNot() { }
	// RVA: 0x2cf63f0 VA: 0x759530e3f0
	private Void _InitPluginIfNot(CharSelectCardMaskPlugin prefab, CharSelectStateBean stateBean, Object context) { }
	// RVA: 0x2cf65f0 VA: 0x759530e5f0
	public Void .ctor() { }
}
```