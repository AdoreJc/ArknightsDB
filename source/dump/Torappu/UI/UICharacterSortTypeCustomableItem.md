# UICharacterSortTypeCustomableItem

**Namespace:** `Torappu.UI`


## Fields

- `CharacterSortType _firstSortType`

- `CharacterSortType _secondSortType`

- `ThreeStateToggle m_toggle`

- `Boolean m_isInited`

- `Boolean m_customSortTypeSet`

- `Action <onOpenCustomSortPanel>k__BackingField`


## Properties

- `Action onOpenCustomSortPanel`


## Methods

- `Void _InitIfNot()`

- `Void set_onSortTypeChanged(Action`1)`

- `Action get_onOpenCustomSortPanel()`

- `Void set_onOpenCustomSortPanel(Action)`

- `Void _NotifySortTypeChanged(CharacterSortType)`

- `Void _OnToggleClick(State)`

- `Void SetCustomSortType(CharacterCardSortTypeViewModel)`

- `Void _RenderCustomSortType(CharacterCardSortTypeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortTypeCustomableItem : MonoBehaviour, IHotfixable
{
	private Text[] _sortTypeTexts; // 0x18
	private CharacterSortType _firstSortType; // 0x20
	private CharacterSortType _secondSortType; // 0x24
	private ThreeStateToggle m_toggle; // 0x28
	private Boolean m_isInited; // 0x30
	private Boolean m_customSortTypeSet; // 0x31
	private Action`1 <onSortTypeChanged>k__BackingField; // 0x38
	private Action <onOpenCustomSortPanel>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_onSortTypeChanged; // 0x8
	private static DelegateBridge __Hotfix0_set_onSortTypeChanged; // 0x10
	private static DelegateBridge __Hotfix0_get_onOpenCustomSortPanel; // 0x18
	private static DelegateBridge __Hotfix0_set_onOpenCustomSortPanel; // 0x20
	private static DelegateBridge __Hotfix0__NotifySortTypeChanged; // 0x28
	private static DelegateBridge __Hotfix0__OnToggleClick; // 0x30
	private static DelegateBridge __Hotfix0_SetCustomSortType; // 0x38
	private static DelegateBridge __Hotfix0__RenderCustomSortType; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onSortTypeChanged { get; set; }
	private Action onOpenCustomSortPanel { get; set; }

	// RVA: 0x21343d4 VA: 0x759474c3d4
	private Void _InitIfNot() { }
	// RVA: 0x21344e8 VA: 0x759474c4e8
	private Action`1 get_onSortTypeChanged() { }
	// RVA: 0x2134550 VA: 0x759474c550
	public Void set_onSortTypeChanged(Action`1 value) { }
	// RVA: 0x21345d4 VA: 0x759474c5d4
	private Action get_onOpenCustomSortPanel() { }
	// RVA: 0x213463c VA: 0x759474c63c
	public Void set_onOpenCustomSortPanel(Action value) { }
	// RVA: 0x21346c0 VA: 0x759474c6c0
	private Void _NotifySortTypeChanged(CharacterSortType sortType) { }
	// RVA: 0x2134794 VA: 0x759474c794
	public Void _OnToggleClick(State state) { }
	// RVA: 0x2134904 VA: 0x759474c904
	public Void SetCustomSortType(CharacterCardSortTypeViewModel viewModel) { }
	// RVA: 0x21349b0 VA: 0x759474c9b0
	private Void _RenderCustomSortType(CharacterCardSortTypeViewModel viewModel) { }
	// RVA: 0x2134b7c VA: 0x759474cb7c
	public Void .ctor() { }
}
```