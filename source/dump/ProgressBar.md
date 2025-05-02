# ProgressBar

**Namespace:** ` `


## Fields

- `Image _progressBarShadow`

- `Image _progressBar`

- `Rl01OuterBuffSkillMainNode <closure>k__BackingField`

- `Int32 m_totalProgress`

- `Int32 m_cachedProgress`

- `Tween m_tween`


## Properties

- `Rl01OuterBuffSkillMainNode closure`


## Methods

- `Rl01OuterBuffSkillMainNode get_closure()`

- `Void set_closure(Rl01OuterBuffSkillMainNode)`

- `Void DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel)`

- `Single DoRenderFrontNodeUpgradedStatus(Int32, Single, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ProgressBar : IHotfixable
{
	private Image _progressBarShadow; // 0x10
	private Image _progressBar; // 0x18
	private Rl01OuterBuffSkillMainNode <closure>k__BackingField; // 0x20
	private Int32 m_totalProgress; // 0x28
	private Int32 m_cachedProgress; // 0x2c
	private Tween m_tween; // 0x30
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0_DoInitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_DoRenderFrontNodeUpgradedStatus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Rl01OuterBuffSkillMainNode closure { get; set; }

	// RVA: 0x26cf2b8 VA: 0x7594ce72b8
	private Rl01OuterBuffSkillMainNode get_closure() { }
	// RVA: 0x26cce3c VA: 0x7594ce4e3c
	public Void set_closure(Rl01OuterBuffSkillMainNode value) { }
	// RVA: 0x26cd0d0 VA: 0x7594ce50d0
	public Void DoInitIfNot(RoguelikeTopicOuterBuffSkillTreeNodeModel nodeModel) { }
	// RVA: 0x26cd6dc VA: 0x7594ce56dc
	public Single DoRenderFrontNodeUpgradedStatus(Int32 progress, Single delay, Boolean isInit) { }
	// RVA: 0x26cf388 VA: 0x7594ce7388
	public Void .ctor() { }
}
```