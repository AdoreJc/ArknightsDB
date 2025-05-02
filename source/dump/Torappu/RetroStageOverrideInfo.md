# RetroStageOverrideInfo

**Namespace:** `Torappu`


## Fields

- `StageDropInfo dropInfo`

- `String zoneId`

- `Int32 apCost`

- `Int32 apFailReturn`

- `Int32 expGain`

- `Int32 goldGain`

- `Int32 passFavor`

- `Int32 completeFavor`

- `Boolean canContinuousBattle`


## Methods

- `Boolean ShouldSerializecanContinuousBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RetroStageOverrideInfo
{
	public StageDropInfo dropInfo; // 0x10
	public String zoneId; // 0x18
	public Int32 apCost; // 0x20
	public Int32 apFailReturn; // 0x24
	public Int32 expGain; // 0x28
	public Int32 goldGain; // 0x2c
	public Int32 passFavor; // 0x30
	public Int32 completeFavor; // 0x34
	public Boolean canContinuousBattle; // 0x38


	// RVA: 0x34a6fc0 VA: 0x7595abefc0
	public Boolean ShouldSerializecanContinuousBattle() { }
	// RVA: 0x34a6fc8 VA: 0x7595abefc8
	public Void .ctor() { }
}
```