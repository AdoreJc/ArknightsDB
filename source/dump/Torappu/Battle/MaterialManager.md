# MaterialManager

**Namespace:** `Torappu.Battle`


## Methods

- `Material GetMaterial(Material, String)`

- `Boolean TryGetMaterialOrNewFromShader(Shader, MaterialKey, out)`

- `Tween StartExclusiveTween(Func`2, Material, String)`

- `Tween StartExclusiveTween(Func`2, Material)`

- `Boolean FinishExclusiveTween(Material, String)`

- `Boolean FinishExclusiveTween(Material)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MaterialManager : SingletonMonoBehaviour`1
{
	private Dictionary`2 m_materialMap; // 0x18
	private Dictionary`2 m_tweenMap; // 0x20
	private static DelegateBridge __Hotfix0_GetMaterial; // 0x0
	private static DelegateBridge __Hotfix0_TryGetMaterialOrNewFromShader; // 0x8
	private static DelegateBridge __Hotfix0_StartExclusiveTween; // 0x10
	private static DelegateBridge __Hotfix1_StartExclusiveTween; // 0x18
	private static DelegateBridge __Hotfix0_FinishExclusiveTween; // 0x20
	private static DelegateBridge __Hotfix1_FinishExclusiveTween; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1c51580 VA: 0x7594269580
	public Material GetMaterial(Material source, String instanceKey) { }
	// RVA: 0x1c51720 VA: 0x7594269720
	public Boolean TryGetMaterialOrNewFromShader(Shader shader, MaterialKey key, out Material result) { }
	// RVA: 0x1c51880 VA: 0x7594269880
	public Tween StartExclusiveTween(Func`2 factory, Material source, String instanceKey) { }
	// RVA: 0x1c51930 VA: 0x7594269930
	public Tween StartExclusiveTween(Func`2 factory, Material material) { }
	// RVA: 0x1c51a78 VA: 0x7594269a78
	public Boolean FinishExclusiveTween(Material source, String instanceKey) { }
	// RVA: 0x1c51b10 VA: 0x7594269b10
	public Boolean FinishExclusiveTween(Material material) { }
	// RVA: 0x1c51c00 VA: 0x7594269c00
	protected override Void OnDestroy() { }
	// RVA: 0x1c51e38 VA: 0x7594269e38
	public Void .ctor() { }
}
```