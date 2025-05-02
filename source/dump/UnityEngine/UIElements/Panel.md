# Panel

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement m_RootContainer`

- `VisualTreeUpdater m_VisualTreeUpdater`

- `IStylePropertyAnimationSystem m_StylePropertyAnimationSystem`

- `String m_PanelName`

- `UInt32 m_Version`

- `UInt32 m_RepaintVersion`

- `UInt32 m_HierarchyVersion`

- `ProfilerMarker m_MarkerBeforeUpdate`

- `ProfilerMarker m_MarkerUpdate`

- `ProfilerMarker m_MarkerLayout`

- `ProfilerMarker m_MarkerBindings`

- `ProfilerMarker m_MarkerAnimations`

- `EventDispatcher <dispatcher>k__BackingField`

- `TimerEventScheduler m_Scheduler`

- `ScriptableObject <ownerObject>k__BackingField`

- `ContextType <contextType>k__BackingField`

- `SavePersistentViewData <saveViewData>k__BackingField`

- `GetViewDataDictionary <getViewDataDictionary>k__BackingField`

- `FocusController <focusController>k__BackingField`

- `EventInterests <IMGUIEventInterests>k__BackingField`

- `Int32 <IMGUIContainersCount>k__BackingField`

- `IMGUIContainer <rootIMGUIContainer>k__BackingField`

- `Shader m_StandardShader`

- `AtlasBase m_Atlas`

- `Boolean m_ValidatingLayout`


## Properties

- `TimerEventScheduler timerEventScheduler`


## Methods

- `TimerEventScheduler get_timerEventScheduler()`

- `Void CreateMarkers()`

- `Void UpdateForRepaint()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class Panel : BaseVisualElementPanel
{
	private VisualElement m_RootContainer; // 0xa0
	private VisualTreeUpdater m_VisualTreeUpdater; // 0xa8
	private IStylePropertyAnimationSystem m_StylePropertyAnimationSystem; // 0xb0
	private String m_PanelName; // 0xb8
	private UInt32 m_Version; // 0xc0
	private UInt32 m_RepaintVersion; // 0xc4
	private UInt32 m_HierarchyVersion; // 0xc8
	private ProfilerMarker m_MarkerBeforeUpdate; // 0xd0
	private ProfilerMarker m_MarkerUpdate; // 0xd8
	private ProfilerMarker m_MarkerLayout; // 0xe0
	private ProfilerMarker m_MarkerBindings; // 0xe8
	private ProfilerMarker m_MarkerAnimations; // 0xf0
	private static ProfilerMarker s_MarkerPickAll; // 0x0
	private EventDispatcher <dispatcher>k__BackingField; // 0xf8
	private TimerEventScheduler m_Scheduler; // 0x100
	private ScriptableObject <ownerObject>k__BackingField; // 0x108
	private ContextType <contextType>k__BackingField; // 0x110
	private SavePersistentViewData <saveViewData>k__BackingField; // 0x118
	private GetViewDataDictionary <getViewDataDictionary>k__BackingField; // 0x120
	private FocusController <focusController>k__BackingField; // 0x128
	private EventInterests <IMGUIEventInterests>k__BackingField; // 0x130
	private static LoadResourceFunction <loadResourceFunc>k__BackingField; // 0x8
	private static TimeMsFunction <TimeSinceStartup>k__BackingField; // 0x10
	private Int32 <IMGUIContainersCount>k__BackingField; // 0x134
	private IMGUIContainer <rootIMGUIContainer>k__BackingField; // 0x138
	private Shader m_StandardShader; // 0x140
	private AtlasBase m_Atlas; // 0x148
	private Boolean m_ValidatingLayout; // 0x150
	private static Action`1 beforeAnyRepaint; // 0x18

	public sealed override VisualElement visualTree { get; }
	public sealed override EventDispatcher dispatcher { get; set; }
	public TimerEventScheduler timerEventScheduler { get; }
	internal override IScheduler scheduler { get; }
	internal override IStylePropertyAnimationSystem styleAnimationSystem { get; set; }
	public override ScriptableObject ownerObject { get; set; }
	public override ContextType contextType { get; set; }
	public override SavePersistentViewData saveViewData { get; }
	public override GetViewDataDictionary getViewDataDictionary { get; }
	public sealed override FocusController focusController { get; set; }
	public override EventInterests IMGUIEventInterests { get; set; }
	private static LoadResourceFunction loadResourceFunc { get; }
	internal String name { get; set; }
	private static TimeMsFunction TimeSinceStartup { get; }
	public override Int32 IMGUIContainersCount { get; set; }
	public override IMGUIContainer rootIMGUIContainer { get; }
	internal override UInt32 version { get; }
	internal override UInt32 hierarchyVersion { get; }
	internal override Shader standardShader { get; }
	public override AtlasBase atlas { get; set; }

	// RVA: 0x693f578 VA: 0x7598f57578
	public sealed override VisualElement get_visualTree() { }
	// RVA: 0x693f580 VA: 0x7598f57580
	public sealed override EventDispatcher get_dispatcher() { }
	// RVA: 0x693f588 VA: 0x7598f57588
	public sealed override Void set_dispatcher(EventDispatcher value) { }
	// RVA: 0x693f590 VA: 0x7598f57590
	public TimerEventScheduler get_timerEventScheduler() { }
	// RVA: 0x693f60c VA: 0x7598f5760c
	internal override IScheduler get_scheduler() { }
	// RVA: 0x693f610 VA: 0x7598f57610
	internal override IStylePropertyAnimationSystem get_styleAnimationSystem() { }
	// RVA: 0x693f618 VA: 0x7598f57618
	internal override Void set_styleAnimationSystem(IStylePropertyAnimationSystem value) { }
	// RVA: 0x693f6e0 VA: 0x7598f576e0
	public override ScriptableObject get_ownerObject() { }
	// RVA: 0x693f6e8 VA: 0x7598f576e8
	protected override Void set_ownerObject(ScriptableObject value) { }
	// RVA: 0x693f6f8 VA: 0x7598f576f8
	public override ContextType get_contextType() { }
	// RVA: 0x693f700 VA: 0x7598f57700
	protected override Void set_contextType(ContextType value) { }
	// RVA: 0x693f708 VA: 0x7598f57708
	public override SavePersistentViewData get_saveViewData() { }
	// RVA: 0x693f710 VA: 0x7598f57710
	public override GetViewDataDictionary get_getViewDataDictionary() { }
	// RVA: 0x693f718 VA: 0x7598f57718
	public sealed override FocusController get_focusController() { }
	// RVA: 0x693f720 VA: 0x7598f57720
	public sealed override Void set_focusController(FocusController value) { }
	// RVA: 0x693f730 VA: 0x7598f57730
	public override EventInterests get_IMGUIEventInterests() { }
	// RVA: 0x693f740 VA: 0x7598f57740
	public override Void set_IMGUIEventInterests(EventInterests value) { }
	// RVA: 0x693f750 VA: 0x7598f57750
	private static LoadResourceFunction get_loadResourceFunc() { }
	// RVA: 0x693f7a8 VA: 0x7598f577a8
	internal static Object LoadResource(String pathName, Type type, Single dpiScaling) { }
	// RVA: 0x69328dc VA: 0x7598f4a8dc
	internal Void Focus() { }
	// RVA: 0x69328b4 VA: 0x7598f4a8b4
	internal Void Blur() { }
	// RVA: 0x693f8d4 VA: 0x7598f578d4
	internal String get_name() { }
	// RVA: 0x693f8dc VA: 0x7598f578dc
	internal Void set_name(String value) { }
	// RVA: 0x693f8f8 VA: 0x7598f578f8
	private Void CreateMarkers() { }
	// RVA: 0x693fb44 VA: 0x7598f57b44
	private static TimeMsFunction get_TimeSinceStartup() { }
	// RVA: 0x693fb9c VA: 0x7598f57b9c
	public override Int32 get_IMGUIContainersCount() { }
	// RVA: 0x693fba4 VA: 0x7598f57ba4
	public override Void set_IMGUIContainersCount(Int32 value) { }
	// RVA: 0x693fbac VA: 0x7598f57bac
	public override IMGUIContainer get_rootIMGUIContainer() { }
	// RVA: 0x693fbb4 VA: 0x7598f57bb4
	internal override UInt32 get_version() { }
	// RVA: 0x693fbbc VA: 0x7598f57bbc
	internal override UInt32 get_hierarchyVersion() { }
	// RVA: 0x693fbc4 VA: 0x7598f57bc4
	internal override Shader get_standardShader() { }
	// RVA: 0x693fbcc VA: 0x7598f57bcc
	public override AtlasBase get_atlas() { }
	// RVA: 0x693fbd4 VA: 0x7598f57bd4
	public override Void set_atlas(AtlasBase value) { }
	// RVA: 0x693fc5c VA: 0x7598f57c5c
	public Void .ctor(ScriptableObject ownerObject, ContextType contextType, EventDispatcher dispatcher) { }
	// RVA: 0x6940014 VA: 0x7598f58014
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x694007c VA: 0x7598f5807c
	public static Int64 TimeSinceStartupMs() { }
	// RVA: 0x6940158 VA: 0x7598f58158
	internal static Int64 DefaultTimeSinceStartupMs() { }
	// RVA: 0x6940190 VA: 0x7598f58190
	private static VisualElement PickAll(VisualElement root, Vector2 point, List`1 picked) { }
	// RVA: 0x6940244 VA: 0x7598f58244
	private static VisualElement PerformPick(VisualElement root, Vector2 point, List`1 picked) { }
	// RVA: 0x6940534 VA: 0x7598f58534
	public override VisualElement PickAll(Vector2 point, List`1 picked) { }
	// RVA: 0x694060c VA: 0x7598f5860c
	public override VisualElement Pick(Vector2 point) { }
	// RVA: 0x6940878 VA: 0x7598f58878
	public override Void ValidateLayout() { }
	// RVA: 0x69408f4 VA: 0x7598f588f4
	public override Void UpdateAnimations() { }
	// RVA: 0x6940930 VA: 0x7598f58930
	public override Void UpdateBindings() { }
	// RVA: 0x694096c VA: 0x7598f5896c
	public override Void ApplyStyles() { }
	// RVA: 0x694098c VA: 0x7598f5898c
	private Void UpdateForRepaint() { }
	// RVA: 0x6940a00 VA: 0x7598f58a00
	public override Void Repaint(Event e) { }
	// RVA: 0x6940d8c VA: 0x7598f58d8c
	internal override Void OnVersionChanged(VisualElement ve, VersionChangeType versionChangeType) { }
	// RVA: 0x6940dd8 VA: 0x7598f58dd8
	internal override IVisualTreeUpdater GetUpdater(VisualTreeUpdatePhase phase) { }
	// RVA: 0x6940df4 VA: 0x7598f58df4
	private static Void .cctor() { }
	// RVA: 0x6940780 VA: 0x7598f58780
	internal static Vector2Int <Pick>g__PixelOf|99_0(Vector2 p) { }
}
```