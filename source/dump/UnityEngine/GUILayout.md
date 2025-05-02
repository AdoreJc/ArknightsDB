# GUILayout

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
public class GUILayout
{


	// RVA: 0x68b87ac VA: 0x7598ed07ac
	public static Void Label(String text, GUILayoutOption[] options) { }
	// RVA: 0x68b8920 VA: 0x7598ed0920
	public static Void Label(String text, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b8854 VA: 0x7598ed0854
	private static Void DoLabel(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b89fc VA: 0x7598ed09fc
	public static Void Box(Texture image, GUILayoutOption[] options) { }
	// RVA: 0x68b8aa4 VA: 0x7598ed0aa4
	private static Void DoBox(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b8b70 VA: 0x7598ed0b70
	public static Boolean Button(String text, GUILayoutOption[] options) { }
	// RVA: 0x68b8c18 VA: 0x7598ed0c18
	private static Boolean DoButton(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b8ce4 VA: 0x7598ed0ce4
	public static String TextField(String text, GUILayoutOption[] options) { }
	// RVA: 0x68b8d60 VA: 0x7598ed0d60
	private static String DoTextField(String text, Int32 maxLength, Boolean multiline, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b8f38 VA: 0x7598ed0f38
	public static Boolean Toggle(Boolean value, String text, GUILayoutOption[] options) { }
	// RVA: 0x68b8ff0 VA: 0x7598ed0ff0
	private static Boolean DoToggle(Boolean value, GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b90cc VA: 0x7598ed10cc
	public static Int32 SelectionGrid(Int32 selected, String[] texts, Int32 xCount, GUILayoutOption[] options) { }
	// RVA: 0x68b9254 VA: 0x7598ed1254
	public static Int32 SelectionGrid(Int32 selected, Texture[] images, Int32 xCount, GUILayoutOption[] options) { }
	// RVA: 0x68b918c VA: 0x7598ed118c
	public static Int32 SelectionGrid(Int32 selected, GUIContent[] contents, Int32 xCount, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b9314 VA: 0x7598ed1314
	public static Single HorizontalSlider(Single value, Single leftValue, Single rightValue, GUILayoutOption[] options) { }
	// RVA: 0x68b93c0 VA: 0x7598ed13c0
	private static Single DoHorizontalSlider(Single value, Single leftValue, Single rightValue, GUIStyle slider, GUIStyle thumb, GUILayoutOption[] options) { }
	// RVA: 0x68b94fc VA: 0x7598ed14fc
	public static Void Space(Single pixels) { }
	// RVA: 0x68b98c8 VA: 0x7598ed18c8
	public static Void FlexibleSpace() { }
	// RVA: 0x68b9cdc VA: 0x7598ed1cdc
	public static Void BeginHorizontal(GUILayoutOption[] options) { }
	// RVA: 0x68b9d70 VA: 0x7598ed1d70
	public static Void BeginHorizontal(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68ba274 VA: 0x7598ed2274
	public static Void EndHorizontal() { }
	// RVA: 0x68ba544 VA: 0x7598ed2544
	public static Void BeginVertical(GUILayoutOption[] options) { }
	// RVA: 0x68ba78c VA: 0x7598ed278c
	public static Void BeginVertical(GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68ba5d8 VA: 0x7598ed25d8
	public static Void BeginVertical(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68ba7fc VA: 0x7598ed27fc
	public static Void EndVertical() { }
	// RVA: 0x68ba848 VA: 0x7598ed2848
	public static Void BeginArea(Rect screenRect) { }
	// RVA: 0x68bab30 VA: 0x7598ed2b30
	public static Void BeginArea(Rect screenRect, String text) { }
	// RVA: 0x68ba904 VA: 0x7598ed2904
	public static Void BeginArea(Rect screenRect, GUIContent content, GUIStyle style) { }
	// RVA: 0x68bae84 VA: 0x7598ed2e84
	public static Void EndArea() { }
	// RVA: 0x68bb048 VA: 0x7598ed3048
	public static Vector2 BeginScrollView(Vector2 scrollPosition, GUILayoutOption[] options) { }
	// RVA: 0x68bb38c VA: 0x7598ed338c
	public static Vector2 BeginScrollView(Vector2 scrollPosition, Boolean alwaysShowHorizontal, Boolean alwaysShowVertical, GUILayoutOption[] options) { }
	// RVA: 0x68bb0ec VA: 0x7598ed30ec
	public static Vector2 BeginScrollView(Vector2 scrollPosition, Boolean alwaysShowHorizontal, Boolean alwaysShowVertical, GUIStyle horizontalScrollbar, GUIStyle verticalScrollbar, GUIStyle background, GUILayoutOption[] options) { }
	// RVA: 0x68bb440 VA: 0x7598ed3440
	public static Void EndScrollView() { }
	// RVA: 0x68bb448 VA: 0x7598ed3448
	internal static Void EndScrollView(Boolean handleScrollWheel) { }
	// RVA: 0x68bb4c4 VA: 0x7598ed34c4
	public static Rect Window(Int32 id, Rect screenRect, WindowFunction func, String text, GUILayoutOption[] options) { }
	// RVA: 0x68bb5bc VA: 0x7598ed35bc
	private static Rect DoWindow(Int32 id, Rect screenRect, WindowFunction func, GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b7500 VA: 0x7598ecf500
	public static GUILayoutOption Width(Single width) { }
	// RVA: 0x68bb788 VA: 0x7598ed3788
	public static GUILayoutOption MinWidth(Single minWidth) { }
	// RVA: 0x68bb834 VA: 0x7598ed3834
	public static GUILayoutOption MaxWidth(Single maxWidth) { }
	// RVA: 0x68b75a8 VA: 0x7598ecf5a8
	public static GUILayoutOption Height(Single height) { }
	// RVA: 0x68bb8e0 VA: 0x7598ed38e0
	public static GUILayoutOption MinHeight(Single minHeight) { }
	// RVA: 0x68bb98c VA: 0x7598ed398c
	public static GUILayoutOption MaxHeight(Single maxHeight) { }
	// RVA: 0x68b9bf4 VA: 0x7598ed1bf4
	public static GUILayoutOption ExpandWidth(Boolean expand) { }
	// RVA: 0x68b9b44 VA: 0x7598ed1b44
	public static GUILayoutOption ExpandHeight(Boolean expand) { }
}
```