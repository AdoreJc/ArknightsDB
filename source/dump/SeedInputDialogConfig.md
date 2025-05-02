# SeedInputDialogConfig

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SeedInputDialogConfig : CommonInputDialogServiceConfirmConfig`2
{
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_OnValidateResponse; // 0x10
	private static DelegateBridge __Hotfix0_OnInputFieldValueChange; // 0x18
	private static DelegateBridge __Hotfix0_OnInputFieldEndEdit; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String serviceCode { get; }

	// RVA: 0x26df854 VA: 0x7594cf7854
	protected override RoguelikeTopicSetSeedRequest ParseRequest(ValueBundle param, String inputText) { }
	// RVA: 0x26df994 VA: 0x7594cf7994
	protected override String get_serviceCode() { }
	// RVA: 0x26dfa10 VA: 0x7594cf7a10
	protected override Boolean OnValidateResponse(ValueBundle param, String inputText, RoguelikeTopicSetSeedResponse response) { }
	// RVA: 0x26dfb44 VA: 0x7594cf7b44
	public override String OnInputFieldValueChange(String input) { }
	// RVA: 0x26dfbc4 VA: 0x7594cf7bc4
	public override String OnInputFieldEndEdit(String input) { }
	// RVA: 0x26dfc44 VA: 0x7594cf7c44
	public Void .ctor() { }
}
```