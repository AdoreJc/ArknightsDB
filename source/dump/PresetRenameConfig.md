# PresetRenameConfig

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PresetRenameConfig : CommonInputDialogServiceConfirmConfig`2
{
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_OnValidateResponse; // 0x10
	private static DelegateBridge __Hotfix0_OnInputFieldValueChange; // 0x18
	private static DelegateBridge __Hotfix0_OnInputFieldEndEdit; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String serviceCode { get; }

	// RVA: 0x27de5e4 VA: 0x7594df65e4
	protected override CharRotationUpdatePresetRequest ParseRequest(ValueBundle param, String inputText) { }
	// RVA: 0x27de730 VA: 0x7594df6730
	protected override String get_serviceCode() { }
	// RVA: 0x27de7ac VA: 0x7594df67ac
	protected override Boolean OnValidateResponse(ValueBundle param, String inputText, CharRotationUpdatePresetResponse response) { }
	// RVA: 0x27de864 VA: 0x7594df6864
	public override String OnInputFieldValueChange(String input) { }
	// RVA: 0x27de8e0 VA: 0x7594df68e0
	public override String OnInputFieldEndEdit(String input) { }
	// RVA: 0x27de95c VA: 0x7594df695c
	public Void .ctor() { }
}
```