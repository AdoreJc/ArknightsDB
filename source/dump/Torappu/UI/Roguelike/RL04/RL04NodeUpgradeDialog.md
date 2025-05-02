# RL04NodeUpgradeDialog

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `UIRenderTextureImage _blurBg`

- `RectTransform _backRt`

- `RL04NodeUpgradeView _view`

- `RL04NodeUpgradeProp m_prop`

- `RL04NodeUpgradeConfig m_config`

- `String m_topicId`

- `RoguelikeEventType m_nodeType`

- `Boolean m_hasInited`

- `Boolean m_isClosing`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnBtnBack()`

- `Void EventOnBtnBackClick()`

- `Void EventOnBtnConfirm()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04NodeUpgradeDialog : UICompDialog`1
{
	private UIRenderTextureImage _blurBg; // 0x48
	private RectTransform _backRt; // 0x50
	private RL04NodeUpgradeView _view; // 0x58
	private RL04NodeUpgradeProp m_prop; // 0x60
	private RL04NodeUpgradeConfig m_config; // 0x68
	private String m_topicId; // 0x70
	private RoguelikeEventType m_nodeType; // 0x78
	private Boolean m_hasInited; // 0x7c
	private Boolean m_isClosing; // 0x7d
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBtnBackClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnConfirm; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2b2ff34 VA: 0x7595147f34
	protected override Void OnInit() { }
	// RVA: 0x2b2ffa8 VA: 0x7595147fa8
	protected override Void OnRender(Input input) { }
	// RVA: 0x2b30214 VA: 0x7595148214
	private Void _InitIfNot() { }
	// RVA: 0x2b309e8 VA: 0x75951489e8
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2b30a50 VA: 0x7595148a50
	private Void _EventOnBtnBack() { }
	// RVA: 0x2b30b2c VA: 0x7595148b2c
	public Void EventOnBtnBackClick() { }
	// RVA: 0x2b30b94 VA: 0x7595148b94
	public Void EventOnBtnConfirm() { }
	// RVA: 0x2b310d8 VA: 0x75951490d8
	public Void .ctor() { }
	// RVA: 0x2b31210 VA: 0x7595149210
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2b31218 VA: 0x7595149218
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```