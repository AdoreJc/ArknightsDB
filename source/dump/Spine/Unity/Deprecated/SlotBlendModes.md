# SlotBlendModes

**Namespace:** `Spine.Unity.Deprecated`


## Fields

- `Material multiplyMaterialSource`

- `Material screenMaterialSource`

- `Texture2D texture`

- `Boolean <Applied>k__BackingField`


## Properties

- `Boolean Applied`


## Methods

- `Boolean get_Applied()`

- `Void set_Applied(Boolean)`

- `Void Start()`

- `Void OnDestroy()`

- `Void Apply()`

- `Void Remove()`

- `Void GetTexture()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity.Deprecated
public class SlotBlendModes : MonoBehaviour
{
	private static Dictionary`2 materialTable; // 0x0
	public Material multiplyMaterialSource; // 0x18
	public Material screenMaterialSource; // 0x20
	private Texture2D texture; // 0x28
	private SlotMaterialTextureTuple[] slotsWithCustomMaterial; // 0x30
	private Boolean <Applied>k__BackingField; // 0x38

	internal static Dictionary`2 MaterialTable { get; }
	public Boolean Applied { get; set; }

	// RVA: 0x6226928 VA: 0x759883e928
	internal static Dictionary`2 get_MaterialTable() { }
	// RVA: 0x62269e0 VA: 0x759883e9e0
	internal static Material GetOrAddMaterialFor(Material materialSource, Texture2D texture) { }
	// RVA: 0x6226ca0 VA: 0x759883eca0
	internal static MaterialWithRefcount GetExistingMaterialFor(Material materialSource, Texture2D texture) { }
	// RVA: 0x6226dbc VA: 0x759883edbc
	internal static Void RemoveMaterialFromTable(Material materialSource, Texture2D texture) { }
	// RVA: 0x6226e4c VA: 0x759883ee4c
	public Boolean get_Applied() { }
	// RVA: 0x6226e54 VA: 0x759883ee54
	private Void set_Applied(Boolean value) { }
	// RVA: 0x6226e60 VA: 0x759883ee60
	private Void Start() { }
	// RVA: 0x6227414 VA: 0x759883f414
	private Void OnDestroy() { }
	// RVA: 0x6226e70 VA: 0x759883ee70
	public Void Apply() { }
	// RVA: 0x6227424 VA: 0x759883f424
	public Void Remove() { }
	// RVA: 0x6227628 VA: 0x759883f628
	public Void GetTexture() { }
	// RVA: 0x6227844 VA: 0x759883f844
	public Void .ctor() { }
}
```