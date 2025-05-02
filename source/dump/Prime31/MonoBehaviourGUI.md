# MonoBehaviourGUI

**Namespace:** `Prime31`


## Fields

- `Single _width`

- `Single _buttonHeight`

- `StringBuilder _logBuilder`

- `Boolean _logRegistered`

- `Vector2 _logScrollPosition`

- `Boolean _isShowingLogConsole`

- `Single _doubleClickDelay`

- `Single _previousClickTime`

- `Boolean _isIphoneX`

- `Texture2D _normalBackground`

- `Texture2D _bottomButtonBackground`

- `Texture2D _activeBackground`

- `Texture2D _toggleButtonBackground`

- `Boolean _didRetinaIpadCheck`

- `Boolean _isRetinaIpad`


## Properties

- `Texture2D normalBackground`

- `Texture2D bottomButtonBackground`

- `Texture2D activeBackground`

- `Texture2D toggleButtonBackground`


## Methods

- `Texture2D get_normalBackground()`

- `Texture2D get_bottomButtonBackground()`

- `Texture2D get_activeBackground()`

- `Texture2D get_toggleButtonBackground()`

- `Boolean isRetinaOrLargeScreen()`

- `Boolean isRetinaIpad()`

- `Int32 buttonHeight()`

- `Int32 buttonFontSize()`

- `Void checkForIphoneX()`

- `Int32 getNotchOffset()`

- `Void paintWindow(Int32)`

- `Void handleLog(String, String, LogType)`

- `Void OnDestroy()`

- `Void Update()`

- `Void OnGUI()`

- `Void addLogCallback()`

- `Void removeLogCallback()`

- `Void prepGuiSkin()`

- `Void beginColumn()`

- `Void endColumn()`

- `Void endColumn(Boolean)`

- `Void beginRightColumn()`

- `Boolean button(String)`

- `Boolean bottomRightButton(String, Single)`

- `Boolean bottomLeftButton(String, Single)`

- `Boolean bottomCenterButton(String, Single)`

- `Boolean toggleButton(String, String)`

- `Boolean toggleButtonState(String)`

- `Void setTrigger(String, Boolean)`

- `Boolean checkTrigger(String)`


## Dump
```C#
// Dll : P31RestKit.dll
// Namespace : Prime31
public class MonoBehaviourGUI : MonoBehaviour
{
	protected Single _width; // 0x18
	protected Single _buttonHeight; // 0x1c
	protected Dictionary`2 _toggleButtons; // 0x20
	protected Dictionary`2 _toggleTriggers; // 0x28
	protected StringBuilder _logBuilder; // 0x30
	private Boolean _logRegistered; // 0x38
	private Vector2 _logScrollPosition; // 0x3c
	private Boolean _isShowingLogConsole; // 0x44
	private Single _doubleClickDelay; // 0x48
	private Single _previousClickTime; // 0x4c
	private Boolean _isIphoneX; // 0x50
	private Texture2D _normalBackground; // 0x58
	private Texture2D _bottomButtonBackground; // 0x60
	private Texture2D _activeBackground; // 0x68
	private Texture2D _toggleButtonBackground; // 0x70
	private Boolean _didRetinaIpadCheck; // 0x78
	private Boolean _isRetinaIpad; // 0x79

	private Texture2D normalBackground { get; }
	private Texture2D bottomButtonBackground { get; }
	private Texture2D activeBackground { get; }
	private Texture2D toggleButtonBackground { get; }

	// RVA: 0x61bb4b0 VA: 0x75987d34b0
	private Texture2D get_normalBackground() { }
	// RVA: 0x61bb598 VA: 0x75987d3598
	private Texture2D get_bottomButtonBackground() { }
	// RVA: 0x61bb680 VA: 0x75987d3680
	private Texture2D get_activeBackground() { }
	// RVA: 0x61bb770 VA: 0x75987d3770
	private Texture2D get_toggleButtonBackground() { }
	// RVA: 0x61bb858 VA: 0x75987d3858
	private Boolean isRetinaOrLargeScreen() { }
	// RVA: 0x61bb88c VA: 0x75987d388c
	private Boolean isRetinaIpad() { }
	// RVA: 0x61bb8d8 VA: 0x75987d38d8
	private Int32 buttonHeight() { }
	// RVA: 0x61bb928 VA: 0x75987d3928
	private Int32 buttonFontSize() { }
	// RVA: 0x61bb978 VA: 0x75987d3978
	private Void checkForIphoneX() { }
	// RVA: 0x61bba58 VA: 0x75987d3a58
	private Int32 getNotchOffset() { }
	// RVA: 0x61bba9c VA: 0x75987d3a9c
	private Void paintWindow(Int32 id) { }
	// RVA: 0x61bbc2c VA: 0x75987d3c2c
	private Void handleLog(String logString, String stackTrace, LogType type) { }
	// RVA: 0x61bbc88 VA: 0x75987d3c88
	private Void OnDestroy() { }
	// RVA: 0x61bbca0 VA: 0x75987d3ca0
	private Void Update() { }
	// RVA: 0x61bbd94 VA: 0x75987d3d94
	private Void OnGUI() { }
	// RVA: 0x61bbd14 VA: 0x75987d3d14
	private Void addLogCallback() { }
	// RVA: 0x61bbc94 VA: 0x75987d3c94
	private Void removeLogCallback() { }
	// RVA: 0x61bbff4 VA: 0x75987d3ff4
	protected Void prepGuiSkin() { }
	// RVA: 0x61bc2ec VA: 0x75987d42ec
	protected Void beginColumn() { }
	// RVA: 0x61bc3d8 VA: 0x75987d43d8
	protected Void endColumn() { }
	// RVA: 0x61bc3e0 VA: 0x75987d43e0
	protected Void endColumn(Boolean hasSecondColumn) { }
	// RVA: 0x61bc524 VA: 0x75987d4524
	private Void beginRightColumn() { }
	// RVA: 0x61bc62c VA: 0x75987d462c
	protected Boolean button(String text) { }
	// RVA: 0x61bc684 VA: 0x75987d4684
	protected Boolean bottomRightButton(String text, Single width) { }
	// RVA: 0x61bc7fc VA: 0x75987d47fc
	protected Boolean bottomLeftButton(String text, Single width) { }
	// RVA: 0x61bc960 VA: 0x75987d4960
	protected Boolean bottomCenterButton(String text, Single width) { }
	// RVA: 0x61bcac4 VA: 0x75987d4ac4
	protected Boolean toggleButton(String defaultText, String selectedText) { }
	// RVA: 0x61bcd98 VA: 0x75987d4d98
	protected Boolean toggleButtonState(String defaultText) { }
	// RVA: 0x61bce48 VA: 0x75987d4e48
	protected Void setTrigger(String trigger, Boolean state) { }
	// RVA: 0x61bceb0 VA: 0x75987d4eb0
	protected Boolean checkTrigger(String trigger) { }
	// RVA: 0x61bcf44 VA: 0x75987d4f44
	protected virtual Void onLeftColumnGUI() { }
	// RVA: 0x61bcf48 VA: 0x75987d4f48
	protected virtual Void onRightColumnGUI() { }
	// RVA: 0x61bcf4c VA: 0x75987d4f4c
	public static Void loadLevel(Int32 level) { }
	// RVA: 0x61bcfa4 VA: 0x75987d4fa4
	public static Void loadLevel(String level) { }
	// RVA: 0x61bcffc VA: 0x75987d4ffc
	public static Void captureScreenshot(String filename) { }
	// RVA: 0x61bd5c0 VA: 0x75987d55c0
	public static IEnumerator fetchScreenshot(String filename, Single delay) { }
	// RVA: 0x61bd66c VA: 0x75987d566c
	public Void .ctor() { }
}
```