# HeightController

**Namespace:** ` `


## Fields

- `Enemy m_owner`

- `Single m_curHeight`

- `Single m_targetHeight`

- `Single m_levitateHeight`

- `Boolean m_changeHeightImmediately`


## Properties

- `Single curHeight`


## Methods

- `Void OnInit(Single)`

- `Void Reset(Enemy)`

- `Void SetEnemyHeight(Single)`

- `Single get_curHeight()`

- `Void SetEnemyHeightOffset(Single, Boolean, Boolean)`

- `Void AdjustEnemyHeightByInitial(Single, Boolean)`

- `Void SetHeightImmediatelyChange()`

- `Void SetEnemyLevitateOffset(Single)`

- `Void OnTick(FP)`

- `Void _UpdateHeight(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HeightController
{
	private static Single DELTA_OFFSET; // 0x0
	private Enemy m_owner; // 0x10
	private Single m_curHeight; // 0x18
	private Single m_targetHeight; // 0x1c
	private Single m_levitateHeight; // 0x20
	private Boolean m_changeHeightImmediately; // 0x24

	public Single curHeight { get; }

	// RVA: 0x1c188d8 VA: 0x75942308d8
	public Void OnInit(Single initHeight) { }
	// RVA: 0x1c188e4 VA: 0x75942308e4
	public Void Reset(Enemy owner) { }
	// RVA: 0x1c188ec VA: 0x75942308ec
	public Void SetEnemyHeight(Single height) { }
	// RVA: 0x1c188f8 VA: 0x75942308f8
	public Single get_curHeight() { }
	// RVA: 0x1c18900 VA: 0x7594230900
	public Void SetEnemyHeightOffset(Single offset, Boolean instant, Boolean isSet) { }
	// RVA: 0x1c18950 VA: 0x7594230950
	public Void AdjustEnemyHeightByInitial(Single offset, Boolean instant) { }
	// RVA: 0x1c18998 VA: 0x7594230998
	public Void SetHeightImmediatelyChange() { }
	// RVA: 0x1c189a4 VA: 0x75942309a4
	public Void SetEnemyLevitateOffset(Single offset) { }
	// RVA: 0x1c189b4 VA: 0x75942309b4
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x1c189f0 VA: 0x75942309f0
	private Void _UpdateHeight(Single destHeight) { }
	// RVA: 0x1c18b64 VA: 0x7594230b64
	public Void .ctor() { }
	// RVA: 0x1c18b6c VA: 0x7594230b6c
	private static Void .cctor() { }
}
```