# FxUVTweenerAdvance

**Namespace:** `Torappu.Fx`


## Fields

- `Boolean tweenRepeat`

- `Single tweenAnmTime`

- `Boolean keepInitOffset`

- `Boolean useSharedMaterial`

- `Single xspeed`

- `Single yspeed`

- `Boolean useSecondMap`

- `String secondMapName`

- `Single secondXSpeed`

- `Single secondYSpeed`

- `Single m_time`

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
public class FxUVTweenerAdvance : MonoBehaviour
{
	private const String MATERIAL_KEY; // 0x0
	private const Single SPEED_SCALE; // 0x0
	public Boolean tweenRepeat; // 0x18
	public Single tweenAnmTime; // 0x1c
	public Boolean keepInitOffset; // 0x20
	public Boolean useSharedMaterial; // 0x21
	public Single xspeed; // 0x24
	public Single yspeed; // 0x28
	public Boolean useSecondMap; // 0x2c
	public String secondMapName; // 0x30
	public Single secondXSpeed; // 0x38
	public Single secondYSpeed; // 0x3c
	public List`1 extraMapSettings; // 0x40
	private Single m_time; // 0x48
	private Material m_sharedMaterial; // 0x50
	private Renderer m_renderer; // 0x58
	private Vector2 m_v2; // 0x60
	private Vector4 m_secondMapST; // 0x68
	private String m_secondMapSTProp; // 0x78
	private Material m_activeMaterial; // 0x80

	private Material activeMaterial { get; }
	private String secondMapPropertyName { get; }

	// RVA: 0x3f00188 VA: 0x7596518188
	private Material get_activeMaterial() { }
	// RVA: 0x3f0023c VA: 0x759651823c
	private String get_secondMapPropertyName() { }
	// RVA: 0x3f002a8 VA: 0x75965182a8
	private Void Awake() { }
	// RVA: 0x3f005b8 VA: 0x75965185b8
	private Void OnEnable() { }
	// RVA: 0x3f007a0 VA: 0x75965187a0
	private Void Update() { }
	// RVA: 0x3f00a74 VA: 0x7596518a74
	private Void OnDestroy() { }
	// RVA: 0x3f00af0 VA: 0x7596518af0
	public Void .ctor() { }
}
```