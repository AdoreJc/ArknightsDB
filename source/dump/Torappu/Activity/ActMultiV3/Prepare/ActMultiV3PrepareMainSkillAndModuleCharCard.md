# ActMultiV3PrepareMainSkillAndModuleCharCard

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3CharCardBase _cardPrefab`

- `Transform _container`

- `SimpleLayoutContent _contentSkill`

- `GameObject _objSkillPanel`

- `SimpleLayoutContent _contentModule`

- `GameObject _objModulePanel`

- `UIWrappedScrollRect _scrollRectModule`

- `UILayoutDimensionListener _dimensionListenerModule`

- `ActMultiV3CharCardBase m_card`

- `String m_cachedSelectedEquipId`

- `String m_cachedSelectedSkillId`

- `Int32 m_cachedInstId`

- `UIPageFinder m_pageFinder`

- `ModuleListAdapter m_moduleAdapter`

- `SkillListAdapter m_skillAdapter`

- `Boolean m_hasInited`

- `Int32 m_cachedSeqNum`

- `Int32 m_cachedSelectedModuleIndex`


## Methods

- `Void set_onSelectSkillEvent(Action`2)`

- `Void set_onSelectModuleEvent(Action`2)`

- `Void Render(ActMultiV3PrepareMainSkillAndModuleCharCardModel, Boolean, Int32)`

- `Void SetDragHandler(IDragHandler)`

- `Void _InitIfNot()`

- `Void _RenderSkillAndModule(ActMultiV3PrepareMainSkillAndModuleCharCardModel, Boolean, Boolean)`

- `Void _OnSelectSkill(Int32, String)`

- `Void _OnSelectModule(Int32, String)`

- `Void _EventOnPostLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSkillAndModuleCharCard : MonoBehaviour, IHotfixable
{
	private const Int32 EMPTY_INST_ID; // 0x0
	private const Int32 SLOT_COUNT; // 0x0
	private const Int32 UPPER_MODULE_INDEX; // 0x0
	private ActMultiV3CharCardBase _cardPrefab; // 0x18
	private Transform _container; // 0x20
	private SimpleLayoutContent _contentSkill; // 0x28
	private GameObject _objSkillPanel; // 0x30
	private SimpleLayoutContent _contentModule; // 0x38
	private GameObject _objModulePanel; // 0x40
	private UIWrappedScrollRect _scrollRectModule; // 0x48
	private UILayoutDimensionListener _dimensionListenerModule; // 0x50
	private ActMultiV3CharCardBase m_card; // 0x58
	private List`1 m_cachedEquips; // 0x60
	private List`1 m_cachedSkills; // 0x68
	private String m_cachedSelectedEquipId; // 0x70
	private String m_cachedSelectedSkillId; // 0x78
	private Int32 m_cachedInstId; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private ModuleListAdapter m_moduleAdapter; // 0x98
	private SkillListAdapter m_skillAdapter; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private Int32 m_cachedSeqNum; // 0xac
	private Int32 m_cachedSelectedModuleIndex; // 0xb0
	private Action`2 <onSelectSkillEvent>k__BackingField; // 0xb8
	private Action`2 <onSelectModuleEvent>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_get_onSelectSkillEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectSkillEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_onSelectModuleEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_onSelectModuleEvent; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_SetDragHandler; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderSkillAndModule; // 0x38
	private static DelegateBridge __Hotfix0__OnSelectSkill; // 0x40
	private static DelegateBridge __Hotfix0__OnSelectModule; // 0x48
	private static DelegateBridge __Hotfix0__EventOnPostLayout; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Action`2 onSelectSkillEvent { get; set; }
	private Action`2 onSelectModuleEvent { get; set; }

	// RVA: 0x315ff88 VA: 0x7595777f88
	private Action`2 get_onSelectSkillEvent() { }
	// RVA: 0x315fff0 VA: 0x7595777ff0
	public Void set_onSelectSkillEvent(Action`2 value) { }
	// RVA: 0x3160074 VA: 0x7595778074
	private Action`2 get_onSelectModuleEvent() { }
	// RVA: 0x31600dc VA: 0x75957780dc
	public Void set_onSelectModuleEvent(Action`2 value) { }
	// RVA: 0x3160160 VA: 0x7595778160
	public Void Render(ActMultiV3PrepareMainSkillAndModuleCharCardModel model, Boolean showSkill, Int32 seqNum) { }
	// RVA: 0x3160740 VA: 0x7595778740
	public Void SetDragHandler(IDragHandler handler) { }
	// RVA: 0x3160278 VA: 0x7595778278
	private Void _InitIfNot() { }
	// RVA: 0x3160588 VA: 0x7595778588
	private Void _RenderSkillAndModule(ActMultiV3PrepareMainSkillAndModuleCharCardModel model, Boolean showSkill, Boolean needRebuildModule) { }
	// RVA: 0x3160a2c VA: 0x7595778a2c
	private Void _OnSelectSkill(Int32 instId, String skillId) { }
	// RVA: 0x3160af4 VA: 0x7595778af4
	private Void _OnSelectModule(Int32 instId, String moduleId) { }
	// RVA: 0x3160bbc VA: 0x7595778bbc
	private Void _EventOnPostLayout() { }
	// RVA: 0x3160c44 VA: 0x7595778c44
	public Void .ctor() { }
}
```