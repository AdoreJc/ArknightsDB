# RL04FragmentListView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelNotEmpty`

- `UIAnimationLocation _animBtnSwitch`

- `RL04FragmentListAdapter _adapter`

- `CanvasGroup _canvasGroupList`

- `Single _fadeTime`

- `ILoadAsset <loader>k__BackingField`

- `Action <onSwitchBtnClicked>k__BackingField`

- `Boolean m_hasInited`

- `Tween m_switchTween`

- `RoguelikeFragmentDialogListType m_cachedListType`

- `UISwitchTween m_btnSwitchTween`


## Properties

- `ILoadAsset loader`

- `Action onSwitchBtnClicked`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void set_onItemClicked(Action`1)`

- `Action get_onSwitchBtnClicked()`

- `Void set_onSwitchBtnClicked(Action)`

- `Void EventOnListSwitchBtnClicked()`

- `Void _InitIfNot()`

- `Void _GenerateSwitchTween(RL04FragmentViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentListView : DataBinder`1, IHotfixable
{
	private const Single ALPHA_FADE_OUT; // 0x0
	private const Single ALPHA_FADE_IN; // 0x0
	private GameObject _panelEmpty; // 0x20
	private GameObject _panelNotEmpty; // 0x28
	private UIAnimationLocation _animBtnSwitch; // 0x30
	private RL04FragmentListAdapter _adapter; // 0x40
	private CanvasGroup _canvasGroupList; // 0x48
	private Single _fadeTime; // 0x50
	private ILoadAsset <loader>k__BackingField; // 0x58
	private Action`1 <onItemClicked>k__BackingField; // 0x60
	private Action <onSwitchBtnClicked>k__BackingField; // 0x68
	private Boolean m_hasInited; // 0x70
	private Tween m_switchTween; // 0x78
	private RoguelikeFragmentDialogListType m_cachedListType; // 0x80
	private UISwitchTween m_btnSwitchTween; // 0x88
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onSwitchBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onSwitchBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_EventOnListSwitchBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__GenerateSwitchTween; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private ILoadAsset loader { get; set; }
	private Action`1 onItemClicked { get; set; }
	private Action onSwitchBtnClicked { get; set; }

	// RVA: 0x2b26570 VA: 0x759513e570
	private ILoadAsset get_loader() { }
	// RVA: 0x2b248bc VA: 0x759513c8bc
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b265d8 VA: 0x759513e5d8
	private Action`1 get_onItemClicked() { }
	// RVA: 0x2b24940 VA: 0x759513c940
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x2b26640 VA: 0x759513e640
	private Action get_onSwitchBtnClicked() { }
	// RVA: 0x2b249c4 VA: 0x759513c9c4
	public Void set_onSwitchBtnClicked(Action value) { }
	// RVA: 0x2b266a8 VA: 0x759513e6a8
	public override Void OnValueChanged(RL04FragmentProperty property) { }
	// RVA: 0x2b26b1c VA: 0x759513eb1c
	public Void EventOnListSwitchBtnClicked() { }
	// RVA: 0x2b2680c VA: 0x759513e80c
	private Void _InitIfNot() { }
	// RVA: 0x2b2691c VA: 0x759513e91c
	private Void _GenerateSwitchTween(RL04FragmentViewModel model) { }
	// RVA: 0x2b26bc0 VA: 0x759513ebc0
	public Void .ctor() { }
}
```