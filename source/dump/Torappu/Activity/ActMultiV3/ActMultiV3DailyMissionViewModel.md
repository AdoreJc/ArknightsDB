# ActMultiV3DailyMissionViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 maxDailyMissionPoint`

- `Int32 currDailyMissionPoint`

- `Boolean completed`


## Methods

- `Void LoadData(String, PlayerMultiV3Activity, ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3DailyMissionViewModel : IHotfixable
{
	public Int32 maxDailyMissionPoint; // 0x10
	public Int32 currDailyMissionPoint; // 0x14
	public Boolean completed; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30f1138 VA: 0x7595709138
	public Void LoadData(String actId, PlayerMultiV3Activity playerActivity, ActMultiV3Data actData) { }
	// RVA: 0x30f1214 VA: 0x7595709214
	public Void .ctor() { }
}
```