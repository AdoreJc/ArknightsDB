# RoguelikeMenu

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeMenuViewModel m_viewModel`

- `RoguelikeMenuAdapter m_topAdapter`

- `StateTransitionParam m_currTransParam`

- `StateEngine m_bindStateEngine`

- `String <topicId>k__BackingField`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Void RegisterMenuAdapter(Type, RoguelikeMenuAdapter, Type)`

- `RoguelikeMenuAdapter _GetStateMenuAdapter(Type)`

- `Void _OnDataUpdated(Object)`

- `Void _OnBeforeStateTransition(Object)`

- `Void _OnStateChanged(Object, Boolean)`

- `Void _RefreshMenu(Boolean)`

- `Void Init(RoguelikeDungeonController)`

- `Void SetMenuBarSelectStatus(RoguelikeMenuBar, Boolean, Boolean)`

- `Void ClearSelect(Boolean)`

- `Void <Init>b__19_0(Object)`

- `Void <Init>b__19_1(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenu : MonoBehaviour, IHotfixable
{
	private List`1 _menuBars; // 0x18
	private List`1 _raycastTriggers; // 0x20
	private RoguelikeMenuViewModel m_viewModel; // 0x28
	private RoguelikeMenuAdapter m_topAdapter; // 0x30
	private StateTransitionParam m_currTransParam; // 0x38
	private Dictionary`2 m_adapters; // 0x40
	private StateEngine m_bindStateEngine; // 0x48
	private HashSet`1 m_selectStatus; // 0x50
	private String <topicId>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_RegisterMenuAdapter; // 0x10
	private static DelegateBridge __Hotfix0__GetStateMenuAdapter; // 0x18
	private static DelegateBridge __Hotfix0__OnDataUpdated; // 0x20
	private static DelegateBridge __Hotfix0__OnBeforeStateTransition; // 0x28
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x30
	private static DelegateBridge __Hotfix0__RefreshMenu; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x40
	private static DelegateBridge __Hotfix0_SetMenuBarSelectStatus; // 0x48
	private static DelegateBridge __Hotfix0_ClearSelect; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String topicId { get; set; }

	// RVA: 0x2a77c44 VA: 0x759508fc44
	public String get_topicId() { }
	// RVA: 0x2a77cac VA: 0x759508fcac
	private Void set_topicId(String value) { }
	// RVA: 0x2a77d30 VA: 0x759508fd30
	public Void RegisterMenuAdapter(Type stateType, RoguelikeMenuAdapter adapter, Type adapterType) { }
	// RVA: 0x2a77efc VA: 0x759508fefc
	private RoguelikeMenuAdapter _GetStateMenuAdapter(Type stateType) { }
	// RVA: 0x2a78138 VA: 0x7595090138
	private Void _OnDataUpdated(Object arg) { }
	// RVA: 0x2a78760 VA: 0x7595090760
	private Void _OnBeforeStateTransition(Object arg) { }
	// RVA: 0x2a788bc VA: 0x75950908bc
	private Void _OnStateChanged(Object arg, Boolean statePaused) { }
	// RVA: 0x2a78a80 VA: 0x7595090a80
	private Void _RefreshMenu(Boolean fastMode) { }
	// RVA: 0x2a78eb8 VA: 0x7595090eb8
	public Void Init(RoguelikeDungeonController controller) { }
	// RVA: 0x2a79324 VA: 0x7595091324
	public Void SetMenuBarSelectStatus(RoguelikeMenuBar menuBar, Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2a6acc0 VA: 0x7595082cc0
	public Void ClearSelect(Boolean fastMode) { }
	// RVA: 0x2a7977c VA: 0x759509177c
	public Void .ctor() { }
	// RVA: 0x2a79910 VA: 0x7595091910
	private Void <Init>b__19_0(Object arg) { }
	// RVA: 0x2a79918 VA: 0x7595091918
	private Void <Init>b__19_1(Object arg) { }
}
```