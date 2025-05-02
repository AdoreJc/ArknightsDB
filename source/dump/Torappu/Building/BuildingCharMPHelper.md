# BuildingCharMPHelper

**Namespace:** `Torappu.Building`


## Fields

- `CountDownTask m_countDown`

- `BuildingCharModel m_cachedModel`

- `Action onManpowerChanged`


## Properties

- `BuildingCharModel charModel`


## Methods

- `BuildingCharModel get_charModel()`

- `Void Reset(BuildingCharModel)`

- `Void Tick()`

- `Void _OnTimeout()`

- `Void _UpdateCountDown()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingCharMPHelper
{
	private CountDownTask m_countDown; // 0x10
	private BuildingCharModel m_cachedModel; // 0x18
	public Action onManpowerChanged; // 0x88

	public BuildingCharModel charModel { get; }

	// RVA: 0x3787ca4 VA: 0x7595d9fca4
	public BuildingCharModel get_charModel() { }
	// RVA: 0x3787cb4 VA: 0x7595d9fcb4
	public Void Reset(BuildingCharModel model) { }
	// RVA: 0x3787e0c VA: 0x7595d9fe0c
	public Void Tick() { }
	// RVA: 0x3787e28 VA: 0x7595d9fe28
	private Void _OnTimeout() { }
	// RVA: 0x3787ce0 VA: 0x7595d9fce0
	private Void _UpdateCountDown() { }
	// RVA: 0x3787e58 VA: 0x7595d9fe58
	public Void .ctor() { }
}
```