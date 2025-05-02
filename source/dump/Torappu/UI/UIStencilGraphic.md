# UIStencilGraphic

**Namespace:** `Torappu.UI`


## Fields

- `Comparison _comp`

- `Operation _opt`

- `StencilChannel _readChannel`

- `StencilChannel _writeChannel`

- `ColorWriteMask _colorMask`

- `Boolean _blockRaycast`

- `Boolean _needCleaner`

- `Material m_maskMaterial`

- `UIStencilCleaner m_stencilCleaner`


## Properties

- `StencilChannel readChannel`

- `StencilChannel writeChannel`


## Methods

- `StencilChannel get_readChannel()`

- `Void set_readChannel(StencilChannel)`

- `StencilChannel get_writeChannel()`

- `Void set_writeChannel(StencilChannel)`

- `Boolean NeedCleaner()`

- `Void _TryActivateCleaner()`

- `Void _TryDeactivateCleaner()`

- `Boolean <>xLuaBaseProxy_get_raycastTarget()`

- `Void <>xLuaBaseProxy_set_raycastTarget(Boolean)`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`

- `Void <>xLuaBaseProxy_OnCanvasHierarchyChanged()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Material <>xLuaBaseProxy_get_materialForRendering()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIStencilGraphic : UIStencilMaskable, INeedClean
{
	private Comparison _comp; // 0xc0
	private Operation _opt; // 0xc4
	private StencilChannel _readChannel; // 0xc8
	private StencilChannel _writeChannel; // 0xcc
	private ColorWriteMask _colorMask; // 0xd0
	private Boolean _blockRaycast; // 0xd4
	private Boolean _needCleaner; // 0xd5
	private Material m_maskMaterial; // 0xd8
	private UIStencilCleaner m_stencilCleaner; // 0xe0
	private static DelegateBridge __Hotfix0_get_raycastTarget; // 0x0
	private static DelegateBridge __Hotfix0_set_raycastTarget; // 0x8
	private static DelegateBridge __Hotfix0_get_readChannel; // 0x10
	private static DelegateBridge __Hotfix0_set_readChannel; // 0x18
	private static DelegateBridge __Hotfix0_get_writeChannel; // 0x20
	private static DelegateBridge __Hotfix0_set_writeChannel; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge __Hotfix0_OnDisable; // 0x38
	private static DelegateBridge __Hotfix0_OnCanvasHierarchyChanged; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0_get_materialForRendering; // 0x50
	private static DelegateBridge __Hotfix0_NeedCleaner; // 0x58
	private static DelegateBridge __Hotfix0__TryActivateCleaner; // 0x60
	private static DelegateBridge __Hotfix0__TryDeactivateCleaner; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override Boolean raycastTarget { get; set; }
	public StencilChannel readChannel { get; set; }
	public StencilChannel writeChannel { get; set; }
	public override Material materialForRendering { get; }

	// RVA: 0x21bf11c VA: 0x75947d711c
	public override Boolean get_raycastTarget() { }
	// RVA: 0x21bf184 VA: 0x75947d7184
	public override Void set_raycastTarget(Boolean value) { }
	// RVA: 0x21bf204 VA: 0x75947d7204
	public StencilChannel get_readChannel() { }
	// RVA: 0x21bf26c VA: 0x75947d726c
	public Void set_readChannel(StencilChannel value) { }
	// RVA: 0x21bf324 VA: 0x75947d7324
	public StencilChannel get_writeChannel() { }
	// RVA: 0x21bf38c VA: 0x75947d738c
	public Void set_writeChannel(StencilChannel value) { }
	// RVA: 0x21bf444 VA: 0x75947d7444
	protected override Void OnEnable() { }
	// RVA: 0x21bf578 VA: 0x75947d7578
	protected override Void OnDisable() { }
	// RVA: 0x21bf6dc VA: 0x75947d76dc
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x21bf784 VA: 0x75947d7784
	protected override Void OnDestroy() { }
	// RVA: 0x21bf878 VA: 0x75947d7878
	public override Material get_materialForRendering() { }
	// RVA: 0x21bf9ec VA: 0x75947d79ec
	public Boolean NeedCleaner() { }
	// RVA: 0x21bf4cc VA: 0x75947d74cc
	private Void _TryActivateCleaner() { }
	// RVA: 0x21bf644 VA: 0x75947d7644
	private Void _TryDeactivateCleaner() { }
	// RVA: 0x21bfa54 VA: 0x75947d7a54
	public Void .ctor() { }
	// RVA: 0x21bfacc VA: 0x75947d7acc
	private Boolean <>xLuaBaseProxy_get_raycastTarget() { }
	// RVA: 0x21bfad4 VA: 0x75947d7ad4
	private Void <>xLuaBaseProxy_set_raycastTarget(Boolean P0) { }
	// RVA: 0x21bfae0 VA: 0x75947d7ae0
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x21bfae8 VA: 0x75947d7ae8
	private Void <>xLuaBaseProxy_OnDisable() { }
	// RVA: 0x21bfaf0 VA: 0x75947d7af0
	private Void <>xLuaBaseProxy_OnCanvasHierarchyChanged() { }
	// RVA: 0x21bfaf8 VA: 0x75947d7af8
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x21bfb00 VA: 0x75947d7b00
	private Material <>xLuaBaseProxy_get_materialForRendering() { }
}
```