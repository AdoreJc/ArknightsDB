# VCWindowViewModel

**Namespace:** ` `


## Fields

- `String <topicId>k__BackingField`

- `Int32 visionLevel`

- `Int32 maxVisionLvl`

- `String visionStatusIcon`

- `String visionStatus`

- `Color visionStatusClr`

- `String visionDesc1`

- `String visionDesc2`

- `Int32 chaosLevel`

- `Int32 chaosMaxLevel`

- `Int32 chaosValue`

- `Int32 chaosMaxValue`

- `String chaosValueTips`

- `String predictChaosName`

- `String predictChaosDesc`

- `String zoneBuffDesc`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Void _Reset()`

- `Void Load(String, CurrentData, RoguelikeModule)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class VCWindowViewModel
{
	private String <topicId>k__BackingField; // 0x10
	public Int32 visionLevel; // 0x18
	public Int32 maxVisionLvl; // 0x1c
	public String visionStatusIcon; // 0x20
	public String visionStatus; // 0x28
	public Color visionStatusClr; // 0x30
	public String visionDesc1; // 0x40
	public String visionDesc2; // 0x48
	public Int32 chaosLevel; // 0x50
	public Int32 chaosMaxLevel; // 0x54
	public Int32 chaosValue; // 0x58
	public Int32 chaosMaxValue; // 0x5c
	public String chaosValueTips; // 0x60
	public List`1 chaosItems; // 0x68
	public String predictChaosName; // 0x70
	public String predictChaosDesc; // 0x78
	public String zoneBuffDesc; // 0x80

	public String topicId { get; set; }

	// RVA: 0x2ba213c VA: 0x75951ba13c
	public String get_topicId() { }
	// RVA: 0x2ba2144 VA: 0x75951ba144
	private Void set_topicId(String value) { }
	// RVA: 0x2ba214c VA: 0x75951ba14c
	private Void _Reset() { }
	// RVA: 0x2ba1a24 VA: 0x75951b9a24
	public Void Load(String topic, CurrentData currentData, RoguelikeModule moduleData) { }
	// RVA: 0x2ba20ac VA: 0x75951ba0ac
	public Void .ctor() { }
}
```