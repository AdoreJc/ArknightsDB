# BossRushRelicView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `SimpleLayoutContent _contentRelicList`

- `GameObject _tokenPart`

- `GameObject _completedPart`

- `CanvasGroup _emptyInfoCanvas`

- `Text _txtTokenName`

- `Text _txtTokenCount`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `BossRushRelicViewModel m_viewModel`

- `FadeSwitchTween m_doTween`


## Methods

- `Void set_onSelectRelicAction(Action`1)`

- `Void set_onUpgradeClickedAction(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicView : DataBinder`1
{
	private SimpleLayoutContent _contentRelicList; // 0x20
	private GameObject _tokenPart; // 0x28
	private GameObject _completedPart; // 0x30
	private CanvasGroup _emptyInfoCanvas; // 0x38
	private Text _txtTokenName; // 0x40
	private Text _txtTokenCount; // 0x48
	private Action`1 <onSelectRelicAction>k__BackingField; // 0x50
	private Action`1 <onUpgradeClickedAction>k__BackingField; // 0x58
	private Boolean m_hasInited; // 0x60
	private Adapter m_adapter; // 0x68
	private BossRushRelicViewModel m_viewModel; // 0x70
	private FadeSwitchTween m_doTween; // 0x78
	private const Single ALPHA_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_get_onSelectRelicAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectRelicAction; // 0x8
	private static DelegateBridge __Hotfix0_get_onUpgradeClickedAction; // 0x10
	private static DelegateBridge __Hotfix0_set_onUpgradeClickedAction; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onSelectRelicAction { get; set; }
	private Action`1 onUpgradeClickedAction { get; set; }

	// RVA: 0x2e5ff84 VA: 0x7595477f84
	private Action`1 get_onSelectRelicAction() { }
	// RVA: 0x2e5ffec VA: 0x7595477fec
	public Void set_onSelectRelicAction(Action`1 value) { }
	// RVA: 0x2e60070 VA: 0x7595478070
	private Action`1 get_onUpgradeClickedAction() { }
	// RVA: 0x2e600d8 VA: 0x75954780d8
	public Void set_onUpgradeClickedAction(Action`1 value) { }
	// RVA: 0x2e6015c VA: 0x759547815c
	public override Void OnValueChanged(BossRushRelicViewProperty property) { }
	// RVA: 0x2e6030c VA: 0x759547830c
	private Void _InitIfNot() { }
	// RVA: 0x2e60674 VA: 0x7595478674
	public Void .ctor() { }
}
```