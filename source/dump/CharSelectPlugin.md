# CharSelectPlugin

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharSelectPlugin : Plugin`1
{
	private static DelegateBridge __Hotfix0_OverrideCharSelect; // 0x0
	private static DelegateBridge __Hotfix0_OverrideSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_OverrideBranchSelect; // 0x10
	private static DelegateBridge __Hotfix0_OverrideDismiss; // 0x18
	private static DelegateBridge __Hotfix0_AddCharMultiSelectExcludeRule; // 0x20
	private static DelegateBridge __Hotfix0_get_cardMaskPrefab; // 0x28
	private static DelegateBridge __Hotfix0_OverrideSelectConfirmed; // 0x30
	private static DelegateBridge __Hotfix0_OverrideSelectCanceled; // 0x38
	private static DelegateBridge __Hotfix0_get_overrideNoCharText; // 0x40
	private static DelegateBridge __Hotfix0_get_showCharInfoEntry; // 0x48
	private static DelegateBridge __Hotfix0_OverrideUpdateSelectedSkill; // 0x50
	private static DelegateBridge __Hotfix0_OverrideUpdateSelectedBranch; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override CharSelectCardMaskPlugin cardMaskPrefab { get; }
	public override String overrideNoCharText { get; }
	public override Boolean showCharInfoEntry { get; }

	// RVA: 0x33a67e4 VA: 0x75959be7e4
	public override Void OverrideCharSelect(Int32 instId, Action`1 selfCharSelect) { }
	// RVA: 0x33a68bc VA: 0x75959be8bc
	public override Void OverrideSkillSelect(String skillId, Action`1 selfSkillSelect) { }
	// RVA: 0x33a6954 VA: 0x75959be954
	public override Void OverrideBranchSelect(String equipId, Action`1 selfBranchSelect) { }
	// RVA: 0x33a69ec VA: 0x75959be9ec
	public override Void OverrideDismiss(Action selfDismiss) { }
	// RVA: 0x33a6a78 VA: 0x75959bea78
	public override Void AddCharMultiSelectExcludeRule(Int32 instId, List`1 excludeInstIds) { }
	// RVA: 0x33a6bf4 VA: 0x75959bebf4
	public override CharSelectCardMaskPlugin get_cardMaskPrefab() { }
	// RVA: 0x33a6c84 VA: 0x75959bec84
	public override Void OverrideSelectConfirmed(Action selfConfirm) { }
	// RVA: 0x33a6d10 VA: 0x75959bed10
	public override Void OverrideSelectCanceled(Action selfCancel) { }
	// RVA: 0x33a6d9c VA: 0x75959bed9c
	public override String get_overrideNoCharText() { }
	// RVA: 0x33a6e20 VA: 0x75959bee20
	public override Boolean get_showCharInfoEntry() { }
	// RVA: 0x33a6e88 VA: 0x75959bee88
	public override String OverrideUpdateSelectedSkill(Int32 instId, String prevSkill, Func`3 selfUpdateSelectSkill) { }
	// RVA: 0x33a6f58 VA: 0x75959bef58
	public override String OverrideUpdateSelectedBranch(Int32 instId, String prevBranch, Func`3 selfUpdateSelectBranch) { }
	// RVA: 0x33a7028 VA: 0x75959bf028
	public Void .ctor() { }
}
```