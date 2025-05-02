# ActMultiV3LifeCycleViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActState state`

- `Int64 startTime`

- `Int64 endTime`

- `Int64 rewardEndTime`

- `Int64 nextTime`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3LifeCycleViewModel : IHotfixable
{
	public ActState state; // 0x10
	public Int64 startTime; // 0x18
	public Int64 endTime; // 0x20
	public Int64 rewardEndTime; // 0x28
	public Int64 nextTime; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30f0b58 VA: 0x7595708b58
	public Void LoadData(String actId) { }
	// RVA: 0x30f0cb8 VA: 0x7595708cb8
	public Void .ctor() { }
}
```