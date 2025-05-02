# RemainingRespawnTimeModifier

**Namespace:** ` `


## Fields

- `FP m_value`

- `Boolean m_isRatio`


## Properties

- `FP value`

- `Boolean isRatio`


## Methods

- `FP get_value()`

- `Boolean get_isRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RemainingRespawnTimeModifier : CardBuffModifier
{
	private FP m_value; // 0x18
	private Boolean m_isRatio; // 0x20

	public FP value { get; }
	public Boolean isRatio { get; }

	// RVA: 0x3fb43bc VA: 0x75965cc3bc
	private Void .ctor(FP value, Boolean isRatio) { }
	// RVA: 0x3fb43f4 VA: 0x75965cc3f4
	public FP get_value() { }
	// RVA: 0x3fb43fc VA: 0x75965cc3fc
	public Boolean get_isRatio() { }
	// RVA: 0x3fb4404 VA: 0x75965cc404
	public static RemainingRespawnTimeModifier CreateRuntimeModifier(FP value, Boolean isRatio) { }
	// RVA: 0x3fb4484 VA: 0x75965cc484
	public static RemainingRespawnTimeModifier CreateRuntimeModifier(Blackboard blackboard, Boolean isRatio) { }
	// RVA: 0x3fb4508 VA: 0x75965cc508
	public override Void ApplyFirstPass(Card card, ref CardBuffOptions options) { }
	// RVA: 0x3fb45c0 VA: 0x75965cc5c0
	public override Void ApplySecondPass(Card card, ref CardBuffOptions options) { }
}
```