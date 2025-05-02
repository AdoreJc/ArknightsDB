# UIStencilComponent

**Namespace:** `Torappu.UI`


## Fields

- `Comparison _comp`

- `Operation _opt`

- `StencilChannel _readChannel`

- `StencilChannel _writeChannel`

- `ColorWriteMask _colorMask`

- `Boolean _needCleaner`

- `Status m_status`

- `UIStencilCleaner m_stencilCleaner`

- `IMatChecker m_matChecker`


## Properties

- `StencilChannel readChannel`

- `StencilChannel writeChannel`

- `IMatChecker MatChecker`


## Methods

- `StencilChannel get_readChannel()`

- `Void set_readChannel(StencilChannel)`

- `StencilChannel get_writeChannel()`

- `Void set_writeChannel(StencilChannel)`

- `Material GetModifiedMaterial(Material)`

- `Boolean NeedCleaner()`

- `IMatChecker get_MatChecker()`

- `Void BindMatChecker(IMatChecker)`

- `Void _TryActivateCleaner()`

- `Void _TryDeactivateCleaner()`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnCanvasHierarchyChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIStencilComponent : UIBehaviour, IHotfixable, IMaterialModifier, INeedClean
{
	private Comparison _comp; // 0x18
	private Operation _opt; // 0x1c
	private StencilChannel _readChannel; // 0x20
	private StencilChannel _writeChannel; // 0x24
	private ColorWriteMask _colorMask; // 0x28
	private Boolean _needCleaner; // 0x2c
	private Status m_status; // 0x30
	private UIStencilCleaner m_stencilCleaner; // 0x38
	private IMatChecker m_matChecker; // 0x40
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnCanvasHierarchyChanged; // 0x18
	private static DelegateBridge __Hotfix0_get_readChannel; // 0x20
	private static DelegateBridge __Hotfix0_set_readChannel; // 0x28
	private static DelegateBridge __Hotfix0_get_writeChannel; // 0x30
	private static DelegateBridge __Hotfix0_set_writeChannel; // 0x38
	private static DelegateBridge __Hotfix0_GetModifiedMaterial; // 0x40
	private static DelegateBridge __Hotfix0_NeedCleaner; // 0x48
	private static DelegateBridge __Hotfix0_get_MatChecker; // 0x50
	private static DelegateBridge __Hotfix0_BindMatChecker; // 0x58
	private static DelegateBridge __Hotfix0__TryActivateCleaner; // 0x60
	private static DelegateBridge __Hotfix0__TryDeactivateCleaner; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public StencilChannel readChannel { get; set; }
	public StencilChannel writeChannel { get; set; }
	public IMatChecker MatChecker { get; }

	// RVA: 0x21bde98 VA: 0x75947d5e98
	protected override Void OnEnable() { }
	// RVA: 0x21be038 VA: 0x75947d6038
	protected override Void OnDisable() { }
	// RVA: 0x21be208 VA: 0x75947d6208
	protected override Void OnDestroy() { }
	// RVA: 0x21be2d4 VA: 0x75947d62d4
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x21be37c VA: 0x75947d637c
	public StencilChannel get_readChannel() { }
	// RVA: 0x21be3e4 VA: 0x75947d63e4
	public Void set_readChannel(StencilChannel value) { }
	// RVA: 0x21be4f0 VA: 0x75947d64f0
	public StencilChannel get_writeChannel() { }
	// RVA: 0x21be558 VA: 0x75947d6558
	public Void set_writeChannel(StencilChannel value) { }
	// RVA: 0x21be664 VA: 0x75947d6664
	public Material GetModifiedMaterial(Material baseMaterial) { }
	// RVA: 0x21be9f4 VA: 0x75947d69f4
	public Boolean NeedCleaner() { }
	// RVA: 0x21bea5c VA: 0x75947d6a5c
	public IMatChecker get_MatChecker() { }
	// RVA: 0x21beac4 VA: 0x75947d6ac4
	public Void BindMatChecker(IMatChecker checker) { }
	// RVA: 0x21bdf20 VA: 0x75947d5f20
	private Void _TryActivateCleaner() { }
	// RVA: 0x21be0bc VA: 0x75947d60bc
	private Void _TryDeactivateCleaner() { }
	// RVA: 0x21bebe0 VA: 0x75947d6be0
	public Void .ctor() { }
	// RVA: 0x21beca8 VA: 0x75947d6ca8
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x21becb0 VA: 0x75947d6cb0
	private Void <>xLuaBaseProxy_OnDisable() { }
	// RVA: 0x21becb8 VA: 0x75947d6cb8
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x21becc0 VA: 0x75947d6cc0
	private Void <>xLuaBaseProxy_OnCanvasHierarchyChanged() { }
}
```