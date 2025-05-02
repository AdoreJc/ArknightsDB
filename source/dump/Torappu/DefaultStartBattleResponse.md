# DefaultStartBattleResponse

**Namespace:** `Torappu`


## Fields

- `Boolean isApProtect`

- `Int32 apFailReturn`

- `Boolean notifyPowerScoreNotEnoughIfFailed`

- `Boolean inApProtectPeriod`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DefaultStartBattleResponse : CommonStartBattleResponse
{
	public Boolean isApProtect; // 0x38
	public Int32 apFailReturn; // 0x3c
	public Boolean notifyPowerScoreNotEnoughIfFailed; // 0x40
	public Boolean inApProtectPeriod; // 0x41


	// RVA: 0x32cdca0 VA: 0x75958e5ca0
	public override Int32 GetApFailReturn() { }
	// RVA: 0x32cdca8 VA: 0x75958e5ca8
	public override Boolean GetIsApProtect() { }
	// RVA: 0x32cdcb0 VA: 0x75958e5cb0
	public override Boolean GetNotifyPowerScoreNotEnoughIfFailed() { }
	// RVA: 0x32cdcb8 VA: 0x75958e5cb8
	public override Boolean GetInApProtectPeriod() { }
	// RVA: 0x32cdcc0 VA: 0x75958e5cc0
	public Void .ctor() { }
}
```