# UIRawImageMatAnimWrapper

**Namespace:** `Torappu.UI`


## Fields

- `Int32 count`

- `Int32 get`

- `Material m_mat`

- `Material m_cacheBaseMaterial`


## Methods

- `Material GetModifiedMaterial(Material)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UIRawImageMatAnimWrapper : UIAbstractMatAnimWrapper, IMaterialModifier
{
	private Int32 count; // 0x364
	private Int32 get; // 0x368
	private Material m_mat; // 0x370
	private Material m_cacheBaseMaterial; // 0x378
	private static __XLua_Gen_Delegate96 __Hotfix0_GetMaterial; // 0x0
	private static __XLua_Gen_Delegate97 __Hotfix0_GetModifiedMaterial; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_CleanMaterial; // 0x10
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x18


	// RVA: 0x677fb94 VA: 0x7598d97b94
	public override Material GetMaterial() { }
	// RVA: 0x677fc48 VA: 0x7598d97c48
	public Material GetModifiedMaterial(Material baseMaterial) { }
	// RVA: 0x677fe00 VA: 0x7598d97e00
	public override Void CleanMaterial() { }
	// RVA: 0x677fee4 VA: 0x7598d97ee4
	public Void .ctor() { }
}
```