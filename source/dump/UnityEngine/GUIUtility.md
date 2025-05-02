# GUIUtility

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
public class GUIUtility
{
	internal static Int32 s_ControlCount; // 0x0
	internal static Int32 s_SkinMode; // 0x4
	internal static Int32 s_OriginalID; // 0x8
	internal static Action takeCapture; // 0x10
	internal static Action releaseCapture; // 0x18
	internal static Func`3 processEvent; // 0x20
	internal static Action cleanupRoots; // 0x28
	internal static Func`2 endContainerGUIFromException; // 0x30
	internal static Action guiChanged; // 0x38
	private static Boolean <guiIsExiting>k__BackingField; // 0x40
	internal static Func`1 s_HasCurrentWindowKeyFocusFunc; // 0x48

	internal static Single pixelsPerPoint { get; }
	internal static Int32 guiDepth { get; }
	internal static Boolean mouseUsed { set; }
	internal static Boolean textFieldInput { get; set; }
	public static String systemCopyBuffer { get; set; }
	internal static String compositionString { get; }
	internal static IMECompositionMode imeCompositionMode { set; }
	internal static Vector2 compositionCursorPos { set; }
	internal static Boolean guiIsExiting { set; }
	public static Int32 hotControl { get; set; }
	public static Int32 keyboardControl { get; set; }

	// RVA: 0x68c2e18 VA: 0x7598edae18
	internal static Single get_pixelsPerPoint() { }
	// RVA: 0x68c2e40 VA: 0x7598edae40
	internal static Int32 get_guiDepth() { }
	// RVA: 0x68c2e68 VA: 0x7598edae68
	internal static Void set_mouseUsed(Boolean value) { }
	// RVA: 0x68c2ea4 VA: 0x7598edaea4
	internal static Boolean get_textFieldInput() { }
	// RVA: 0x68c2ecc VA: 0x7598edaecc
	internal static Void set_textFieldInput(Boolean value) { }
	// RVA: 0x68c2f08 VA: 0x7598edaf08
	public static String get_systemCopyBuffer() { }
	// RVA: 0x68c2f30 VA: 0x7598edaf30
	public static Void set_systemCopyBuffer(String value) { }
	// RVA: 0x68c2f6c VA: 0x7598edaf6c
	private static Int32 Internal_GetControlID(Int32 hint, FocusType focusType, Rect rect) { }
	// RVA: 0x68c301c VA: 0x7598edb01c
	public static Int32 GetControlID(Int32 hint, FocusType focusType, Rect rect) { }
	// RVA: 0x68c30b4 VA: 0x7598edb0b4
	internal static Void BeginContainerFromOwner(ScriptableObject owner) { }
	// RVA: 0x68c30f0 VA: 0x7598edb0f0
	internal static Void BeginContainer(ObjectGUIState objectGUIState) { }
	// RVA: 0x68c312c VA: 0x7598edb12c
	internal static Void Internal_EndContainer() { }
	// RVA: 0x68c3154 VA: 0x7598edb154
	internal static Int32 CheckForTabEvent(Event evt) { }
	// RVA: 0x68c3190 VA: 0x7598edb190
	internal static Void SetKeyboardControlToFirstControlId() { }
	// RVA: 0x68c31b8 VA: 0x7598edb1b8
	internal static Void SetKeyboardControlToLastControlId() { }
	// RVA: 0x68c31e0 VA: 0x7598edb1e0
	internal static Boolean HasFocusableControls() { }
	// RVA: 0x68c3208 VA: 0x7598edb208
	internal static Boolean OwnsId(Int32 id) { }
	// RVA: 0x68c3244 VA: 0x7598edb244
	public static Rect AlignRectToDevice(Rect rect, out Int32 widthInPixels, out Int32 heightInPixels) { }
	// RVA: 0x68c330c VA: 0x7598edb30c
	internal static String get_compositionString() { }
	// RVA: 0x68c3334 VA: 0x7598edb334
	internal static Void set_imeCompositionMode(IMECompositionMode value) { }
	// RVA: 0x68c3370 VA: 0x7598edb370
	internal static Void set_compositionCursorPos(Vector2 value) { }
	// RVA: 0x68c33ec VA: 0x7598edb3ec
	private static Int32 Internal_GetHotControl() { }
	// RVA: 0x68c3414 VA: 0x7598edb414
	private static Int32 Internal_GetKeyboardControl() { }
	// RVA: 0x68c343c VA: 0x7598edb43c
	private static Void Internal_SetHotControl(Int32 value) { }
	// RVA: 0x68c3478 VA: 0x7598edb478
	private static Void Internal_SetKeyboardControl(Int32 value) { }
	// RVA: 0x68c34b4 VA: 0x7598edb4b4
	private static Object Internal_GetDefaultSkin(Int32 skinMode) { }
	// RVA: 0x68c34f0 VA: 0x7598edb4f0
	private static Void Internal_ExitGUI() { }
	// RVA: 0x68c3518 VA: 0x7598edb518
	private static Void MarkGUIChanged() { }
	// RVA: 0x68c357c VA: 0x7598edb57c
	public static Int32 GetControlID(FocusType focus) { }
	// RVA: 0x68c35b4 VA: 0x7598edb5b4
	public static Int32 GetControlID(FocusType focus, Rect position) { }
	// RVA: 0x68c3588 VA: 0x7598edb588
	public static Int32 GetControlID(Int32 hint, FocusType focus) { }
	// RVA: 0x68c35c0 VA: 0x7598edb5c0
	public static Object GetStateObject(Type t, Int32 controlID) { }
	// RVA: 0x68c3628 VA: 0x7598edb628
	internal static Void set_guiIsExiting(Boolean value) { }
	// RVA: 0x68c3674 VA: 0x7598edb674
	public static Int32 get_hotControl() { }
	// RVA: 0x68c369c VA: 0x7598edb69c
	public static Void set_hotControl(Int32 value) { }
	// RVA: 0x68c36d8 VA: 0x7598edb6d8
	internal static Void TakeCapture() { }
	// RVA: 0x68c373c VA: 0x7598edb73c
	internal static Void RemoveCapture() { }
	// RVA: 0x68c37a0 VA: 0x7598edb7a0
	public static Int32 get_keyboardControl() { }
	// RVA: 0x68c37c8 VA: 0x7598edb7c8
	public static Void set_keyboardControl(Int32 value) { }
	// RVA: 0x68c3804 VA: 0x7598edb804
	internal static Boolean HasKeyFocus(Int32 controlID) { }
	// RVA: 0x68c38a4 VA: 0x7598edb8a4
	public static Void ExitGUI() { }
	// RVA: 0x68c3974 VA: 0x7598edb974
	internal static GUISkin GetDefaultSkin() { }
	// RVA: 0x68c3a0c VA: 0x7598edba0c
	internal static Void ProcessEvent(Int32 instanceID, IntPtr nativeEventPtr, out Boolean result) { }
	// RVA: 0x68c3a90 VA: 0x7598edba90
	internal static Void EndContainer() { }
	// RVA: 0x68c3ad8 VA: 0x7598edbad8
	internal static Void BeginGUI(Int32 skinMode, Int32 instanceID, Int32 useGUILayout) { }
	// RVA: 0x68c3c60 VA: 0x7598edbc60
	internal static Void DestroyGUI(Int32 instanceID) { }
	// RVA: 0x68c3cbc VA: 0x7598edbcbc
	internal static Void EndGUI(Int32 layoutType) { }
	// RVA: 0x68c3e70 VA: 0x7598edbe70
	internal static Boolean EndGUIFromException(Exception exception) { }
	// RVA: 0x68c3eb4 VA: 0x7598edbeb4
	internal static Boolean EndContainerGUIFromException(Exception exception) { }
	// RVA: 0x68c3b78 VA: 0x7598edbb78
	internal static Void ResetGlobalState() { }
	// RVA: 0x68c3f24 VA: 0x7598edbf24
	internal static Boolean IsExitGUIException(Exception exception) { }
	// RVA: 0x68c3eb0 VA: 0x7598edbeb0
	internal static Boolean ShouldRethrowException(Exception exception) { }
	// RVA: 0x68c3fa8 VA: 0x7598edbfa8
	internal static Void CheckOnGUI() { }
	// RVA: 0x68c402c VA: 0x7598edc02c
	internal static Single RoundToPixelGrid(Single v) { }
	// RVA: 0x68c4098 VA: 0x7598edc098
	public static Void ScaleAroundPivot(Vector2 scale, Vector2 pivotPoint) { }
	// RVA: 0x68c4310 VA: 0x7598edc310
	public static Rect AlignRectToDevice(Rect rect) { }
	// RVA: 0x68c432c VA: 0x7598edc32c
	internal static Boolean HitTest(Rect rect, Vector2 point, Int32 offset) { }
	// RVA: 0x68c43d0 VA: 0x7598edc3d0
	internal static Boolean HitTest(Rect rect, Vector2 point, Boolean isDirectManipulationDevice) { }
	// RVA: 0x68c43d8 VA: 0x7598edc3d8
	internal static Boolean HitTest(Rect rect, Event evt) { }
	// RVA: 0x68c2fc8 VA: 0x7598edafc8
	private static Int32 Internal_GetControlID_Injected(Int32 hint, FocusType focusType, ref Rect rect) { }
	// RVA: 0x68c32b0 VA: 0x7598edb2b0
	private static Void AlignRectToDevice_Injected(ref Rect rect, out Int32 widthInPixels, out Int32 heightInPixels, out Rect ret) { }
	// RVA: 0x68c33b0 VA: 0x7598edb3b0
	private static Void set_compositionCursorPos_Injected(ref Vector2 value) { }
}
```