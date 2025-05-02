# MainNode

**Namespace:** ` `


## Fields

- `CanvasGroup _pnlLocked`

- `CanvasGroup _pnlUnlocked`

- `Image _imgBuffIcon`

- `CanvasGroup _borderSelected`

- `Image _imgStageNum`

- `Image _imgStageNumBottom`

- `Button _btnNode`

- `UIAnimationLocation _animUnlock`

- `Rl01OuterBuffSkillMainNode <closure>k__BackingField`

- `UpgradedBorderSwitchTween m_upgradedBorderSwitchTween`

- `SelectedBorderSwitchTween m_selectedBorderSwitchTween`

- `UnlockedSwitchTween m_unlockedSwitchTween`

- `Boolean m_cachedCanUpgrade`


## Properties

- `Rl01OuterBuffSkillMainNode closure`


## Methods

- `Rl01OuterBuffSkillMainNode get_closure()`

- `Void set_closure(Rl01OuterBuffSkillMainNode)`

- `Void DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel)`

- `Single DoRenderFrontNodeUpgradedStatus(Boolean, Single, Boolean)`

- `Void DoRenderIsUpgraded(Boolean, Boolean)`

- `Void DoRenderSelection(Boolean, Boolean)`

- `Void EventOnButtonClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MainNode : IHotfixable
{
	private CanvasGroup _pnlLocked; // 0x10
	private CanvasGroup _pnlUnlocked; // 0x18
	private Image _imgBuffIcon; // 0x20
	private CanvasGroup _borderSelected; // 0x28
	private Image _imgStageNum; // 0x30
	private Image _imgStageNumBottom; // 0x38
	private Button _btnNode; // 0x40
	private UIAnimationLocation _animUnlock; // 0x48
	private Rl01OuterBuffSkillMainNode <closure>k__BackingField; // 0x58
	private UpgradedBorderSwitchTween m_upgradedBorderSwitchTween; // 0x60
	private SelectedBorderSwitchTween m_selectedBorderSwitchTween; // 0x68
	private UnlockedSwitchTween m_unlockedSwitchTween; // 0x70
	private Boolean m_cachedCanUpgrade; // 0x78
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0_DoInitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_DoRenderFrontNodeUpgradedStatus; // 0x18
	private static DelegateBridge __Hotfix0_DoRenderIsUpgraded; // 0x20
	private static DelegateBridge __Hotfix0_DoRenderSelection; // 0x28
	private static DelegateBridge __Hotfix0_EventOnButtonClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Rl01OuterBuffSkillMainNode closure { get; set; }

	// RVA: 0x26cde5c VA: 0x7594ce5e5c
	private Rl01OuterBuffSkillMainNode get_closure() { }
	// RVA: 0x26ccec0 VA: 0x7594ce4ec0
	public Void set_closure(Rl01OuterBuffSkillMainNode value) { }
	// RVA: 0x26cd238 VA: 0x7594ce5238
	public Void DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel nodeModel) { }
	// RVA: 0x26cd9a8 VA: 0x7594ce59a8
	public Single DoRenderFrontNodeUpgradedStatus(Boolean canUpgrade, Single delay, Boolean isInit) { }
	// RVA: 0x26cdb74 VA: 0x7594ce5b74
	public Void DoRenderIsUpgraded(Boolean isUpgraded, Boolean isInit) { }
	// RVA: 0x26cdcf8 VA: 0x7594ce5cf8
	public Void DoRenderSelection(Boolean isSelected, Boolean isInit) { }
	// RVA: 0x26ce0bc VA: 0x7594ce60bc
	public Void EventOnButtonClicked() { }
	// RVA: 0x26ce1e4 VA: 0x7594ce61e4
	public Void .ctor() { }
}
```