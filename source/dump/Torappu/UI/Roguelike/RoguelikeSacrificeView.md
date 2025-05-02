# RoguelikeSacrificeView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `LoopVerticalScrollRect _scrollRect`

- `RoguelikeSacrificeViewScrollAdapter _scrollAdapter`

- `RoguelikeSacrificeSelectedView _selectedView`

- `RoguelikeSacrificePlugin _plugin`

- `String m_cachedSelectedItem`

- `PlayerRoguelikeSacrificeType m_cachedSacrificeType`

- `Action <onConfirmClick>k__BackingField`


## Properties

- `Action onConfirmClick`

- `RoguelikeSacrificePlugin plugin`


## Methods

- `Void set_onItemClick(Action`1)`

- `Action get_onConfirmClick()`

- `Void set_onConfirmClick(Action)`

- `RoguelikeSacrificePlugin get_plugin()`

- `Void _UpdateSacrificeTypePanels(PlayerRoguelikeSacrificeType)`

- `Void ResetListToTop()`

- `Void OnConfirmBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSacrificeView : DataBinder`1
{
	private LoopVerticalScrollRect _scrollRect; // 0x20
	private RoguelikeSacrificeViewScrollAdapter _scrollAdapter; // 0x28
	private RoguelikeSacrificeSelectedView _selectedView; // 0x30
	private RoguelikeSacrificePlugin _plugin; // 0x38
	private List`1 _sacrificeTypePanels; // 0x40
	private String m_cachedSelectedItem; // 0x48
	private PlayerRoguelikeSacrificeType m_cachedSacrificeType; // 0x50
	private Action`1 <onItemClick>k__BackingField; // 0x58
	private Action <onConfirmClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onConfirmClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onConfirmClick; // 0x18
	private static DelegateBridge __Hotfix0_get_plugin; // 0x20
	private static DelegateBridge __Hotfix0__UpdateSacrificeTypePanels; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_ResetListToTop; // 0x38
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Action`1 onItemClick { get; set; }
	public Action onConfirmClick { get; set; }
	public RoguelikeSacrificePlugin plugin { get; }

	// RVA: 0x2ac1888 VA: 0x75950d9888
	public Action`1 get_onItemClick() { }
	// RVA: 0x2ac03c8 VA: 0x75950d83c8
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2ac18f0 VA: 0x75950d98f0
	public Action get_onConfirmClick() { }
	// RVA: 0x2ac044c VA: 0x75950d844c
	public Void set_onConfirmClick(Action value) { }
	// RVA: 0x2ac04d0 VA: 0x75950d84d0
	public RoguelikeSacrificePlugin get_plugin() { }
	// RVA: 0x2ac1958 VA: 0x75950d9958
	private Void _UpdateSacrificeTypePanels(PlayerRoguelikeSacrificeType sacrificeType) { }
	// RVA: 0x2ac1a50 VA: 0x75950d9a50
	public override Void OnValueChanged(RoguelikeSacrificeProperty property) { }
	// RVA: 0x2ac05a8 VA: 0x75950d85a8
	public Void ResetListToTop() { }
	// RVA: 0x2ac21e8 VA: 0x75950da1e8
	public Void OnConfirmBtnClick() { }
	// RVA: 0x2ac2284 VA: 0x75950da284
	public Void .ctor() { }
}
```