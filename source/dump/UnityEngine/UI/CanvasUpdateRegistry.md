# CanvasUpdateRegistry

**Namespace:** `UnityEngine.UI`


## Fields

- `Boolean m_PerformingLayoutUpdate`

- `Boolean m_PerformingGraphicUpdate`


## Methods

- `Boolean ObjectValidForUpdate(ICanvasElement)`

- `Void CleanInvalidItems()`

- `Void PerformUpdate()`

- `Boolean InternalRegisterCanvasElementForLayoutRebuild(ICanvasElement)`

- `Boolean InternalRegisterCanvasElementForGraphicRebuild(ICanvasElement)`

- `Void InternalUnRegisterCanvasElementForLayoutRebuild(ICanvasElement)`

- `Void InternalUnRegisterCanvasElementForGraphicRebuild(ICanvasElement)`

- `Void InternalDisableCanvasElementForLayoutRebuild(ICanvasElement)`

- `Void InternalDisableCanvasElementForGraphicRebuild(ICanvasElement)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class CanvasUpdateRegistry
{
	private static CanvasUpdateRegistry s_Instance; // 0x0
	private Boolean m_PerformingLayoutUpdate; // 0x10
	private Boolean m_PerformingGraphicUpdate; // 0x11
	private String[] m_CanvasUpdateProfilerStrings; // 0x18
	private const String m_CullingUpdateProfilerString; // 0x0
	private readonly IndexedSet`1 m_LayoutRebuildQueue; // 0x20
	private readonly IndexedSet`1 m_GraphicRebuildQueue; // 0x28
	private static readonly Comparison`1 s_SortLayoutFunction; // 0x8

	public static CanvasUpdateRegistry instance { get; }

	// RVA: 0x6912ef0 VA: 0x7598f2aef0
	protected Void .ctor() { }
	// RVA: 0x691320c VA: 0x7598f2b20c
	public static CanvasUpdateRegistry get_instance() { }
	// RVA: 0x69132c4 VA: 0x7598f2b2c4
	private Boolean ObjectValidForUpdate(ICanvasElement element) { }
	// RVA: 0x6913394 VA: 0x7598f2b394
	private Void CleanInvalidItems() { }
	// RVA: 0x6913678 VA: 0x7598f2b678
	private Void PerformUpdate() { }
	// RVA: 0x6913e50 VA: 0x7598f2be50
	private static Int32 ParentCount(Transform child) { }
	// RVA: 0x6913f10 VA: 0x7598f2bf10
	private static Int32 SortLayoutList(ICanvasElement x, ICanvasElement y) { }
	// RVA: 0x6914060 VA: 0x7598f2c060
	public static Void RegisterCanvasElementForLayoutRebuild(ICanvasElement element) { }
	// RVA: 0x6914158 VA: 0x7598f2c158
	public static Boolean TryRegisterCanvasElementForLayoutRebuild(ICanvasElement element) { }
	// RVA: 0x69140c0 VA: 0x7598f2c0c0
	private Boolean InternalRegisterCanvasElementForLayoutRebuild(ICanvasElement element) { }
	// RVA: 0x69141b8 VA: 0x7598f2c1b8
	public static Void RegisterCanvasElementForGraphicRebuild(ICanvasElement element) { }
	// RVA: 0x69142e8 VA: 0x7598f2c2e8
	public static Boolean TryRegisterCanvasElementForGraphicRebuild(ICanvasElement element) { }
	// RVA: 0x6914218 VA: 0x7598f2c218
	private Boolean InternalRegisterCanvasElementForGraphicRebuild(ICanvasElement element) { }
	// RVA: 0x6914348 VA: 0x7598f2c348
	public static Void UnRegisterCanvasElementForRebuild(ICanvasElement element) { }
	// RVA: 0x6914680 VA: 0x7598f2c680
	public static Void DisableCanvasElementForRebuild(ICanvasElement element) { }
	// RVA: 0x69143b8 VA: 0x7598f2c3b8
	private Void InternalUnRegisterCanvasElementForLayoutRebuild(ICanvasElement element) { }
	// RVA: 0x691451c VA: 0x7598f2c51c
	private Void InternalUnRegisterCanvasElementForGraphicRebuild(ICanvasElement element) { }
	// RVA: 0x69146f0 VA: 0x7598f2c6f0
	private Void InternalDisableCanvasElementForLayoutRebuild(ICanvasElement element) { }
	// RVA: 0x6914854 VA: 0x7598f2c854
	private Void InternalDisableCanvasElementForGraphicRebuild(ICanvasElement element) { }
	// RVA: 0x69149b8 VA: 0x7598f2c9b8
	public static Boolean IsRebuildingLayout() { }
	// RVA: 0x6914a14 VA: 0x7598f2ca14
	public static Boolean IsRebuildingGraphics() { }
	// RVA: 0x6914a70 VA: 0x7598f2ca70
	private static Void .cctor() { }
}
```