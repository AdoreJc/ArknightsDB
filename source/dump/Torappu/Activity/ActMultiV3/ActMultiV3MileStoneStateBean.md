# ActMultiV3MileStoneStateBean

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3MilestoneProp m_prop`


## Properties

- `ActMultiV3MilestoneProp mileStoneProp`


## Methods

- `ActMultiV3MilestoneProp get_mileStoneProp()`

- `Void InitModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MileStoneStateBean : IStateBean, IHotfixable
{
	private ActMultiV3MilestoneProp m_prop; // 0x10
	private static DelegateBridge __Hotfix0_get_mileStoneProp; // 0x0
	private static DelegateBridge __Hotfix0_InitModel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public ActMultiV3MilestoneProp mileStoneProp { get; }

	// RVA: 0x30f4068 VA: 0x759570c068
	public ActMultiV3MilestoneProp get_mileStoneProp() { }
	// RVA: 0x30f3fc0 VA: 0x759570bfc0
	public Void InitModel(String actId) { }
	// RVA: 0x30f4dac VA: 0x759570cdac
	public Void .ctor() { }
}
```