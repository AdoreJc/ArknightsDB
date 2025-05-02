# UIParticleAttractor

**Namespace:** `Torappu.UI`


## Fields

- `ParticleSystem _particleSystem`

- `Single _destinationRadius`

- `Single _delayRate`

- `Single _maxSpeed`

- `Movement _movement`

- `UpdateMode _updateMode`

- `UnityEvent _onAttracted`

- `UIParticle m_uiParticle`


## Properties

- `Single destinationRadius`

- `Single delay`

- `Single maxSpeed`

- `Movement movement`

- `UpdateMode updateMode`

- `UnityEvent onAttracted`

- `ParticleSystem particleSystem`


## Methods

- `Single get_destinationRadius()`

- `Void set_destinationRadius(Single)`

- `Single get_delay()`

- `Void set_delay(Single)`

- `Single get_maxSpeed()`

- `Void set_maxSpeed(Single)`

- `Movement get_movement()`

- `Void set_movement(Movement)`

- `UpdateMode get_updateMode()`

- `Void set_updateMode(UpdateMode)`

- `UnityEvent get_onAttracted()`

- `Void set_onAttracted(UnityEvent)`

- `ParticleSystem get_particleSystem()`

- `Void set_particleSystem(ParticleSystem)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void _AttractParticles(Particle[], Int32)`

- `Vector3 _GetDestinationPosition()`

- `Vector3 GetAttractedPosition(Vector3, Vector3, Single, Single)`

- `Void _ApplyParticleSystem()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UIParticleAttractor : MonoBehaviour
{
	private ParticleSystem _particleSystem; // 0x18
	private Single _destinationRadius; // 0x20
	private Single _delayRate; // 0x24
	private Single _maxSpeed; // 0x28
	private Movement _movement; // 0x2c
	private UpdateMode _updateMode; // 0x30
	private UnityEvent _onAttracted; // 0x38
	private UIParticle m_uiParticle; // 0x40

	public Single destinationRadius { get; set; }
	public Single delay { get; set; }
	public Single maxSpeed { get; set; }
	public Movement movement { get; set; }
	public UpdateMode updateMode { get; set; }
	public UnityEvent onAttracted { get; set; }
	public ParticleSystem particleSystem { get; set; }

	// RVA: 0x6783e4c VA: 0x7598d9be4c
	public Single get_destinationRadius() { }
	// RVA: 0x6783e54 VA: 0x7598d9be54
	public Void set_destinationRadius(Single value) { }
	// RVA: 0x6783e74 VA: 0x7598d9be74
	public Single get_delay() { }
	// RVA: 0x6783e7c VA: 0x7598d9be7c
	public Void set_delay(Single value) { }
	// RVA: 0x6783e84 VA: 0x7598d9be84
	public Single get_maxSpeed() { }
	// RVA: 0x6783e8c VA: 0x7598d9be8c
	public Void set_maxSpeed(Single value) { }
	// RVA: 0x6783e94 VA: 0x7598d9be94
	public Movement get_movement() { }
	// RVA: 0x6783e9c VA: 0x7598d9be9c
	public Void set_movement(Movement value) { }
	// RVA: 0x6783ea4 VA: 0x7598d9bea4
	public UpdateMode get_updateMode() { }
	// RVA: 0x6783eac VA: 0x7598d9beac
	public Void set_updateMode(UpdateMode value) { }
	// RVA: 0x6783eb4 VA: 0x7598d9beb4
	public UnityEvent get_onAttracted() { }
	// RVA: 0x6783ebc VA: 0x7598d9bebc
	public Void set_onAttracted(UnityEvent value) { }
	// RVA: 0x6783ec4 VA: 0x7598d9bec4
	public ParticleSystem get_particleSystem() { }
	// RVA: 0x6783ecc VA: 0x7598d9becc
	public Void set_particleSystem(ParticleSystem value) { }
	// RVA: 0x6784070 VA: 0x7598d9c070
	private Void OnEnable() { }
	// RVA: 0x678418c VA: 0x7598d9c18c
	private Void OnDisable() { }
	// RVA: 0x67842a0 VA: 0x7598d9c2a0
	private Void OnDestroy() { }
	// RVA: 0x67842c8 VA: 0x7598d9c2c8
	internal Void Attract() { }
	// RVA: 0x6784428 VA: 0x7598d9c428
	private Void _AttractParticles(Particle[] particles, Int32 count) { }
	// RVA: 0x6784770 VA: 0x7598d9c770
	private Vector3 _GetDestinationPosition() { }
	// RVA: 0x6784914 VA: 0x7598d9c914
	private Vector3 GetAttractedPosition(Vector3 current, Vector3 target, Single duration, Single time) { }
	// RVA: 0x6783ee8 VA: 0x7598d9bee8
	private Void _ApplyParticleSystem() { }
	// RVA: 0x6784b08 VA: 0x7598d9cb08
	public Void .ctor() { }
}
```