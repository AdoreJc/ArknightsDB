# SharedDataBbModifier

**Namespace:** ` `


## Fields

- `SharedData m_sharedData`

- `PeriodicTimer m_periodTimer`

- `SharedDataBbModifierParam m_param`

- `Single <valueRatio>k__BackingField`


## Properties

- `Single valueRatio`


## Methods

- `Single get_valueRatio()`

- `Void set_valueRatio(Single)`

- `Void SetData(Character, SharedDataBbModifierParam)`

- `Void _DoModifySharedData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SharedDataBbModifier : CardHoldDataModifier
{
	private SharedData m_sharedData; // 0x10
	private PeriodicTimer m_periodTimer; // 0x18
	private SharedDataBbModifierParam m_param; // 0x20
	private Single <valueRatio>k__BackingField; // 0x38

	public Single valueRatio { get; set; }

	// RVA: 0x1b80b48 VA: 0x7594198b48
	public Single get_valueRatio() { }
	// RVA: 0x1b80b50 VA: 0x7594198b50
	private Void set_valueRatio(Single value) { }
	// RVA: 0x1b809bc VA: 0x75941989bc
	public Void SetData(Character character, SharedDataBbModifierParam param) { }
	// RVA: 0x1b80b58 VA: 0x7594198b58
	public override Void OnTick(Card card, FP deltaTime) { }
	// RVA: 0x1b80cf8 VA: 0x7594198cf8
	private Void _DoModifySharedData() { }
	// RVA: 0x1b80948 VA: 0x7594198948
	public Void .ctor() { }
}
```