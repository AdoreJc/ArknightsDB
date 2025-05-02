# ClimbTowerEntryFloatGodCardView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _content`

- `UIAnimationLocation _tabOpenAnimLocation`

- `UIAnimationLocation _tabCloseAnimLocation`

- `Boolean m_hasInited`

- `String m_seasonId`

- `Adapter m_adapter`

- `FloatGodCardSwitchTween m_tabSwitchTween`

- `UIPage <page>k__BackingField`

- `Action <onClicked>k__BackingField`


## Properties

- `UIPage page`

- `Action onClicked`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Action get_onClicked()`

- `Void set_onClicked(Action)`

- `Void set_onItemClicked(Action`1)`

- `Void Render(ClimbTowerEntryFloatPanelViewModel)`

- `Void OnClick()`

- `Void _InitIfNot(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryFloatGodCardView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private UIAnimationLocation _tabOpenAnimLocation; // 0x20
	private UIAnimationLocation _tabCloseAnimLocation; // 0x30
	private Boolean m_hasInited; // 0x40
	private String m_seasonId; // 0x48
	private Adapter m_adapter; // 0x50
	private List`1 m_godCardViewModel; // 0x58
	private FloatGodCardSwitchTween m_tabSwitchTween; // 0x60
	private UIPage <page>k__BackingField; // 0x68
	private Action <onClicked>k__BackingField; // 0x70
	private Action`1 <onItemClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private UIPage page { get; set; }
	private Action onClicked { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x2c62ea8 VA: 0x759527aea8
	private UIPage get_page() { }
	// RVA: 0x2c62f10 VA: 0x759527af10
	public Void set_page(UIPage value) { }
	// RVA: 0x2c62f94 VA: 0x759527af94
	private Action get_onClicked() { }
	// RVA: 0x2c62ffc VA: 0x759527affc
	public Void set_onClicked(Action value) { }
	// RVA: 0x2c63080 VA: 0x759527b080
	private Action`1 get_onItemClicked() { }
	// RVA: 0x2c630e8 VA: 0x759527b0e8
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x2c6316c VA: 0x759527b16c
	public Void Render(ClimbTowerEntryFloatPanelViewModel viewModel) { }
	// RVA: 0x2c63388 VA: 0x759527b388
	public Void OnClick() { }
	// RVA: 0x2c63248 VA: 0x759527b248
	private Void _InitIfNot(Boolean isGodCardTabClose) { }
	// RVA: 0x2c6354c VA: 0x759527b54c
	public Void .ctor() { }
}
```