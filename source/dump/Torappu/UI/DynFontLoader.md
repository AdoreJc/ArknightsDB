# DynFontLoader

**Namespace:** `Torappu.UI`


## Fields

- `String _fontName`

- `Boolean _autoResume`

- `Text m_text`


## Properties

- `Single minWidth`

- `Single preferredWidth`

- `Single flexibleWidth`

- `Single minHeight`

- `Single preferredHeight`

- `Single flexibleHeight`

- `Int32 layoutPriority`


## Methods

- `Single get_minWidth()`

- `Single get_preferredWidth()`

- `Single get_flexibleWidth()`

- `Single get_minHeight()`

- `Single get_preferredHeight()`

- `Single get_flexibleHeight()`

- `Int32 get_layoutPriority()`

- `Void CalculateLayoutInputHorizontal()`

- `Void CalculateLayoutInputVertical()`

- `Void Start()`

- `Void ManualSetupFont()`

- `Void _SetupFont()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DynFontLoader : MonoBehaviour, ILayoutElement, IHotfixable
{
	private String _fontName; // 0x18
	private Boolean _autoResume; // 0x20
	private Text m_text; // 0x28
	private static DelegateBridge __Hotfix0_get_minWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x8
	private static DelegateBridge __Hotfix0_get_flexibleWidth; // 0x10
	private static DelegateBridge __Hotfix0_get_minHeight; // 0x18
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x20
	private static DelegateBridge __Hotfix0_get_flexibleHeight; // 0x28
	private static DelegateBridge __Hotfix0_get_layoutPriority; // 0x30
	private static DelegateBridge __Hotfix0_CalculateLayoutInputHorizontal; // 0x38
	private static DelegateBridge __Hotfix0_CalculateLayoutInputVertical; // 0x40
	private static DelegateBridge __Hotfix0_Start; // 0x48
	private static DelegateBridge __Hotfix0_ManualSetupFont; // 0x50
	private static DelegateBridge __Hotfix0__SetupFont; // 0x58
	private static DelegateBridge __Hotfix0_GetFontInEditor; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Single minWidth { get; }
	public Single preferredWidth { get; }
	public Single flexibleWidth { get; }
	public Single minHeight { get; }
	public Single preferredHeight { get; }
	public Single flexibleHeight { get; }
	public Int32 layoutPriority { get; }

	// RVA: 0x2172144 VA: 0x759478a144
	public Single get_minWidth() { }
	// RVA: 0x217220c VA: 0x759478a20c
	public Single get_preferredWidth() { }
	// RVA: 0x2172334 VA: 0x759478a334
	public Single get_flexibleWidth() { }
	// RVA: 0x21723fc VA: 0x759478a3fc
	public Single get_minHeight() { }
	// RVA: 0x21724c4 VA: 0x759478a4c4
	public Single get_preferredHeight() { }
	// RVA: 0x21725ec VA: 0x759478a5ec
	public Single get_flexibleHeight() { }
	// RVA: 0x21726b4 VA: 0x759478a6b4
	public Int32 get_layoutPriority() { }
	// RVA: 0x217271c VA: 0x759478a71c
	public Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x21727e0 VA: 0x759478a7e0
	public Void CalculateLayoutInputVertical() { }
	// RVA: 0x21728a4 VA: 0x759478a8a4
	private Void Start() { }
	// RVA: 0x2172c00 VA: 0x759478ac00
	public Void ManualSetupFont() { }
	// RVA: 0x217290c VA: 0x759478a90c
	private Void _SetupFont() { }
	// RVA: 0x2172c68 VA: 0x759478ac68
	public static Font GetFontInEditor(String fontName) { }
	// RVA: 0x2172cdc VA: 0x759478acdc
	public Void .ctor() { }
}
```