# FxUVTweener

**Namespace:** `Torappu.Fx`


## Fields

- `Boolean keepInitOffset`

- `Boolean useSharedMaterial`

- `Boolean protectMainUV`

- `Single xspeed`

- `Single yspeed`

- `Boolean useSecondMap`

- `Boolean protectSecondUV`

- `String secondMapName`

- `Single secondXSpeed`

- `Single secondYSpeed`

- `Material m_sharedMaterial`

- `Renderer m_renderer`

- `Vector2 m_v2`

- `Vector4 m_secondMapST`

- `String m_secondMapSTProp`

- `Material m_activeMaterial`


## Properties

- `Material activeMaterial`

- `String secondMapPropertyName`


## Methods

- `Material get_activeMaterial()`

- `String get_secondMapPropertyName()`

- `Void Awake()`

- `Void OnEnable()`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxUVTweener : MonoBehaviour
{
	private const String MATERIAL_KEY; // 0x0
	private const Single SPEED_SCALE; // 0x0
	public Boolean keepInitOffset; // 0x18
	public Boolean useSharedMaterial; // 0x19
	public Boolean protectMainUV; // 0x1a
	public Single xspeed; // 0x1c
	public Single yspeed; // 0x20
	public Boolean useSecondMap; // 0x24
	public Boolean protectSecondUV; // 0x25
	public String secondMapName; // 0x28
	public Single secondXSpeed; // 0x30
	public Single secondYSpeed; // 0x34
	private Material m_sharedMaterial; // 0x38
	private Renderer m_renderer; // 0x40
	private Vector2 m_v2; // 0x48
	private Vector4 m_secondMapST; // 0x50
	private String m_secondMapSTProp; // 0x60
	private Material m_activeMaterial; // 0x68

	private Material activeMaterial { get; }
	private String secondMapPropertyName { get; }

	// RVA: 0x3effc7c VA: 0x7596517c7c
	private Material get_activeMaterial() { }
	// RVA: 0x3effd30 VA: 0x7596517d30
	private String get_secondMapPropertyName() { }
	// RVA: 0x3effd9c VA: 0x7596517d9c
	private Void Awake() { }
	// RVA: 0x3effed0 VA: 0x7596517ed0
	private Void OnEnable() { }
	// RVA: 0x3efff68 VA: 0x7596517f68
	private Void Update() { }
	// RVA: 0x3f000b4 VA: 0x75965180b4
	private Void OnDestroy() { }
	// RVA: 0x3f00130 VA: 0x7596518130
	public Void .ctor() { }
}
```