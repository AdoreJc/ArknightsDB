# SandboxV2RacingBattleStartResponse

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String myRacer`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacingBattleStartResponse : CommonStartBattleResponse
{
	public String myRacer; // 0x38
	public List`1 racers; // 0x40
	public List`1 extraRunes; // 0x48


	// RVA: 0x2606934 VA: 0x7594c1e934
	public override Int32 GetApFailReturn() { }
	// RVA: 0x260693c VA: 0x7594c1e93c
	public override Boolean GetInApProtectPeriod() { }
	// RVA: 0x2606944 VA: 0x7594c1e944
	public override Boolean GetIsApProtect() { }
	// RVA: 0x260694c VA: 0x7594c1e94c
	public override Boolean GetNotifyPowerScoreNotEnoughIfFailed() { }
	// RVA: 0x2606954 VA: 0x7594c1e954
	public Void .ctor() { }
}
```