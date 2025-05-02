# GUI

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
public class GUI
{
	private static Int32 s_ScrollControlId; // 0x0
	private static Int32 s_HotTextField; // 0x4
	private static readonly Int32 s_BoxHash; // 0x8
	private static readonly Int32 s_ButonHash; // 0xc
	private static readonly Int32 s_RepeatButtonHash; // 0x10
	private static readonly Int32 s_ToggleHash; // 0x14
	private static readonly Int32 s_ButtonGridHash; // 0x18
	private static readonly Int32 s_SliderHash; // 0x1c
	private static readonly Int32 s_BeginGroupHash; // 0x20
	private static readonly Int32 s_ScrollviewHash; // 0x24
	private static Int32 <scrollTroughSide>k__BackingField; // 0x28
	private static DateTime <nextScrollStepTime>k__BackingField; // 0x30
	private static GUISkin s_Skin; // 0x38
	internal static Rect s_ToolTipRect; // 0x40
	private static GenericStack <scrollViewStates>k__BackingField; // 0x50

	public static Color color { get; set; }
	public static Color backgroundColor { get; set; }
	public static Color contentColor { get; set; }
	public static Boolean changed { get; set; }
	public static Boolean enabled { get; set; }
	public static Int32 depth { set; }
	internal static Boolean usePageScrollbars { get; }
	internal static Material blendMaterial { get; }
	internal static Material blitMaterial { get; }
	internal static Material roundedRectMaterial { get; }
	internal static Material roundedRectWithColorPerBorderMaterial { get; }
	internal static Int32 scrollTroughSide { get; set; }
	internal static DateTime nextScrollStepTime { get; set; }
	public static GUISkin skin { get; set; }
	public static Matrix4x4 matrix { get; set; }
	internal static GenericStack scrollViewStates { get; }

	// RVA: 0x68adc24 VA: 0x7598ec5c24
	public static Color get_color() { }
	// RVA: 0x68adce8 VA: 0x7598ec5ce8
	public static Void set_color(Color value) { }
	// RVA: 0x68adda8 VA: 0x7598ec5da8
	public static Color get_backgroundColor() { }
	// RVA: 0x68ade6c VA: 0x7598ec5e6c
	public static Void set_backgroundColor(Color value) { }
	// RVA: 0x68adf2c VA: 0x7598ec5f2c
	public static Color get_contentColor() { }
	// RVA: 0x68adff0 VA: 0x7598ec5ff0
	public static Void set_contentColor(Color value) { }
	// RVA: 0x68ae0b0 VA: 0x7598ec60b0
	public static Boolean get_changed() { }
	// RVA: 0x68ae0d8 VA: 0x7598ec60d8
	public static Void set_changed(Boolean value) { }
	// RVA: 0x68ae114 VA: 0x7598ec6114
	public static Boolean get_enabled() { }
	// RVA: 0x68ae13c VA: 0x7598ec613c
	public static Void set_enabled(Boolean value) { }
	// RVA: 0x68ae178 VA: 0x7598ec6178
	public static Void set_depth(Int32 value) { }
	// RVA: 0x68ae1b4 VA: 0x7598ec61b4
	internal static Boolean get_usePageScrollbars() { }
	// RVA: 0x68ae1dc VA: 0x7598ec61dc
	internal static Material get_blendMaterial() { }
	// RVA: 0x68ae204 VA: 0x7598ec6204
	internal static Material get_blitMaterial() { }
	// RVA: 0x68ae22c VA: 0x7598ec622c
	internal static Material get_roundedRectMaterial() { }
	// RVA: 0x68ae254 VA: 0x7598ec6254
	internal static Material get_roundedRectWithColorPerBorderMaterial() { }
	// RVA: 0x68ae27c VA: 0x7598ec627c
	internal static Void GrabMouseControl(Int32 id) { }
	// RVA: 0x68ae2b8 VA: 0x7598ec62b8
	internal static Boolean HasMouseControl(Int32 id) { }
	// RVA: 0x68ae2f4 VA: 0x7598ec62f4
	internal static Void ReleaseMouseControl() { }
	// RVA: 0x68ae31c VA: 0x7598ec631c
	public static Void SetNextControlName(String name) { }
	// RVA: 0x68ae358 VA: 0x7598ec6358
	internal static Void InternalRepaintEditorWindow() { }
	// RVA: 0x68ae380 VA: 0x7598ec6380
	private static Rect Internal_DoWindow(Int32 id, Int32 instanceID, Rect clientRect, WindowFunction func, GUIContent title, GUIStyle style, Object skin, Boolean forceRectOnLayout) { }
	// RVA: 0x68ae504 VA: 0x7598ec6504
	private static Void .cctor() { }
	// RVA: 0x68ae7a0 VA: 0x7598ec67a0
	internal static Int32 get_scrollTroughSide() { }
	// RVA: 0x68ae7f8 VA: 0x7598ec67f8
	internal static Void set_scrollTroughSide(Int32 value) { }
	// RVA: 0x68ae854 VA: 0x7598ec6854
	internal static DateTime get_nextScrollStepTime() { }
	// RVA: 0x68ae8ac VA: 0x7598ec68ac
	internal static Void set_nextScrollStepTime(DateTime value) { }
	// RVA: 0x68ae908 VA: 0x7598ec6908
	public static Void set_skin(GUISkin value) { }
	// RVA: 0x68aea14 VA: 0x7598ec6a14
	public static GUISkin get_skin() { }
	// RVA: 0x68ae964 VA: 0x7598ec6964
	internal static Void DoSetSkin(GUISkin newSkin) { }
	// RVA: 0x68aeb4c VA: 0x7598ec6b4c
	public static Matrix4x4 get_matrix() { }
	// RVA: 0x68aec24 VA: 0x7598ec6c24
	public static Void set_matrix(Matrix4x4 value) { }
	// RVA: 0x68aecac VA: 0x7598ec6cac
	public static Void Label(Rect position, String text) { }
	// RVA: 0x68aee38 VA: 0x7598ec6e38
	public static Void Label(Rect position, GUIContent content, GUIStyle style) { }
	// RVA: 0x68af14c VA: 0x7598ec714c
	public static Void DrawTexture(Rect position, Texture image) { }
	// RVA: 0x68af1d4 VA: 0x7598ec71d4
	public static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode) { }
	// RVA: 0x68af26c VA: 0x7598ec726c
	public static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend) { }
	// RVA: 0x68af30c VA: 0x7598ec730c
	public static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend, Single imageAspect) { }
	// RVA: 0x68af3d8 VA: 0x7598ec73d8
	public static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend, Single imageAspect, Color color, Single borderWidth, Single borderRadius) { }
	// RVA: 0x68af4fc VA: 0x7598ec74fc
	public static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend, Single imageAspect, Color color, Vector4 borderWidths, Single borderRadius) { }
	// RVA: 0x68af630 VA: 0x7598ec7630
	public static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend, Single imageAspect, Color color, Vector4 borderWidths, Vector4 borderRadiuses) { }
	// RVA: 0x68af788 VA: 0x7598ec7788
	internal static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend, Single imageAspect, Color color, Vector4 borderWidths, Vector4 borderRadiuses, Boolean drawSmoothCorners) { }
	// RVA: 0x68af8e0 VA: 0x7598ec78e0
	internal static Void DrawTexture(Rect position, Texture image, ScaleMode scaleMode, Boolean alphaBlend, Single imageAspect, Color leftColor, Color topColor, Color rightColor, Color bottomColor, Vector4 borderWidths, Vector4 borderRadiuses, Boolean drawSmoothCorners) { }
	// RVA: 0x68aff84 VA: 0x7598ec7f84
	internal static Boolean CalculateScaledTextureRects(Rect position, ScaleMode scaleMode, Single imageAspect, ref Rect outScreenRect, ref Rect outSourceRect) { }
	// RVA: 0x68b01dc VA: 0x7598ec81dc
	public static Void Box(Rect position, String text) { }
	// RVA: 0x68b0440 VA: 0x7598ec8440
	public static Void Box(Rect position, Texture image) { }
	// RVA: 0x68b02b4 VA: 0x7598ec82b4
	public static Void Box(Rect position, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b0664 VA: 0x7598ec8664
	public static Boolean Button(Rect position, String text) { }
	// RVA: 0x68b07f8 VA: 0x7598ec87f8
	public static Boolean Button(Rect position, GUIContent content) { }
	// RVA: 0x68b073c VA: 0x7598ec873c
	public static Boolean Button(Rect position, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b0894 VA: 0x7598ec8894
	internal static Boolean Button(Rect position, Int32 id, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b0a48 VA: 0x7598ec8a48
	private static Boolean DoRepeatButton(Rect position, GUIContent content, GUIStyle style, FocusType focusType) { }
	// RVA: 0x68b0d24 VA: 0x7598ec8d24
	public static String TextField(Rect position, String text) { }
	// RVA: 0x68b0eec VA: 0x7598ec8eec
	internal static String PasswordFieldGetStrToShow(String password, Char maskChar) { }
	// RVA: 0x68b0e2c VA: 0x7598ec8e2c
	internal static Void DoTextField(Rect position, Int32 id, GUIContent content, Boolean multiline, Int32 maxLength, GUIStyle style) { }
	// RVA: 0x68b1030 VA: 0x7598ec9030
	internal static Void DoTextField(Rect position, Int32 id, GUIContent content, Boolean multiline, Int32 maxLength, GUIStyle style, String secureText) { }
	// RVA: 0x68b10f8 VA: 0x7598ec90f8
	internal static Void DoTextField(Rect position, Int32 id, GUIContent content, Boolean multiline, Int32 maxLength, GUIStyle style, String secureText, Char maskChar) { }
	// RVA: 0x68b1758 VA: 0x7598ec9758
	private static Void HandleTextFieldEventForTouchscreen(Rect position, Int32 id, GUIContent content, Boolean multiline, Int32 maxLength, GUIStyle style, String secureText, Char maskChar, TextEditor editor) { }
	// RVA: 0x68b1b90 VA: 0x7598ec9b90
	private static Void HandleTextFieldEventForDesktop(Rect position, Int32 id, GUIContent content, Boolean multiline, Int32 maxLength, GUIStyle style, TextEditor editor) { }
	// RVA: 0x68b1434 VA: 0x7598ec9434
	private static Void HandleTextFieldEventForDesktopWithForcedKeyboard(Rect position, Int32 id, GUIContent content, Boolean multiline, Int32 maxLength, GUIStyle style, String secureText, TextEditor editor) { }
	// RVA: 0x68b2338 VA: 0x7598eca338
	public static Boolean Toggle(Rect position, Boolean value, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b2520 VA: 0x7598eca520
	public static Int32 SelectionGrid(Rect position, Int32 selected, GUIContent[] contents, Int32 xCount, GUIStyle style) { }
	// RVA: 0x68b31a8 VA: 0x7598ecb1a8
	internal static Int32 CalcTotalHorizSpacing(Int32 xCount, GUIStyle style, GUIStyle firstStyle, GUIStyle midStyle, GUIStyle lastStyle) { }
	// RVA: 0x68b33a0 VA: 0x7598ecb3a0
	internal static Boolean DoControl(Rect position, Int32 id, Boolean on, Boolean hover, GUIContent content, GUIStyle style) { }
	// RVA: 0x68aeed4 VA: 0x7598ec6ed4
	private static Void DoLabel(Rect position, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b2404 VA: 0x7598eca404
	internal static Boolean DoToggle(Rect position, Int32 id, Boolean value, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b0938 VA: 0x7598ec8938
	internal static Boolean DoButton(Rect position, Int32 id, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b2618 VA: 0x7598eca618
	private static Int32 DoButtonGrid(Rect position, Int32 selected, GUIContent[] contents, String[] controlNames, Int32 itemsPerRow, GUIStyle style, GUIStyle firstStyle, GUIStyle midStyle, GUIStyle lastStyle, ToolbarButtonSize buttonSize, Boolean[] contentsEnabled) { }
	// RVA: 0x68b3954 VA: 0x7598ecb954
	private static Rect[] CalcGridRects(Rect position, GUIContent[] contents, Int32 xCount, Single elemWidth, Single elemHeight, GUIStyle style, GUIStyle firstStyle, GUIStyle midStyle, GUIStyle lastStyle, ToolbarButtonSize buttonSize) { }
	// RVA: 0x68b3bf4 VA: 0x7598ecbbf4
	public static Single HorizontalSlider(Rect position, Single value, Single leftValue, Single rightValue, GUIStyle slider, GUIStyle thumb) { }
	// RVA: 0x68b3cc0 VA: 0x7598ecbcc0
	public static Single Slider(Rect position, Single value, Single size, Single start, Single end, GUIStyle slider, GUIStyle thumb, Boolean horiz, Int32 id, GUIStyle thumbExtent) { }
	// RVA: 0x68b3e30 VA: 0x7598ecbe30
	public static Single HorizontalScrollbar(Rect position, Single value, Single size, Single leftValue, Single rightValue, GUIStyle style) { }
	// RVA: 0x68b4a28 VA: 0x7598ecca28
	internal static Boolean ScrollerRepeatButton(Int32 scrollerID, Rect rect, GUIStyle style) { }
	// RVA: 0x68b4d00 VA: 0x7598eccd00
	public static Single VerticalScrollbar(Rect position, Single value, Single size, Single topValue, Single bottomValue, GUIStyle style) { }
	// RVA: 0x68b4374 VA: 0x7598ecc374
	internal static Single Scroller(Rect position, Single value, Single size, Single leftValue, Single rightValue, GUIStyle slider, GUIStyle thumb, GUIStyle leftButton, GUIStyle rightButton, Boolean horiz) { }
	// RVA: 0x68b4e9c VA: 0x7598ecce9c
	public static Void BeginGroup(Rect position, GUIContent content, GUIStyle style) { }
	// RVA: 0x68b4f74 VA: 0x7598eccf74
	internal static Void BeginGroup(Rect position, GUIContent content, GUIStyle style, Vector2 scrollOffset) { }
	// RVA: 0x68b52a8 VA: 0x7598ecd2a8
	public static Void EndGroup() { }
	// RVA: 0x68b5300 VA: 0x7598ecd300
	internal static GenericStack get_scrollViewStates() { }
	// RVA: 0x68b5358 VA: 0x7598ecd358
	public static Vector2 BeginScrollView(Rect position, Vector2 scrollPosition, Rect viewRect, Boolean alwaysShowHorizontal, Boolean alwaysShowVertical) { }
	// RVA: 0x68b545c VA: 0x7598ecd45c
	internal static Vector2 BeginScrollView(Rect position, Vector2 scrollPosition, Rect viewRect, Boolean alwaysShowHorizontal, Boolean alwaysShowVertical, GUIStyle horizontalScrollbar, GUIStyle verticalScrollbar, GUIStyle background) { }
	// RVA: 0x68b6268 VA: 0x7598ece268
	public static Void EndScrollView() { }
	// RVA: 0x68b62b8 VA: 0x7598ece2b8
	public static Void EndScrollView(Boolean handleScrollWheel) { }
	// RVA: 0x68b6ec0 VA: 0x7598eceec0
	public static Rect Window(Int32 id, Rect clientRect, WindowFunction func, GUIContent title, GUIStyle style) { }
	// RVA: 0x68b6f80 VA: 0x7598ecef80
	private static Rect DoWindow(Int32 id, Rect clientRect, WindowFunction func, GUIContent title, GUIStyle style, GUISkin skin, Boolean forceRectOnLayout) { }
	// RVA: 0x68b7068 VA: 0x7598ecf068
	internal static Void CallWindowDelegate(WindowFunction func, Int32 id, Int32 instanceID, GUISkin _skin, Int32 forceRect, Single width, Single height, GUIStyle style) { }
	// RVA: 0x68adcac VA: 0x7598ec5cac
	private static Void get_color_Injected(out Color ret) { }
	// RVA: 0x68add6c VA: 0x7598ec5d6c
	private static Void set_color_Injected(ref Color value) { }
	// RVA: 0x68ade30 VA: 0x7598ec5e30
	private static Void get_backgroundColor_Injected(out Color ret) { }
	// RVA: 0x68adef0 VA: 0x7598ec5ef0
	private static Void set_backgroundColor_Injected(ref Color value) { }
	// RVA: 0x68adfb4 VA: 0x7598ec5fb4
	private static Void get_contentColor_Injected(out Color ret) { }
	// RVA: 0x68ae074 VA: 0x7598ec6074
	private static Void set_contentColor_Injected(ref Color value) { }
	// RVA: 0x68ae468 VA: 0x7598ec6468
	private static Void Internal_DoWindow_Injected(Int32 id, Int32 instanceID, ref Rect clientRect, WindowFunction func, GUIContent title, GUIStyle style, Object skin, Boolean forceRectOnLayout, out Rect ret) { }
}
```