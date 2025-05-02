# ParticleArray

**Namespace:** `Torappu.Particle`


## Fields

- `Int32 <count>k__BackingField`


## Properties

- `Int32 count`


## Methods

- `Int32 get_count()`

- `Void set_count(Int32)`

- `Void set_particles(Particle[])`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Particle
public class ParticleArray
{
	private const Int32 DEFAULT_CAPACITY; // 0x0
	private Int32 <count>k__BackingField; // 0x10
	private Particle[] <particles>k__BackingField; // 0x18

	public Int32 count { get; set; }
	public Particle[] particles { get; set; }

	// RVA: 0x67a8ed4 VA: 0x7598dc0ed4
	public Int32 get_count() { }
	// RVA: 0x67a8edc VA: 0x7598dc0edc
	private Void set_count(Int32 value) { }
	// RVA: 0x67a8ee4 VA: 0x7598dc0ee4
	public Particle[] get_particles() { }
	// RVA: 0x67a8eec VA: 0x7598dc0eec
	private Void set_particles(Particle[] value) { }
	// RVA: 0x67a7df4 VA: 0x7598dbfdf4
	public static Ref ReadParticles(ParticleSystem ps) { }
	// RVA: 0x67a8ef4 VA: 0x7598dc0ef4
	public Void .ctor() { }
}
```