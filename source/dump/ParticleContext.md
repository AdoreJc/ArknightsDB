# ParticleContext

**Namespace:** ` `


## Fields

- `ParticleSystem <system>k__BackingField`

- `ParticleSystemRenderer <renderer>k__BackingField`

- `Material <mainMaterial>k__BackingField`

- `Material <trailMaterial>k__BackingField`

- `BakeCache <bakeCache>k__BackingField`

- `Vector3 <particleScale>k__BackingField`


## Properties

- `ParticleSystem system`

- `ParticleSystemRenderer renderer`

- `Material mainMaterial`

- `Material trailMaterial`

- `BakeCache bakeCache`

- `Vector3 particleScale`


## Methods

- `ParticleSystem get_system()`

- `Void set_system(ParticleSystem)`

- `ParticleSystemRenderer get_renderer()`

- `Void set_renderer(ParticleSystemRenderer)`

- `Material get_mainMaterial()`

- `Void set_mainMaterial(Material)`

- `Material get_trailMaterial()`

- `Void set_trailMaterial(Material)`

- `BakeCache get_bakeCache()`

- `Void set_bakeCache(BakeCache)`

- `Vector3 get_particleScale()`

- `Void set_particleScale(Vector3)`

- `Boolean IsValidForRenderer()`

- `Void DisableRenderer()`

- `Boolean ShouldRenderTrail()`

- `Boolean ShouldRenderMain()`

- `Void SetVars(ParticleVars)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class ParticleContext
{
	private ParticleSystem <system>k__BackingField; // 0x10
	private ParticleSystemRenderer <renderer>k__BackingField; // 0x18
	private Material <mainMaterial>k__BackingField; // 0x20
	private Material <trailMaterial>k__BackingField; // 0x28
	private BakeCache <bakeCache>k__BackingField; // 0x30
	private Vector3 <particleScale>k__BackingField; // 0x38

	public ParticleSystem system { get; set; }
	public ParticleSystemRenderer renderer { get; set; }
	public Material mainMaterial { get; set; }
	public Material trailMaterial { get; set; }
	public BakeCache bakeCache { get; set; }
	public Vector3 particleScale { get; set; }

	// RVA: 0x67839ac VA: 0x7598d9b9ac
	public ParticleSystem get_system() { }
	// RVA: 0x67839b4 VA: 0x7598d9b9b4
	private Void set_system(ParticleSystem value) { }
	// RVA: 0x67839bc VA: 0x7598d9b9bc
	public ParticleSystemRenderer get_renderer() { }
	// RVA: 0x67839c4 VA: 0x7598d9b9c4
	private Void set_renderer(ParticleSystemRenderer value) { }
	// RVA: 0x67839cc VA: 0x7598d9b9cc
	public Material get_mainMaterial() { }
	// RVA: 0x67839d4 VA: 0x7598d9b9d4
	private Void set_mainMaterial(Material value) { }
	// RVA: 0x67839dc VA: 0x7598d9b9dc
	public Material get_trailMaterial() { }
	// RVA: 0x67839e4 VA: 0x7598d9b9e4
	private Void set_trailMaterial(Material value) { }
	// RVA: 0x67839ec VA: 0x7598d9b9ec
	public BakeCache get_bakeCache() { }
	// RVA: 0x67839f4 VA: 0x7598d9b9f4
	private Void set_bakeCache(BakeCache value) { }
	// RVA: 0x67839fc VA: 0x7598d9b9fc
	public Vector3 get_particleScale() { }
	// RVA: 0x6783a08 VA: 0x7598d9ba08
	private Void set_particleScale(Vector3 value) { }
	// RVA: 0x6781514 VA: 0x7598d99514
	public Boolean IsValidForRenderer() { }
	// RVA: 0x6781478 VA: 0x7598d99478
	public Void DisableRenderer() { }
	// RVA: 0x67815ac VA: 0x7598d995ac
	public Boolean ShouldRenderTrail() { }
	// RVA: 0x6781b28 VA: 0x7598d99b28
	public Boolean ShouldRenderMain() { }
	// RVA: 0x6783a14 VA: 0x7598d9ba14
	private Void .ctor() { }
	// RVA: 0x67836dc VA: 0x7598d9b6dc
	public static ParticleContext Create(ParticleSystem ps) { }
	// RVA: 0x6781244 VA: 0x7598d99244
	public Void SetVars(ParticleVars vars) { }
}
```