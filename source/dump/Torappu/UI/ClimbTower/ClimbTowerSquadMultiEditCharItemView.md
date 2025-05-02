# ClimbTowerSquadMultiEditCharItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `RectTransform _charCardParent`

- `SimpleLayoutContent _skillList`

- `SimpleLayoutContent _equipList`

- `Single _charCardScale`

- `GameObject _trackNewGo`

- `RectTransform _equipContentRectTransform`

- `UIWrappedScrollRect _equipScrollRect`

- `Single _equipScrollMaxHeight`

- `Single _equipScrollLimitHeight`

- `UICharacterCardPanel m_charCard`

- `Boolean m_hasInited`

- `SkillListAdapter m_skillAdapter`

- `EquipListAdapter m_equipAdapter`

- `ClimbTowerSquadMultiEditCharModel m_charEditModel`

- `EditType m_editType`

- `UIStateFinder m_stateFinder`


## Methods

- `Void set_onSkillSelect(Action`2)`

- `Void set_onEquipSelect(Action`2)`

- `Void UpdateViewData(ClimbTowerSquadMultiEditCharModel, EditType, Boolean)`

- `Void _InitIfNot()`

- `Void _SetScrollViewDragDelegate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditCharItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _charCardParent; // 0x18
	private SimpleLayoutContent _skillList; // 0x20
	private SimpleLayoutContent _equipList; // 0x28
	private Single _charCardScale; // 0x30
	private GameObject _trackNewGo; // 0x38
	private RectTransform _equipContentRectTransform; // 0x40
	private UIWrappedScrollRect _equipScrollRect; // 0x48
	private Single _equipScrollMaxHeight; // 0x50
	private Single _equipScrollLimitHeight; // 0x54
	private UICharacterCardPanel m_charCard; // 0x58
	private Boolean m_hasInited; // 0x60
	private SkillListAdapter m_skillAdapter; // 0x68
	private EquipListAdapter m_equipAdapter; // 0x70
	private ClimbTowerSquadMultiEditCharModel m_charEditModel; // 0x78
	private EditType m_editType; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private Action`2 <onSkillSelect>k__BackingField; // 0x98
	private Action`2 <onEquipSelect>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onEquipSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_onEquipSelect; // 0x18
	private static DelegateBridge __Hotfix0_UpdateViewData; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SetScrollViewDragDelegate; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`2 onSkillSelect { get; set; }
	private Action`2 onEquipSelect { get; set; }

	// RVA: 0x2cc26c0 VA: 0x75952da6c0
	private Action`2 get_onSkillSelect() { }
	// RVA: 0x2cc2728 VA: 0x75952da728
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x2cc27ac VA: 0x75952da7ac
	private Action`2 get_onEquipSelect() { }
	// RVA: 0x2cc2814 VA: 0x75952da814
	public Void set_onEquipSelect(Action`2 value) { }
	// RVA: 0x2cc2898 VA: 0x75952da898
	public Void UpdateViewData(ClimbTowerSquadMultiEditCharModel charEditModel, EditType editType, Boolean needRebuild) { }
	// RVA: 0x2cc2ad0 VA: 0x75952daad0
	private Void _InitIfNot() { }
	// RVA: 0x2cc2eb0 VA: 0x75952daeb0
	private Void _SetScrollViewDragDelegate() { }
	// RVA: 0x2cc2fa0 VA: 0x75952dafa0
	public Void .ctor() { }
}
```