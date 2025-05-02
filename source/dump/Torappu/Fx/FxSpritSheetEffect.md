# FxSpritSheetEffect

**Namespace:** `Torappu.Fx`


## Fields

- `Int32 row`

- `Int32 column`

- `Single duration`

- `Boolean loop`

- `Single m_time`

- `Single m_perFrameTime`

- `Int32 m_totalFrameNum`

- `Material m_varyingMaterial`


## Properties

- `Material VaryingMaterial`


## Methods

- `Material get_VaryingMaterial()`

- `Void Start()`

- `Void Update()`

- `Void OnEnable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxSpritSheetEffect : MonoBehaviour
{
	public Int32 row; // 0x18
	public Int32 column; // 0x1c
	public Single duration; // 0x20
	public Boolean loop; // 0x24
	private Single m_time; // 0x28
	private Single m_perFrameTime; // 0x2c
	private Int32 m_totalFrameNum; // 0x30
	private readonly Int32 HG_FX_OUT_CTRL_PROP; // 0x34
	private readonly Int32 HG_FX_SPRITE_SHEET_PARAM_PROP; // 0x38
	private Material m_varyingMaterial; // 0x40

	private Material VaryingMaterial { get; }

	// RVA: 0x3efee98 VA: 0x7596516e98
	private Material get_VaryingMaterial() { }
	// RVA: 0x3efef50 VA: 0x7596516f50
	private Void Start() { }
	// RVA: 0x3efefac VA: 0x7596516fac
	private Void Update() { }
	// RVA: 0x3eff114 VA: 0x7596517114
	private Void OnEnable() { }
	// RVA: 0x3eff11c VA: 0x759651711c
	private Void OnDestroy() { }
	// RVA: 0x3eff1c8 VA: 0x75965171c8
	public Void .ctor() { }
}
```