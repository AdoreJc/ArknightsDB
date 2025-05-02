# EnterRoomConfig

**Namespace:** ` `


## Methods

- `Void _HandleResult(JoinResultType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnterRoomConfig : CommonInputDialogServiceConfirmConfig`2
{
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_OnValidateResponse; // 0x10
	private static DelegateBridge __Hotfix0__HandleResult; // 0x18
	private static DelegateBridge __Hotfix0_OnInputFieldValueChange; // 0x20
	private static DelegateBridge __Hotfix0_OnInputFieldEndEdit; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String serviceCode { get; }

	// RVA: 0x294a994 VA: 0x7594f62994
	protected override EnemyDuelJoinTeamRequest ParseRequest(ValueBundle param, String inputText) { }
	// RVA: 0x294aa74 VA: 0x7594f62a74
	protected override String get_serviceCode() { }
	// RVA: 0x294aaf0 VA: 0x7594f62af0
	protected override Boolean OnValidateResponse(ValueBundle param, String inputText, EnemyDuelJoinTeamResponse response) { }
	// RVA: 0x294aca4 VA: 0x7594f62ca4
	private Void _HandleResult(JoinResultType result) { }
	// RVA: 0x294add4 VA: 0x7594f62dd4
	public override String OnInputFieldValueChange(String input) { }
	// RVA: 0x294ae50 VA: 0x7594f62e50
	public override String OnInputFieldEndEdit(String input) { }
	// RVA: 0x294aef0 VA: 0x7594f62ef0
	public Void .ctor() { }
}
```