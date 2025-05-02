# ProgressNode

**Namespace:** ` `


## Fields

- `UIAnimationLocation _animUnlock`

- `Text _unlockedText`

- `Rl01OuterBuffSkillMainNode <closure>k__BackingField`

- `UnlockedSwitchTween m_unlockedSwitchTween`

- `Boolean m_cachedCanUpgrade`


## Properties

- `Rl01OuterBuffSkillMainNode closure`


## Methods

- `Rl01OuterBuffSkillMainNode get_closure()`

- `Void set_closure(Rl01OuterBuffSkillMainNode)`

- `Void DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel)`

- `Single DoRenderFrontNodeUpgradedStatus(Boolean, Single, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ProgressNode : IHotfixable
{
	private UIAnimationLocation _animUnlock; // 0x10
	private Text _unlockedText; // 0x20
	private Rl01OuterBuffSkillMainNode <closure>k__BackingField; // 0x28
	private UnlockedSwitchTween m_unlockedSwitchTween; // 0x30
	private Boolean m_cachedCanUpgrade; // 0x38
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0_DoInitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_DoRenderFrontNodeUpgradedStatus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Rl01OuterBuffSkillMainNode closure { get; set; }

	// RVA: 0x26cec38 VA: 0x7594ce6c38
	private Rl01OuterBuffSkillMainNode get_closure() { }
	// RVA: 0x26ccdb8 VA: 0x7594ce4db8
	public Void set_closure(Rl01OuterBuffSkillMainNode value) { }
	// RVA: 0x26ccfec VA: 0x7594ce4fec
	public Void DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel nodeModel) { }
	// RVA: 0x26cd874 VA: 0x7594ce5874
	public Single DoRenderFrontNodeUpgradedStatus(Boolean canUpgrade, Single delay, Boolean isInit) { }
	// RVA: 0x26ced34 VA: 0x7594ce6d34
	public Void .ctor() { }
}
```