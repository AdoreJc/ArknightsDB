# RuntimeRespawnTimeModifier

**Namespace:** ` `


## Fields

- `FP m_value`

- `Boolean m_isOverride`

- `Boolean m_isRatio`

- `Boolean m_disabled`

- `Boolean m_respawnStopped`

- `Boolean m_addRespawnCostMultCnt`


## Properties

- `FP value`

- `Boolean isRatio`

- `Boolean disabled`

- `Boolean respawnStopped`

- `Boolean addRespawnCostMultCnt`


## Methods

- `FP get_value()`

- `Boolean get_isRatio()`

- `Boolean get_disabled()`

- `Boolean get_respawnStopped()`

- `Boolean get_addRespawnCostMultCnt()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RuntimeRespawnTimeModifier : CardBuffModifier
{
	private FP m_value; // 0x18
	private Boolean m_isOverride; // 0x20
	private Boolean m_isRatio; // 0x21
	private Boolean m_disabled; // 0x22
	private Boolean m_respawnStopped; // 0x23
	private Boolean m_addRespawnCostMultCnt; // 0x24

	public FP value { get; }
	public Boolean isRatio { get; }
	public Boolean disabled { get; }
	private Boolean respawnStopped { get; }
	public Boolean addRespawnCostMultCnt { get; }

	// RVA: 0x3fb3f54 VA: 0x75965cbf54
	private Void .ctor(FP value, Boolean isRatio, Boolean disabled, Boolean addRespawnCostMultCnt, Boolean respawnStopped, Boolean isOverride) { }
	// RVA: 0x3fb3fbc VA: 0x75965cbfbc
	public FP get_value() { }
	// RVA: 0x3fb3fc4 VA: 0x75965cbfc4
	public Boolean get_isRatio() { }
	// RVA: 0x3fb3fcc VA: 0x75965cbfcc
	public Boolean get_disabled() { }
	// RVA: 0x3fb3fd4 VA: 0x75965cbfd4
	private Boolean get_respawnStopped() { }
	// RVA: 0x3fb3fdc VA: 0x75965cbfdc
	public Boolean get_addRespawnCostMultCnt() { }
	// RVA: 0x3fb3fe4 VA: 0x75965cbfe4
	public static RuntimeRespawnTimeModifier CreateRuntimeModifier(FP value, Boolean isRatio, Boolean disabled, Boolean addRespawnCostMultCnt, Boolean respawnStopped, Boolean isOverride) { }
	// RVA: 0x3fb40a4 VA: 0x75965cc0a4
	public static RuntimeRespawnTimeModifier CreateRuntimeModifier(Blackboard blackboard, Boolean isRatio) { }
	// RVA: 0x3fb426c VA: 0x75965cc26c
	public override Void ApplyFirstPass(Card card, ref CardBuffOptions options) { }
	// RVA: 0x3fb4334 VA: 0x75965cc334
	public override Void ApplySecondPass(Card card, ref CardBuffOptions options) { }
}
```