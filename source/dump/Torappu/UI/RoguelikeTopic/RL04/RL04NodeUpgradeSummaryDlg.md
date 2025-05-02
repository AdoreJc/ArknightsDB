# RL04NodeUpgradeSummaryDlg

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `RL04NodeUpgradeSummaryView _view`

- `RectTransform _topMenuContainer`

- `UIGuidebookTrigger _guideBookTrigger`

- `Boolean m_hasInited`

- `String m_topicId`

- `RL04NodeUpgradeSummaryProp m_prop`

- `CommonTopMenu m_topMenu`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnBtnTypeClick(RoguelikeEventType)`

- `Void _EventOnBtnBack()`

- `RL04NodeUpgradeConfig GetNodeConfig(RoguelikeEventType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04NodeUpgradeSummaryDlg : UICompDialog`1, INodeConfigFetcher
{
	private const String GUIDE_SUB_SIGNAL; // 0x0
	private RL04NodeUpgradeSummaryView _view; // 0x48
	private RectTransform _topMenuContainer; // 0x50
	private UIGuidebookTrigger _guideBookTrigger; // 0x58
	private Boolean m_hasInited; // 0x60
	private String m_topicId; // 0x68
	private Dictionary`2 m_nodeConfigDict; // 0x70
	private RL04NodeUpgradeSummaryProp m_prop; // 0x78
	private CommonTopMenu m_topMenu; // 0x80
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__EventOnBtnTypeClick; // 0x10
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x18
	private static DelegateBridge __Hotfix0_GetNodeConfig; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26e3f18 VA: 0x7594cfbf18
	protected override Void OnRender(Input input) { }
	// RVA: 0x26e40ec VA: 0x7594cfc0ec
	private Void _InitIfNot() { }
	// RVA: 0x26e4824 VA: 0x7594cfc824
	private Void _EventOnBtnTypeClick(RoguelikeEventType nodeType) { }
	// RVA: 0x26e4a34 VA: 0x7594cfca34
	private Void _EventOnBtnBack() { }
	// RVA: 0x26e4b08 VA: 0x7594cfcb08
	public RL04NodeUpgradeConfig GetNodeConfig(RoguelikeEventType type) { }
	// RVA: 0x26e4d0c VA: 0x7594cfcd0c
	public Void .ctor() { }
}
```