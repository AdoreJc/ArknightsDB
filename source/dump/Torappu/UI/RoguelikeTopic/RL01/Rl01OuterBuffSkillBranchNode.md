# Rl01OuterBuffSkillBranchNode

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `CanvasGroup _pnlLocked`

- `CanvasGroup _pnlUnlocked`

- `Image _imgBuffIcon`

- `CanvasGroup _borderSelected`

- `Button _btnNode`

- `UIAnimationLocation _animUnlock`

- `SelectedBorderSwitchTween m_selectedBorderSwitchTween`

- `UpgradedBorderSwitchTween m_upgradedBorderSwitchTween`

- `UnlockedSwitchTween m_unlockedSwitchTween`


## Methods

- `Void EventOnButtonClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffSkillBranchNode : Rl01OuterBuffSkillTreeNode
{
	private CanvasGroup _pnlLocked; // 0x48
	private CanvasGroup _pnlUnlocked; // 0x50
	private Image _imgBuffIcon; // 0x58
	private CanvasGroup _borderSelected; // 0x60
	private Button _btnNode; // 0x68
	private UIAnimationLocation _animUnlock; // 0x70
	private SelectedBorderSwitchTween m_selectedBorderSwitchTween; // 0x80
	private UpgradedBorderSwitchTween m_upgradedBorderSwitchTween; // 0x88
	private UnlockedSwitchTween m_unlockedSwitchTween; // 0x90
	private static DelegateBridge __Hotfix0__DoInitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__DoRenderFrontNodeUpgradedStatus; // 0x8
	private static DelegateBridge __Hotfix0__DoRenderIsUpgraded; // 0x10
	private static DelegateBridge __Hotfix0__DoRenderSelection; // 0x18
	private static DelegateBridge __Hotfix0_EventOnButtonClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26cb29c VA: 0x7594ce329c
	protected override Void _DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel nodeModel) { }
	// RVA: 0x26cb3d4 VA: 0x7594ce33d4
	protected override Void _DoRenderFrontNodeUpgradedStatus(Boolean[] frontIsUpgraded, Int32 changedFrontNodeIndex, RoguelikeTopicDevNodeType changedFrontNodeType, Boolean isInit) { }
	// RVA: 0x26cba40 VA: 0x7594ce3a40
	protected override Void _DoRenderIsUpgraded(Boolean isUpgraded, Boolean isInit) { }
	// RVA: 0x26cbbc4 VA: 0x7594ce3bc4
	protected override Void _DoRenderSelection(Boolean isSelected, Boolean isInit) { }
	// RVA: 0x26cbd4c VA: 0x7594ce3d4c
	public Void EventOnButtonClicked() { }
	// RVA: 0x26cbf80 VA: 0x7594ce3f80
	public Void .ctor() { }
}
```