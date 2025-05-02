# BagLightController

**Namespace:** `Torappu.Gacha`


## Fields

- `String _padAudioSignal`

- `Vector2 _padProgressRange`

- `Vector2 _padVolumeLevelRange`


## Methods

- `Void OnEnter()`

- `Void OnExit()`

- `Void UpdatePillars(Single)`

- `Void PreloadAudioSignals()`

- `Void _SetAllActive(Boolean)`

- `Void _SetPadSeVolumn(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class BagLightController : MonoBehaviour
{
	private LightPillar[] _pillars; // 0x18
	private String _padAudioSignal; // 0x20
	private Vector2 _padProgressRange; // 0x28
	private Vector2 _padVolumeLevelRange; // 0x30
	private AudioAtom[] m_atoms; // 0x38


	// RVA: 0x36fba98 VA: 0x7595d13a98
	public Void OnEnter() { }
	// RVA: 0x36fbc84 VA: 0x7595d13c84
	public Void OnExit() { }
	// RVA: 0x36fbd20 VA: 0x7595d13d20
	public Void UpdatePillars(Single progress) { }
	// RVA: 0x36fbeb0 VA: 0x7595d13eb0
	public Void PreloadAudioSignals() { }
	// RVA: 0x36fbb6c VA: 0x7595d13b6c
	private Void _SetAllActive(Boolean active) { }
	// RVA: 0x36fbbe0 VA: 0x7595d13be0
	private Void _SetPadSeVolumn(Single progress) { }
	// RVA: 0x36fbfd4 VA: 0x7595d13fd4
	public Void .ctor() { }
}
```