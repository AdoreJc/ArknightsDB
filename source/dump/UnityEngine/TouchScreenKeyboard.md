# TouchScreenKeyboard

**Namespace:** `UnityEngine`


## Properties

- `String text`

- `Boolean active`

- `Status status`

- `Int32 characterLimit`

- `Boolean canGetSelection`

- `Boolean canSetSelection`

- `RangeInt selection`


## Methods

- `Void Destroy()`

- `String get_text()`

- `Void set_text(String)`

- `Boolean get_active()`

- `Void set_active(Boolean)`

- `Status get_status()`

- `Void set_characterLimit(Int32)`

- `Boolean get_canGetSelection()`

- `Boolean get_canSetSelection()`

- `RangeInt get_selection()`

- `Void set_selection(RangeInt)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class TouchScreenKeyboard
{
	internal IntPtr m_Ptr; // 0x10
	private static Boolean <disableInPlaceEditing>k__BackingField; // 0x0

	public static Boolean isSupported { get; }
	internal static Boolean disableInPlaceEditing { get; }
	public static Boolean isInPlaceEditingAllowed { get; }
	internal static Boolean isRequiredToForceOpen { get; }
	public String text { get; set; }
	public static Boolean hideInput { set; }
	public Boolean active { get; set; }
	public Status status { get; }
	public Int32 characterLimit { set; }
	public Boolean canGetSelection { get; }
	public Boolean canSetSelection { get; }
	public RangeInt selection { get; set; }

	// RVA: 0x688fabc VA: 0x7598ea7abc
	private static Void Internal_Destroy(IntPtr ptr) { }
	// RVA: 0x688faf8 VA: 0x7598ea7af8
	private Void Destroy() { }
	// RVA: 0x688fbc4 VA: 0x7598ea7bc4
	protected override Void Finalize() { }
	// RVA: 0x688fc58 VA: 0x7598ea7c58
	public Void .ctor(String text, TouchScreenKeyboardType keyboardType, Boolean autocorrection, Boolean multiline, Boolean secure, Boolean alert, String textPlaceholder, Int32 characterLimit) { }
	// RVA: 0x688fdb4 VA: 0x7598ea7db4
	private static IntPtr TouchScreenKeyboard_InternalConstructorHelper(ref TouchScreenKeyboard_InternalConstructorHelperArguments arguments, String text, String textPlaceholder) { }
	// RVA: 0x688fe08 VA: 0x7598ea7e08
	public static Boolean get_isSupported() { }
	// RVA: 0x688fe74 VA: 0x7598ea7e74
	internal static Boolean get_disableInPlaceEditing() { }
	// RVA: 0x688febc VA: 0x7598ea7ebc
	public static Boolean get_isInPlaceEditingAllowed() { }
	// RVA: 0x688ff28 VA: 0x7598ea7f28
	private static Boolean IsInPlaceEditingAllowed() { }
	// RVA: 0x688ff50 VA: 0x7598ea7f50
	internal static Boolean get_isRequiredToForceOpen() { }
	// RVA: 0x688ff78 VA: 0x7598ea7f78
	private static Boolean IsRequiredToForceOpen() { }
	// RVA: 0x688ffa0 VA: 0x7598ea7fa0
	public static TouchScreenKeyboard Open(String text, TouchScreenKeyboardType keyboardType, Boolean autocorrection, Boolean multiline, Boolean secure, Boolean alert, String textPlaceholder, Int32 characterLimit) { }
	// RVA: 0x6890060 VA: 0x7598ea8060
	public static TouchScreenKeyboard Open(String text, TouchScreenKeyboardType keyboardType, Boolean autocorrection, Boolean multiline, Boolean secure) { }
	// RVA: 0x68900ec VA: 0x7598ea80ec
	public String get_text() { }
	// RVA: 0x6890128 VA: 0x7598ea8128
	public Void set_text(String value) { }
	// RVA: 0x689016c VA: 0x7598ea816c
	public static Void set_hideInput(Boolean value) { }
	// RVA: 0x68901a8 VA: 0x7598ea81a8
	public Boolean get_active() { }
	// RVA: 0x68901e4 VA: 0x7598ea81e4
	public Void set_active(Boolean value) { }
	// RVA: 0x6890228 VA: 0x7598ea8228
	public Status get_status() { }
	// RVA: 0x6890264 VA: 0x7598ea8264
	public Void set_characterLimit(Int32 value) { }
	// RVA: 0x68902a8 VA: 0x7598ea82a8
	public Boolean get_canGetSelection() { }
	// RVA: 0x68902e4 VA: 0x7598ea82e4
	public Boolean get_canSetSelection() { }
	// RVA: 0x6890320 VA: 0x7598ea8320
	public RangeInt get_selection() { }
	// RVA: 0x68903b4 VA: 0x7598ea83b4
	public Void set_selection(RangeInt value) { }
	// RVA: 0x6890370 VA: 0x7598ea8370
	private static Void GetSelection(out Int32 start, out Int32 length) { }
	// RVA: 0x68904ac VA: 0x7598ea84ac
	private static Void SetSelection(Int32 start, Int32 length) { }
}
```