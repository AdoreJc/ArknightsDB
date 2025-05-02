# ClimbTowerSquadCreateView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _squadList`

- `GridLayoutGroup _squadGridLayout`

- `Text _textCaption`

- `Text _textCurrentCount`

- `Text _textTotalCount`

- `ScrollRect _squadScrollRect`

- `Single _scrollDuration`

- `Boolean m_hasInited`

- `Int32 m_displaySlotCount`

- `SquadListAdapter m_adapter`


## Methods

- `Void set_onSlotClick(Action`1)`

- `Void set_onClearAssistClick(Action`1)`

- `Void set_onGetAssistClick(Action`1)`

- `Void FocusToEnd()`

- `Void _InitIfNot()`

- `Void _CalcDisplayCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadCreateView : DataBinder`1
{
	private SimpleLayoutContent _squadList; // 0x20
	private GridLayoutGroup _squadGridLayout; // 0x28
	private Text _textCaption; // 0x30
	private Text _textCurrentCount; // 0x38
	private Text _textTotalCount; // 0x40
	private ScrollRect _squadScrollRect; // 0x48
	private Single _scrollDuration; // 0x50
	private Boolean m_hasInited; // 0x54
	private Int32 m_displaySlotCount; // 0x58
	private SquadListAdapter m_adapter; // 0x60
	private Action`1 <onSlotClick>k__BackingField; // 0x68
	private Action`1 <onClearAssistClick>k__BackingField; // 0x70
	private Action`1 <onGetAssistClick>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onSlotClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onClearAssistClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onClearAssistClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onGetAssistClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onGetAssistClick; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_FocusToEnd; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__CalcDisplayCount; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 onSlotClick { get; set; }
	private Action`1 onClearAssistClick { get; set; }
	private Action`1 onGetAssistClick { get; set; }

	// RVA: 0x2cb7310 VA: 0x75952cf310
	private Action`1 get_onSlotClick() { }
	// RVA: 0x2cb7378 VA: 0x75952cf378
	public Void set_onSlotClick(Action`1 value) { }
	// RVA: 0x2cb73fc VA: 0x75952cf3fc
	private Action`1 get_onClearAssistClick() { }
	// RVA: 0x2cb7464 VA: 0x75952cf464
	public Void set_onClearAssistClick(Action`1 value) { }
	// RVA: 0x2cb74e8 VA: 0x75952cf4e8
	private Action`1 get_onGetAssistClick() { }
	// RVA: 0x2cb7550 VA: 0x75952cf550
	public Void set_onGetAssistClick(Action`1 value) { }
	// RVA: 0x2cb75d4 VA: 0x75952cf5d4
	public override Void OnValueChanged(SquadGroupViewProperty property) { }
	// RVA: 0x2cb7b54 VA: 0x75952cfb54
	public Void FocusToEnd() { }
	// RVA: 0x2cb7860 VA: 0x75952cf860
	private Void _InitIfNot() { }
	// RVA: 0x2cb7bc8 VA: 0x75952cfbc8
	private Void _CalcDisplayCount() { }
	// RVA: 0x2cb7d58 VA: 0x75952cfd58
	public Void .ctor() { }
}
```