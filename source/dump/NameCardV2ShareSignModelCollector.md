# NameCardV2ShareSignModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareSignStartLayoutElement m_closure`

- `CrossAppShareImageModel <iconModel>k__BackingField`

- `CrossAppShareTextModel <signTextModel>k__BackingField`

- `CrossAppShareImageModel <bgRectModel>k__BackingField`


## Properties

- `CrossAppShareImageModel iconModel`

- `CrossAppShareTextModel signTextModel`

- `CrossAppShareImageModel bgRectModel`


## Methods

- `Void InitCollector(NameCardV2ShareSignStartLayoutElement)`

- `CrossAppShareImageModel get_iconModel()`

- `Void set_iconModel(CrossAppShareImageModel)`

- `CrossAppShareTextModel get_signTextModel()`

- `Void set_signTextModel(CrossAppShareTextModel)`

- `CrossAppShareImageModel get_bgRectModel()`

- `Void set_bgRectModel(CrossAppShareImageModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardV2ShareSignModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareSignStartLayoutElement m_closure; // 0x28
	private CrossAppShareImageModel <iconModel>k__BackingField; // 0x30
	private CrossAppShareTextModel <signTextModel>k__BackingField; // 0x38
	private CrossAppShareImageModel <bgRectModel>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_CollectModel; // 0x0
	private static DelegateBridge __Hotfix0_InitCollector; // 0x8
	private static DelegateBridge __Hotfix0_get_iconModel; // 0x10
	private static DelegateBridge __Hotfix0_set_iconModel; // 0x18
	private static DelegateBridge __Hotfix0_get_signTextModel; // 0x20
	private static DelegateBridge __Hotfix0_set_signTextModel; // 0x28
	private static DelegateBridge __Hotfix0_get_bgRectModel; // 0x30
	private static DelegateBridge __Hotfix0_set_bgRectModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public CrossAppShareImageModel iconModel { get; set; }
	public CrossAppShareTextModel signTextModel { get; set; }
	public CrossAppShareImageModel bgRectModel { get; set; }

	// RVA: 0x28d9eec VA: 0x7594ef1eec
	public override Void CollectModel() { }
	// RVA: 0x28d9df8 VA: 0x7594ef1df8
	public Void InitCollector(NameCardV2ShareSignStartLayoutElement closure) { }
	// RVA: 0x28d9b30 VA: 0x7594ef1b30
	public CrossAppShareImageModel get_iconModel() { }
	// RVA: 0x28da0d0 VA: 0x7594ef20d0
	private Void set_iconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d9b98 VA: 0x7594ef1b98
	public CrossAppShareTextModel get_signTextModel() { }
	// RVA: 0x28da1d8 VA: 0x7594ef21d8
	private Void set_signTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d9c00 VA: 0x7594ef1c00
	public CrossAppShareImageModel get_bgRectModel() { }
	// RVA: 0x28da154 VA: 0x7594ef2154
	private Void set_bgRectModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d9d88 VA: 0x7594ef1d88
	public Void .ctor() { }
}
```