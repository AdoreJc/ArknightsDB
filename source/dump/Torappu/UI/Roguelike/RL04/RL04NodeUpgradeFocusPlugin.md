# RL04NodeUpgradeFocusPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _panelUpgrade`

- `GameObject _panelPermUpgrade`

- `GameObject _panelPermUpgraded`

- `GameObject _panelCanPermUpgrade`

- `GameObject _panelCannotPermUpgrade`

- `GameObject _panelCanTempUpgrade`

- `GameObject _panelCannotTempUpgrade`

- `GameObject _panelTempUpgraded`

- `GameObject _panelNormalTitle`

- `GameObject _panelUpgradeTitle`

- `Text _upgradeTitle`

- `UIAnimationLocation _animPermEffect`

- `UIAnimationLocation _animTempEffect`

- `UIAnimationLocation _animRefreshEffect`

- `Int32 m_dialogInst`

- `RoguelikeDungeonNode m_focusNode`

- `RoguelikeEventType m_nodeType`

- `Tween m_effectTween`

- `Tween m_refreshEffectTween`

- `NodeUpgradeStatus m_cachedStatus`

- `Boolean m_hasInited`


## Methods

- `Boolean _RenderDefault()`

- `Void _InitIfNot()`

- `Void EventOnBtnDetail()`

- `Void HandleCallBack(Int32, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04NodeUpgradeFocusPlugin : RoguelikeFocusPlugin, ICompDialogCallBack
{
	private GameObject _panelUpgrade; // 0x28
	private GameObject _panelPermUpgrade; // 0x30
	private GameObject _panelPermUpgraded; // 0x38
	private GameObject _panelCanPermUpgrade; // 0x40
	private GameObject _panelCannotPermUpgrade; // 0x48
	private GameObject _panelCanTempUpgrade; // 0x50
	private GameObject _panelCannotTempUpgrade; // 0x58
	private GameObject _panelTempUpgraded; // 0x60
	private GameObject _panelNormalTitle; // 0x68
	private GameObject _panelUpgradeTitle; // 0x70
	private Text _upgradeTitle; // 0x78
	private UIAnimationLocation _animPermEffect; // 0x80
	private UIAnimationLocation _animTempEffect; // 0x90
	private UIAnimationLocation _animRefreshEffect; // 0xa0
	private Int32 m_dialogInst; // 0xb0
	private RoguelikeDungeonNode m_focusNode; // 0xb8
	private RoguelikeEventType m_nodeType; // 0xc0
	private Tween m_effectTween; // 0xc8
	private Tween m_refreshEffectTween; // 0xd0
	private NodeUpgradeStatus m_cachedStatus; // 0xd8
	private Boolean m_hasInited; // 0xdc
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderDefault; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnDetail; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b313b8 VA: 0x75951493b8
	public override Boolean Render(RoguelikeFocusViewModel viewModel) { }
	// RVA: 0x2b3182c VA: 0x759514982c
	private Boolean _RenderDefault() { }
	// RVA: 0x2b316e8 VA: 0x75951496e8
	private Void _InitIfNot() { }
	// RVA: 0x2b318f0 VA: 0x75951498f0
	public Void EventOnBtnDetail() { }
	// RVA: 0x2b31b64 VA: 0x7595149b64
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2b31db4 VA: 0x7595149db4
	public Void .ctor() { }
}
```