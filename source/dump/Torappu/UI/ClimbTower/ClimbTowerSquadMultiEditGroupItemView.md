# ClimbTowerSquadMultiEditGroupItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgProfession`

- `SimpleLayoutContent _charList`

- `GridLayoutGroup _gridLayout`

- `Boolean m_hasInited`

- `SpriteHub m_professionHub`

- `EditType m_editType`

- `Adapter m_adapter`

- `Int32 m_viewIndex`

- `Int64 m_cachedGameStartTs`

- `Boolean m_needRebuild`


## Properties

- `GridLayoutGroup gridLayout`


## Methods

- `Void set_onSkillSelect(Action`2)`

- `Void set_onEquipSelect(Action`2)`

- `GridLayoutGroup get_gridLayout()`

- `Void InitView(ProfessionCategory, List`1, SpriteHub, Int64)`

- `Void SetViewIndex(Int32)`

- `Int32 GetViewIndex()`

- `Void Refresh(EditType, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditGroupItemView : MonoBehaviour, IHotfixable
{
	private Image _imgProfession; // 0x18
	private SimpleLayoutContent _charList; // 0x20
	private GridLayoutGroup _gridLayout; // 0x28
	private Boolean m_hasInited; // 0x30
	private List`1 m_characterList; // 0x38
	private SpriteHub m_professionHub; // 0x40
	private EditType m_editType; // 0x48
	private Adapter m_adapter; // 0x50
	private Int32 m_viewIndex; // 0x58
	private Int64 m_cachedGameStartTs; // 0x60
	private Boolean m_needRebuild; // 0x68
	private Action`2 <onSkillSelect>k__BackingField; // 0x70
	private Action`2 <onEquipSelect>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onEquipSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_onEquipSelect; // 0x18
	private static DelegateBridge __Hotfix0_get_gridLayout; // 0x20
	private static DelegateBridge __Hotfix0_InitView; // 0x28
	private static DelegateBridge __Hotfix0_SetViewIndex; // 0x30
	private static DelegateBridge __Hotfix0_GetViewIndex; // 0x38
	private static DelegateBridge __Hotfix0_Refresh; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`2 onSkillSelect { get; set; }
	private Action`2 onEquipSelect { get; set; }
	public GridLayoutGroup gridLayout { get; }

	// RVA: 0x2cc3d7c VA: 0x75952dbd7c
	private Action`2 get_onSkillSelect() { }
	// RVA: 0x2cc2330 VA: 0x75952da330
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x2cc3de4 VA: 0x75952dbde4
	private Action`2 get_onEquipSelect() { }
	// RVA: 0x2cc23b4 VA: 0x75952da3b4
	public Void set_onEquipSelect(Action`2 value) { }
	// RVA: 0x2cc21c8 VA: 0x75952da1c8
	public GridLayoutGroup get_gridLayout() { }
	// RVA: 0x2cc24b4 VA: 0x75952da4b4
	public Void InitView(ProfessionCategory profession, List`1 charList, SpriteHub professionSpriteHub, Int64 gameStartTs) { }
	// RVA: 0x2cc2438 VA: 0x75952da438
	public Void SetViewIndex(Int32 viewIndex) { }
	// RVA: 0x2cc3f1c VA: 0x75952dbf1c
	public Int32 GetViewIndex() { }
	// RVA: 0x2cc25bc VA: 0x75952da5bc
	public Void Refresh(EditType editType, Boolean needRebuild) { }
	// RVA: 0x2cc3e4c VA: 0x75952dbe4c
	private Void _InitIfNot() { }
	// RVA: 0x2cc4018 VA: 0x75952dc018
	public Void .ctor() { }
}
```