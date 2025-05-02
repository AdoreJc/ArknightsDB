# RuntimeCostModifier

**Namespace:** ` `


## Fields

- `Int32 m_value`

- `FP m_rawCostScale`


## Properties

- `Int32 value`

- `FP scale`


## Methods

- `Int32 get_value()`

- `FP get_scale()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RuntimeCostModifier : CardBuffModifier
{
	private Int32 m_value; // 0x18
	private FP m_rawCostScale; // 0x20

	public Int32 value { get; }
	public FP scale { get; }

	// RVA: 0x3fb3cf4 VA: 0x75965cbcf4
	public Void .ctor(Int32 value, FP scale) { }
	// RVA: 0x3fb3d2c VA: 0x75965cbd2c
	public Int32 get_value() { }
	// RVA: 0x3fb3d34 VA: 0x75965cbd34
	public FP get_scale() { }
	// RVA: 0x3fb3d3c VA: 0x75965cbd3c
	public static RuntimeCostModifier CreateRuntimeModifier(Int32 value, FP scale) { }
	// RVA: 0x3fb3db8 VA: 0x75965cbdb8
	public static RuntimeCostModifier CreateRuntimeModifier(Blackboard blackboard) { }
	// RVA: 0x3fb3ebc VA: 0x75965cbebc
	public virtual Void Preprocess(Deck deck) { }
	// RVA: 0x3fb3ec0 VA: 0x75965cbec0
	public virtual Boolean TryGetCostDelta(Card card, out Int32 costDelta) { }
	// RVA: 0x3fb3ecc VA: 0x75965cbecc
	public override Void ApplyFirstPass(Card card, ref CardBuffOptions options) { }
}
```