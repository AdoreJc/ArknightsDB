# VecBreakDefenseRoutePolicy

**Namespace:** `Torappu.UI.VecBreak`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseRoutePolicy : RoutePolicy
{
	private static DelegateBridge __Hotfix0_GetEntryPageParam; // 0x0
	private static DelegateBridge __Hotfix0_GetStageRouteStack; // 0x8
	private static DelegateBridge __Hotfix1_GetStageRouteStack; // 0x10
	private static DelegateBridge __Hotfix0_GetPolicyType; // 0x18
	private static DelegateBridge __Hotfix0_UsePolicy; // 0x20
	private static DelegateBridge __Hotfix0__GeneratePageStack; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x22e0adc VA: 0x75948f8adc
	public override StackElement GetEntryPageParam(CommonEntryRouteInput param) { }
	// RVA: 0x22e0b74 VA: 0x75948f8b74
	public override List`1 GetStageRouteStack(CommonStageRouteInput input) { }
	// RVA: 0x22e10d8 VA: 0x75948f90d8
	public override List`1 GetStageRouteStack(BattleOutRouteInput input) { }
	// RVA: 0x22e11b0 VA: 0x75948f91b0
	protected override String GetPolicyType() { }
	// RVA: 0x22e1230 VA: 0x75948f9230
	protected override Boolean UsePolicy(Condition condition) { }
	// RVA: 0x22e0c24 VA: 0x75948f8c24
	private List`1 _GeneratePageStack(DataBundle stageBundle, Params param) { }
	// RVA: 0x22e144c VA: 0x75948f944c
	public Void .ctor() { }
}
```