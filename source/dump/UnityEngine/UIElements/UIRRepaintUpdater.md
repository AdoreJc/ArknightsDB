# UIRRepaintUpdater

**Namespace:** `UnityEngine.UIElements`


## Fields

- `BaseVisualElementPanel attachedPanel`

- `Boolean <drawStats>k__BackingField`

- `Boolean <breakBatches>k__BackingField`

- `Boolean <disposed>k__BackingField`


## Properties

- `Boolean drawStats`

- `Boolean breakBatches`

- `Boolean disposed`


## Methods

- `Boolean get_drawStats()`

- `Boolean get_breakBatches()`

- `Void OnPanelChanged(BaseVisualElementPanel)`

- `Void AttachToPanel()`

- `Void DetachFromPanel()`

- `Void InitRenderChain()`

- `Void OnPanelAtlasChanged()`

- `Void OnPanelHierarchyChanged(VisualElement, HierarchyChangeType)`

- `Void OnPanelStandardShaderChanged()`

- `Void OnPanelStandardWorldSpaceShaderChanged()`

- `Void ResetAllElementsDataRecursive(VisualElement)`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class UIRRepaintUpdater : BaseVisualTreeUpdater
{
	private BaseVisualElementPanel attachedPanel; // 0x20
	internal RenderChain renderChain; // 0x28
	private static readonly String s_Description; // 0x0
	private static readonly ProfilerMarker s_ProfilerMarker; // 0x8
	private Boolean <drawStats>k__BackingField; // 0x30
	private Boolean <breakBatches>k__BackingField; // 0x31
	private Boolean <disposed>k__BackingField; // 0x32

	public override ProfilerMarker profilerMarker { get; }
	public Boolean drawStats { get; }
	public Boolean breakBatches { get; }
	protected Boolean disposed { get; set; }

	// RVA: 0x6a09db4 VA: 0x7599021db4
	public Void .ctor() { }
	// RVA: 0x6a09e44 VA: 0x7599021e44
	public override ProfilerMarker get_profilerMarker() { }
	// RVA: 0x6a09e9c VA: 0x7599021e9c
	public Boolean get_drawStats() { }
	// RVA: 0x6a09ea4 VA: 0x7599021ea4
	public Boolean get_breakBatches() { }
	// RVA: 0x6a09eac VA: 0x7599021eac
	public override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x6a09fa4 VA: 0x7599021fa4
	public override Void Update() { }
	// RVA: 0x6a0a128 VA: 0x7599022128
	protected virtual RenderChain CreateRenderChain() { }
	// RVA: 0x6a0a1a0 VA: 0x75990221a0
	private static Void .cctor() { }
	// RVA: 0x6a0a2bc VA: 0x75990222bc
	private static Void OnGraphicsResourcesRecreate(Boolean recreate) { }
	// RVA: 0x6a0a4f8 VA: 0x75990224f8
	private Void OnPanelChanged(BaseVisualElementPanel obj) { }
	// RVA: 0x6a0a6d0 VA: 0x75990226d0
	private Void AttachToPanel() { }
	// RVA: 0x6a0a510 VA: 0x7599022510
	private Void DetachFromPanel() { }
	// RVA: 0x6a0a060 VA: 0x7599022060
	private Void InitRenderChain() { }
	// RVA: 0x6a0a48c VA: 0x759902248c
	internal Void DestroyRenderChain() { }
	// RVA: 0x6a0acac VA: 0x7599022cac
	private Void OnPanelAtlasChanged() { }
	// RVA: 0x6a0acb0 VA: 0x7599022cb0
	private Void OnPanelHierarchyChanged(VisualElement ve, HierarchyChangeType changeType) { }
	// RVA: 0x6a0a8d4 VA: 0x75990228d4
	private Void OnPanelStandardShaderChanged() { }
	// RVA: 0x6a0aa78 VA: 0x7599022a78
	private Void OnPanelStandardWorldSpaceShaderChanged() { }
	// RVA: 0x6a0ac1c VA: 0x7599022c1c
	private Void ResetAllElementsDataRecursive(VisualElement ve) { }
	// RVA: 0x6a0ace8 VA: 0x7599022ce8
	protected Boolean get_disposed() { }
	// RVA: 0x6a0acf0 VA: 0x7599022cf0
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6a0acfc VA: 0x7599022cfc
	protected override Void Dispose(Boolean disposing) { }
}
```