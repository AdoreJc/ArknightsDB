# SelectCharPlugin

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SelectCharPlugin : Plugin`1
{
	private static DelegateBridge __Hotfix0_get_overrideNoCharText; // 0x0
	private static DelegateBridge __Hotfix0_get_showCharInfoEntry; // 0x8
	private static DelegateBridge __Hotfix0_get_cardMaskPrefab; // 0x10
	private static DelegateBridge __Hotfix0_OverrideCharSelect; // 0x18
	private static DelegateBridge __Hotfix0_OverrideDismiss; // 0x20
	private static DelegateBridge __Hotfix0_OverrideSelectCanceled; // 0x28
	private static DelegateBridge __Hotfix0_OverrideSkillSelect; // 0x30
	private static DelegateBridge __Hotfix0_OverrideBranchSelect; // 0x38
	private static DelegateBridge __Hotfix0_PostUpdateAttribute; // 0x40
	private static DelegateBridge __Hotfix0_OverrideSelectConfirmed; // 0x48
	private static DelegateBridge __Hotfix0_AddCharMultiSelectExcludeRule; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override String overrideNoCharText { get; }
	public override Boolean showCharInfoEntry { get; }
	public override CharSelectCardMaskPlugin cardMaskPrefab { get; }

	// RVA: 0x28ae798 VA: 0x7594ec6798
	public override String get_overrideNoCharText() { }
	// RVA: 0x28ae81c VA: 0x7594ec681c
	public override Boolean get_showCharInfoEntry() { }
	// RVA: 0x28ae884 VA: 0x7594ec6884
	public override CharSelectCardMaskPlugin get_cardMaskPrefab() { }
	// RVA: 0x28ae8e8 VA: 0x7594ec68e8
	public override Void OverrideCharSelect(Int32 instId, Action`1 selfCharSelect) { }
	// RVA: 0x28aeca4 VA: 0x7594ec6ca4
	public override Void OverrideDismiss(Action selfDismiss) { }
	// RVA: 0x28aed30 VA: 0x7594ec6d30
	public override Void OverrideSelectCanceled(Action selfCancel) { }
	// RVA: 0x28aedbc VA: 0x7594ec6dbc
	public override Void OverrideSkillSelect(String skillId, Action`1 selfSkillSelect) { }
	// RVA: 0x28aee54 VA: 0x7594ec6e54
	public override Void OverrideBranchSelect(String equipId, Action`1 selfBranchSelect) { }
	// RVA: 0x28aeeec VA: 0x7594ec6eec
	public override Void PostUpdateAttribute(CharAttrViewModel attrModel) { }
	// RVA: 0x28aef84 VA: 0x7594ec6f84
	public override Void OverrideSelectConfirmed(Action selfConfirm) { }
	// RVA: 0x28af010 VA: 0x7594ec7010
	public override Void AddCharMultiSelectExcludeRule(Int32 instId, List`1 excludeInstIds) { }
	// RVA: 0x28af090 VA: 0x7594ec7090
	public Void .ctor() { }
}
```