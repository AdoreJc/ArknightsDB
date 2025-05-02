# Act1ArcadeBadgeBookDetailView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UIAnimationLocation _switchAnimation`

- `SimpleLayoutContent _progressContent`

- `UIStateFinder m_finder`

- `Boolean m_hasInited`

- `Act1ArcadeBadgeBookDetailContentAnimator m_animator`

- `Adapter m_adapter`

- `String m_actId`

- `Act1ArcadeBadgeBookItemViewModel m_cachedPresentingItem`

- `Direction m_direction`

- `Action <closeEvent>k__BackingField`

- `Action <switchForwardEvent>k__BackingField`

- `Action <switchBackwardEvent>k__BackingField`


## Properties

- `Action closeEvent`

- `Action switchForwardEvent`

- `Action switchBackwardEvent`


## Methods

- `Action get_closeEvent()`

- `Void set_closeEvent(Action)`

- `Action get_switchForwardEvent()`

- `Void set_switchForwardEvent(Action)`

- `Action get_switchBackwardEvent()`

- `Void set_switchBackwardEvent(Action)`

- `Void OnCloseEvent()`

- `Void OnSwitchForwardEvent()`

- `Void OnSwitchBackwardEvent()`

- `Void _InitIfNot()`

- `Void _RenderItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookDetailView : DataBinder`1
{
	private List`1 _badgeTypePanels; // 0x20
	private UIAnimationLocation _switchAnimation; // 0x28
	private SimpleLayoutContent _progressContent; // 0x38
	private UIStateFinder m_finder; // 0x40
	private Boolean m_hasInited; // 0x50
	private Act1ArcadeBadgeBookDetailContentAnimator m_animator; // 0x58
	private Adapter m_adapter; // 0x60
	private String m_actId; // 0x68
	private Act1ArcadeBadgeBookItemViewModel m_cachedPresentingItem; // 0x70
	private Direction m_direction; // 0x78
	private Action <closeEvent>k__BackingField; // 0x80
	private Action <switchForwardEvent>k__BackingField; // 0x88
	private Action <switchBackwardEvent>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_closeEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_closeEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_switchForwardEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_switchForwardEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_switchBackwardEvent; // 0x20
	private static DelegateBridge __Hotfix0_set_switchBackwardEvent; // 0x28
	private static DelegateBridge __Hotfix0_OnCloseEvent; // 0x30
	private static DelegateBridge __Hotfix0_OnSwitchForwardEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnSwitchBackwardEvent; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__RenderItem; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action closeEvent { get; set; }
	private Action switchForwardEvent { get; set; }
	private Action switchBackwardEvent { get; set; }

	// RVA: 0x33f24ac VA: 0x7595a0a4ac
	private Action get_closeEvent() { }
	// RVA: 0x33f1f10 VA: 0x7595a09f10
	public Void set_closeEvent(Action value) { }
	// RVA: 0x33f2514 VA: 0x7595a0a514
	private Action get_switchForwardEvent() { }
	// RVA: 0x33f1f94 VA: 0x7595a09f94
	public Void set_switchForwardEvent(Action value) { }
	// RVA: 0x33f257c VA: 0x7595a0a57c
	private Action get_switchBackwardEvent() { }
	// RVA: 0x33f2018 VA: 0x7595a0a018
	public Void set_switchBackwardEvent(Action value) { }
	// RVA: 0x33f25e4 VA: 0x7595a0a5e4
	public Void OnCloseEvent() { }
	// RVA: 0x33f2680 VA: 0x7595a0a680
	public Void OnSwitchForwardEvent() { }
	// RVA: 0x33f271c VA: 0x7595a0a71c
	public Void OnSwitchBackwardEvent() { }
	// RVA: 0x33f27b8 VA: 0x7595a0a7b8
	public override Void OnValueChanged(Act1ArcadeBadgeBookDetailProperty property) { }
	// RVA: 0x33f2928 VA: 0x7595a0a928
	private Void _InitIfNot() { }
	// RVA: 0x33f2c94 VA: 0x7595a0ac94
	private Void _RenderItem() { }
	// RVA: 0x33f2e1c VA: 0x7595a0ae1c
	public Void .ctor() { }
}
```