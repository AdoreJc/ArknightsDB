# IMGUIContainer

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Action m_OnGUIHandler`

- `ObjectGUIState m_ObjectGUIState`

- `Rect <lastWorldClip>k__BackingField`

- `Boolean m_CullingEnabled`

- `Boolean m_IsFocusDelegated`

- `Boolean m_RefreshCachedLayout`

- `LayoutCache m_Cache`

- `Rect m_CachedClippingRect`

- `Matrix4x4 m_CachedTransform`

- `ContextType <contextType>k__BackingField`

- `Boolean lostFocus`

- `Boolean receivedFocus`

- `FocusChangeDirection focusChangeDirection`

- `Boolean hasFocusableControls`

- `Int32 newKeyboardFocusControlID`

- `Boolean <focusOnlyIfHasFocusableControls>k__BackingField`

- `GUIGlobals m_GUIGlobals`


## Properties

- `Action onGUIHandler`

- `Boolean cullingEnabled`

- `LayoutCache cache`

- `Single layoutMeasuredWidth`

- `Single layoutMeasuredHeight`

- `ContextType contextType`


## Methods

- `Action get_onGUIHandler()`

- `Void set_onGUIHandler(Action)`

- `Boolean get_cullingEnabled()`

- `LayoutCache get_cache()`

- `Single get_layoutMeasuredWidth()`

- `Single get_layoutMeasuredHeight()`

- `ContextType get_contextType()`

- `Void set_contextType(ContextType)`

- `Void OnGenerateVisualContent(MeshGenerationContext)`

- `Void SaveGlobals()`

- `Void RestoreGlobals()`

- `Void DoOnGUI(Event, Matrix4x4, Rect, Boolean, Rect, Action, Boolean)`

- `Void MarkDirtyLayout()`

- `Void DoIMGUIRepaint()`

- `Boolean SendEventToIMGUIRaw(EventBase, Boolean, Boolean)`

- `Boolean VerifyBounds(EventBase)`

- `Boolean IsContainerCapturingTheMouse()`

- `Boolean IsLocalEvent(EventBase)`

- `Boolean IsEventInsideLocalWindow(EventBase)`

- `Boolean HandleIMGUIEvent(Event, Boolean)`

- `Boolean HandleIMGUIEvent(Event, Matrix4x4, Rect, Action, Boolean)`

- `Void SetFoldoutDepthClass()`

- `Rect GetCurrentClipRect()`

- `Void Dispose()`

- `Void <DoOnGUI>b__57_0()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class IMGUIContainer : VisualElement, IDisposable
{
	private Action m_OnGUIHandler; // 0x3b0
	private ObjectGUIState m_ObjectGUIState; // 0x3b8
	internal Boolean useOwnerObjectGUIState; // 0x3c0
	private Rect <lastWorldClip>k__BackingField; // 0x3c4
	private Boolean m_CullingEnabled; // 0x3d4
	private Boolean m_IsFocusDelegated; // 0x3d5
	private Boolean m_RefreshCachedLayout; // 0x3d6
	private LayoutCache m_Cache; // 0x3d8
	private Rect m_CachedClippingRect; // 0x3e0
	private Matrix4x4 m_CachedTransform; // 0x3f0
	private ContextType <contextType>k__BackingField; // 0x430
	private Boolean lostFocus; // 0x434
	private Boolean receivedFocus; // 0x435
	private FocusChangeDirection focusChangeDirection; // 0x438
	private Boolean hasFocusableControls; // 0x440
	private Int32 newKeyboardFocusControlID; // 0x444
	private Boolean <focusOnlyIfHasFocusableControls>k__BackingField; // 0x448
	public static readonly String ussClassName; // 0x0
	internal static readonly String ussFoldoutChildDepthClassName; // 0x8
	internal static readonly List`1 ussFoldoutChildDepthClassNames; // 0x10
	internal static IMGUIContainer current; // 0x18
	private GUIGlobals m_GUIGlobals; // 0x44c
	private static readonly ProfilerMarker k_OnGUIMarker; // 0x20
	private static readonly ProfilerMarker k_ImmediateCallbackMarker; // 0x28
	private static Event s_DefaultMeasureEvent; // 0x30
	private static Event s_MeasureEvent; // 0x38
	private static Event s_CurrentEvent; // 0x40

	public Action onGUIHandler { get; set; }
	internal ObjectGUIState guiState { get; }
	internal Rect lastWorldClip { get; set; }
	public Boolean cullingEnabled { get; }
	private LayoutCache cache { get; }
	private Single layoutMeasuredWidth { get; }
	private Single layoutMeasuredHeight { get; }
	public ContextType contextType { get; set; }
	internal Boolean focusOnlyIfHasFocusableControls { get; }
	public override Boolean canGrabFocus { get; }

	// RVA: 0x69395e4 VA: 0x7598f515e4
	public Action get_onGUIHandler() { }
	// RVA: 0x69395ec VA: 0x7598f515ec
	public Void set_onGUIHandler(Action value) { }
	// RVA: 0x6939650 VA: 0x7598f51650
	internal ObjectGUIState get_guiState() { }
	// RVA: 0x6939704 VA: 0x7598f51704
	internal Rect get_lastWorldClip() { }
	// RVA: 0x6939718 VA: 0x7598f51718
	internal Void set_lastWorldClip(Rect value) { }
	// RVA: 0x693972c VA: 0x7598f5172c
	public Boolean get_cullingEnabled() { }
	// RVA: 0x6939734 VA: 0x7598f51734
	private LayoutCache get_cache() { }
	// RVA: 0x69397b4 VA: 0x7598f517b4
	private Single get_layoutMeasuredWidth() { }
	// RVA: 0x69397dc VA: 0x7598f517dc
	private Single get_layoutMeasuredHeight() { }
	// RVA: 0x6939804 VA: 0x7598f51804
	public ContextType get_contextType() { }
	// RVA: 0x693980c VA: 0x7598f5180c
	public Void set_contextType(ContextType value) { }
	// RVA: 0x6939814 VA: 0x7598f51814
	internal Boolean get_focusOnlyIfHasFocusableControls() { }
	// RVA: 0x693981c VA: 0x7598f5181c
	public override Boolean get_canGrabFocus() { }
	// RVA: 0x693983c VA: 0x7598f5183c
	private static Void .cctor() { }
	// RVA: 0x6939c4c VA: 0x7598f51c4c
	public Void .ctor() { }
	// RVA: 0x6939c54 VA: 0x7598f51c54
	public Void .ctor(Action onGUIHandler) { }
	// RVA: 0x6939eac VA: 0x7598f51eac
	private Void OnGenerateVisualContent(MeshGenerationContext mgc) { }
	// RVA: 0x6939fd8 VA: 0x7598f51fd8
	private Void SaveGlobals() { }
	// RVA: 0x693a0e8 VA: 0x7598f520e8
	private Void RestoreGlobals() { }
	// RVA: 0x693a200 VA: 0x7598f52200
	private Void DoOnGUI(Event evt, Matrix4x4 parentTransform, Rect clippingRect, Boolean isComputingLayout, Rect layoutSize, Action onGUIHandler, Boolean canAffectFocus) { }
	// RVA: 0x693af58 VA: 0x7598f52f58
	public Void MarkDirtyLayout() { }
	// RVA: 0x693af6c VA: 0x7598f52f6c
	public override Void HandleEvent(EventBase evt) { }
	// RVA: 0x693b298 VA: 0x7598f53298
	private Void DoIMGUIRepaint() { }
	// RVA: 0x693affc VA: 0x7598f52ffc
	internal Boolean SendEventToIMGUI(EventBase evt, Boolean canAffectFocus, Boolean verifyBounds) { }
	// RVA: 0x693b920 VA: 0x7598f53920
	private Boolean SendEventToIMGUIRaw(EventBase evt, Boolean canAffectFocus, Boolean verifyBounds) { }
	// RVA: 0x693ba20 VA: 0x7598f53a20
	private Boolean VerifyBounds(EventBase evt) { }
	// RVA: 0x693bac0 VA: 0x7598f53ac0
	private Boolean IsContainerCapturingTheMouse() { }
	// RVA: 0x693bbd0 VA: 0x7598f53bd0
	private Boolean IsLocalEvent(EventBase evt) { }
	// RVA: 0x693bdd4 VA: 0x7598f53dd4
	private Boolean IsEventInsideLocalWindow(EventBase evt) { }
	// RVA: 0x693bf54 VA: 0x7598f53f54
	private static Boolean IsDockAreaMouseUp(EventBase evt) { }
	// RVA: 0x693bab0 VA: 0x7598f53ab0
	private Boolean HandleIMGUIEvent(Event e, Boolean canAffectFocus) { }
	// RVA: 0x693c114 VA: 0x7598f54114
	internal Boolean HandleIMGUIEvent(Event e, Action onGUIHandler, Boolean canAffectFocus) { }
	// RVA: 0x693b628 VA: 0x7598f53628
	private Boolean HandleIMGUIEvent(Event e, Matrix4x4 worldTransform, Rect clippingRect, Action onGUIHandler, Boolean canAffectFocus) { }
	// RVA: 0x693c3a0 VA: 0x7598f543a0
	protected override Void ExecuteDefaultAction(EventBase evt) { }
	// RVA: 0x693c690 VA: 0x7598f54690
	private Void SetFoldoutDepthClass() { }
	// RVA: 0x693c7fc VA: 0x7598f547fc
	protected internal override Vector2 DoMeasure(Single desiredWidth, MeasureMode widthMode, Single desiredHeight, MeasureMode heightMode) { }
	// RVA: 0x693c0a8 VA: 0x7598f540a8
	private Rect GetCurrentClipRect() { }
	// RVA: 0x693c1e0 VA: 0x7598f541e0
	private static Void GetCurrentTransformAndClip(IMGUIContainer container, Event evt, out Matrix4x4 transform, out Rect clipRect) { }
	// RVA: 0x693ca54 VA: 0x7598f54a54
	public Void Dispose() { }
	// RVA: 0x693cac4 VA: 0x7598f54ac4
	protected virtual Void Dispose(Boolean disposeManaged) { }
	// RVA: 0x693cadc VA: 0x7598f54adc
	private Void <DoOnGUI>b__57_0() { }
}
```