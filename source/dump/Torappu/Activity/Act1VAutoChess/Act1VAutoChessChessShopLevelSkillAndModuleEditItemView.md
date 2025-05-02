# Act1VAutoChessChessShopLevelSkillAndModuleEditItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `SimpleLayoutContent _contentSkill`

- `GameObject _objSkillPanel`

- `SimpleLayoutContent _contentModule`

- `GameObject _objModulePanel`

- `UIWrappedScrollRect _scrollRectModule`

- `UILayoutDimensionListener _dimensionListenerModule`

- `String m_cachedSelectedEquipId`

- `String m_cachedSelectedSkillId`

- `String m_cachedChessId`

- `Int32 m_cachedChessLv`

- `UIPageFinder m_pageFinder`

- `ModuleListAdapter m_moduleAdapter`

- `SkillListAdapter m_skillAdapter`

- `Boolean m_hasInited`

- `Int32 m_cachedSelectedModuleIndex`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(Act1VAutoChessMultiCharSkillEquipEditItemViewModel)`

- `Void SetDragHandler(IDragHandler)`

- `Void _InitIfNot()`

- `Void _OnSelectSkill(String, Int32, String)`

- `Void _OnSelectModule(String, Int32, String)`

- `Void _EventOnPostLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelSkillAndModuleEditItemView : MonoBehaviour, IHotfixable
{
	private const Int32 SLOT_COUNT; // 0x0
	private const Int32 UPPER_MODULE_INDEX; // 0x0
	private SimpleLayoutContent _contentSkill; // 0x18
	private GameObject _objSkillPanel; // 0x20
	private SimpleLayoutContent _contentModule; // 0x28
	private GameObject _objModulePanel; // 0x30
	private UIWrappedScrollRect _scrollRectModule; // 0x38
	private UILayoutDimensionListener _dimensionListenerModule; // 0x40
	private List`1 m_cachedEquips; // 0x48
	private List`1 m_cachedSkills; // 0x50
	private String m_cachedSelectedEquipId; // 0x58
	private String m_cachedSelectedSkillId; // 0x60
	private String m_cachedChessId; // 0x68
	private Int32 m_cachedChessLv; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private ModuleListAdapter m_moduleAdapter; // 0x88
	private SkillListAdapter m_skillAdapter; // 0x90
	private Boolean m_hasInited; // 0x98
	private Int32 m_cachedSelectedModuleIndex; // 0x9c
	private UIStateFinder m_stateFinder; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetDragHandler; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnSelectSkill; // 0x18
	private static DelegateBridge __Hotfix0__OnSelectModule; // 0x20
	private static DelegateBridge __Hotfix0__EventOnPostLayout; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x331d164 VA: 0x7595935164
	public Void Render(Act1VAutoChessMultiCharSkillEquipEditItemViewModel model) { }
	// RVA: 0x331d070 VA: 0x7595935070
	public Void SetDragHandler(IDragHandler handler) { }
	// RVA: 0x33228a8 VA: 0x759593a8a8
	private Void _InitIfNot() { }
	// RVA: 0x3322b9c VA: 0x759593ab9c
	private Void _OnSelectSkill(String chessId, Int32 chessLv, String skillId) { }
	// RVA: 0x3322d28 VA: 0x759593ad28
	private Void _OnSelectModule(String chessId, Int32 chessLv, String moduleId) { }
	// RVA: 0x3322eb4 VA: 0x759593aeb4
	private Void _EventOnPostLayout() { }
	// RVA: 0x3322f3c VA: 0x759593af3c
	public Void .ctor() { }
}
```