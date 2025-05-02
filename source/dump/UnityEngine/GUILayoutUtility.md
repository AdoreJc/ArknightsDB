# GUILayoutUtility

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
public class GUILayoutUtility
{
	private static readonly Dictionary`2 s_StoredLayouts; // 0x0
	private static readonly Dictionary`2 s_StoredWindows; // 0x8
	internal static LayoutCache current; // 0x10
	internal static readonly Rect kDummyRect; // 0x18
	private static Int32 <unbalancedgroupscount>k__BackingField; // 0x28
	private static GUIStyle s_SpaceStyle; // 0x30

	internal static Int32 unbalancedgroupscount { get; set; }
	internal static GUIStyle spaceStyle { get; }

	// RVA: 0x68bbb84 VA: 0x7598ed3b84
	private static Rect Internal_GetWindowRect(Int32 windowID) { }
	// RVA: 0x68bbc58 VA: 0x7598ed3c58
	private static Void Internal_MoveWindow(Int32 windowID, Rect r) { }
	// RVA: 0x68bbd28 VA: 0x7598ed3d28
	internal static Int32 get_unbalancedgroupscount() { }
	// RVA: 0x68bbd80 VA: 0x7598ed3d80
	internal static Void set_unbalancedgroupscount(Int32 value) { }
	// RVA: 0x68bbddc VA: 0x7598ed3ddc
	internal static LayoutCache GetLayoutCache(Int32 instanceID, Boolean isWindow) { }
	// RVA: 0x68b738c VA: 0x7598ecf38c
	internal static LayoutCache SelectIDList(Int32 instanceID, Boolean isWindow) { }
	// RVA: 0x68bbf94 VA: 0x7598ed3f94
	internal static Void RemoveSelectedIdList(Int32 instanceID, Boolean isWindow) { }
	// RVA: 0x68bc068 VA: 0x7598ed4068
	internal static Void Begin(Int32 instanceID) { }
	// RVA: 0x68bc29c VA: 0x7598ed429c
	internal static Void BeginContainer(LayoutCache cache) { }
	// RVA: 0x68b7654 VA: 0x7598ecf654
	internal static Void BeginWindow(Int32 windowID, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b792c VA: 0x7598ecf92c
	internal static Void Layout() { }
	// RVA: 0x68bc7e8 VA: 0x7598ed47e8
	internal static Void LayoutFromEditorWindow() { }
	// RVA: 0x68bc994 VA: 0x7598ed4994
	internal static Void LayoutFromContainer(Single w, Single h) { }
	// RVA: 0x68bc454 VA: 0x7598ed4454
	internal static Void LayoutFreeGroup(GUILayoutGroup toplevel) { }
	// RVA: 0x68bc618 VA: 0x7598ed4618
	private static Void LayoutSingleGroup(GUILayoutGroup i) { }
	// RVA: 0x68bcb1c VA: 0x7598ed4b1c
	private static GUILayoutGroup CreateGUILayoutGroupInstanceOfType(Type LayoutType) { }
	// RVA: 0x68b9f20 VA: 0x7598ed1f20
	internal static GUILayoutGroup BeginLayoutGroup(GUIStyle style, GUILayoutOption[] options, Type layoutType) { }
	// RVA: 0x68ba2c0 VA: 0x7598ed22c0
	internal static Void EndLayoutGroup() { }
	// RVA: 0x68babf0 VA: 0x7598ed2bf0
	internal static GUILayoutGroup BeginLayoutArea(GUIStyle style, Type layoutType) { }
	// RVA: 0x68b8990 VA: 0x7598ed0990
	public static Rect GetRect(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68bcc6c VA: 0x7598ed4c6c
	private static Rect DoGetRect(GUIContent content, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68bd060 VA: 0x7598ed5060
	public static Rect GetRect(Single width, Single height) { }
	// RVA: 0x68b9844 VA: 0x7598ed1844
	public static Rect GetRect(Single width, Single height, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68bd104 VA: 0x7598ed5104
	private static Rect DoGetRect(Single minWidth, Single maxWidth, Single minHeight, Single maxHeight, GUIStyle style, GUILayoutOption[] options) { }
	// RVA: 0x68b9740 VA: 0x7598ed1740
	internal static GUIStyle get_spaceStyle() { }
	// RVA: 0x68bd3b8 VA: 0x7598ed53b8
	private static Void .cctor() { }
	// RVA: 0x68bbc14 VA: 0x7598ed3c14
	private static Void Internal_GetWindowRect_Injected(Int32 windowID, out Rect ret) { }
	// RVA: 0x68bbce4 VA: 0x7598ed3ce4
	private static Void Internal_MoveWindow_Injected(Int32 windowID, ref Rect r) { }
}
```