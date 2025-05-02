# Blackboard

**Namespace:** ` `


## Fields

- `Boolean isHanging`

- `FP m_unbalanceProtectDueTime`

- `Single m_blinkDistance`

- `Single m_blinkHideTime`

- `Boolean m_blinkUseAnimTime`

- `Enemy <owner>k__BackingField`


## Properties

- `Enemy owner`

- `FP unbalanceProtectDueTime`

- `Single blinkDistance`

- `Single blinkHideTime`

- `Boolean blinkUseAnimTime`


## Methods

- `Enemy get_owner()`

- `Void set_owner(Enemy)`

- `FP get_unbalanceProtectDueTime()`

- `Single get_blinkDistance()`

- `Void set_blinkDistance(Single)`

- `Single get_blinkHideTime()`

- `Void set_blinkHideTime(Single)`

- `Boolean get_blinkUseAnimTime()`

- `Void set_blinkUseAnimTime(Boolean)`

- `Void OnReset()`

- `Void OnTick(FP)`

- `Void OnStop()`

- `Void UpdateUnbalanceProtectTime()`

- `Void ResetUnbalanceProtectTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Blackboard : IBlackboard
{
	public Boolean isHanging; // 0x10
	private FP m_unbalanceProtectDueTime; // 0x18
	private Single m_blinkDistance; // 0x20
	private Single m_blinkHideTime; // 0x24
	private Boolean m_blinkUseAnimTime; // 0x28
	private Enemy <owner>k__BackingField; // 0x30

	public Enemy owner { get; set; }
	public FP unbalanceProtectDueTime { get; }
	public Single blinkDistance { get; set; }
	public Single blinkHideTime { get; set; }
	public Boolean blinkUseAnimTime { get; set; }

	// RVA: 0x1c0a020 VA: 0x7594222020
	public Enemy get_owner() { }
	// RVA: 0x1c0a028 VA: 0x7594222028
	private Void set_owner(Enemy value) { }
	// RVA: 0x1c0a030 VA: 0x7594222030
	public FP get_unbalanceProtectDueTime() { }
	// RVA: 0x1c0a038 VA: 0x7594222038
	public Single get_blinkDistance() { }
	// RVA: 0x1c0a040 VA: 0x7594222040
	public Void set_blinkDistance(Single value) { }
	// RVA: 0x1c0a048 VA: 0x7594222048
	public Single get_blinkHideTime() { }
	// RVA: 0x1c0a050 VA: 0x7594222050
	public Void set_blinkHideTime(Single value) { }
	// RVA: 0x1c0a058 VA: 0x7594222058
	public Boolean get_blinkUseAnimTime() { }
	// RVA: 0x1c0a060 VA: 0x7594222060
	public Void set_blinkUseAnimTime(Boolean value) { }
	// RVA: 0x1c09850 VA: 0x7594221850
	public Void .ctor(Enemy owner) { }
	// RVA: 0x1c0a06c VA: 0x759422206c
	public Void OnReset() { }
	// RVA: 0x1c0a0d4 VA: 0x75942220d4
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x1c0a0d8 VA: 0x75942220d8
	public Void OnStop() { }
	// RVA: 0x1c0a0dc VA: 0x75942220dc
	public Void UpdateUnbalanceProtectTime() { }
	// RVA: 0x1c0a184 VA: 0x7594222184
	public Void ResetUnbalanceProtectTime() { }
}
```