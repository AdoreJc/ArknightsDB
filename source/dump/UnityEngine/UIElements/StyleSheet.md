# StyleSheet

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_ImportedWithErrors`

- `Boolean m_ImportedWithWarnings`

- `Int32 m_ContentHash`

- `Boolean m_IsDefaultStyleSheet`


## Properties

- `Boolean importedWithErrors`

- `Boolean importedWithWarnings`

- `Int32 contentHash`


## Methods

- `Boolean get_importedWithErrors()`

- `Boolean get_importedWithWarnings()`

- `Int32 get_contentHash()`

- `Void set_contentHash(Int32)`

- `Void FlattenImportedStyleSheetsRecursive(StyleSheet)`

- `Void SetupReferences()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class StyleSheet : ScriptableObject
{
	private Boolean m_ImportedWithErrors; // 0x18
	private Boolean m_ImportedWithWarnings; // 0x19
	private StyleRule[] m_Rules; // 0x20
	private StyleComplexSelector[] m_ComplexSelectors; // 0x28
	internal Single[] floats; // 0x30
	internal Dimension[] dimensions; // 0x38
	internal Color[] colors; // 0x40
	internal String[] strings; // 0x48
	internal Object[] assets; // 0x50
	internal ImportStruct[] imports; // 0x58
	private List`1 m_FlattenedImportedStyleSheets; // 0x60
	private Int32 m_ContentHash; // 0x68
	internal ScalableImage[] scalableImages; // 0x70
	internal Dictionary`2 orderedNameSelectors; // 0x78
	internal Dictionary`2 orderedTypeSelectors; // 0x80
	internal Dictionary`2 orderedClassSelectors; // 0x88
	private Boolean m_IsDefaultStyleSheet; // 0x90
	private static String kCustomPropertyMarker; // 0x0

	public Boolean importedWithErrors { get; set; }
	public Boolean importedWithWarnings { get; set; }
	internal StyleRule[] rules { get; set; }
	internal StyleComplexSelector[] complexSelectors { get; set; }
	internal List`1 flattenedRecursiveImports { get; }
	public Int32 contentHash { get; set; }
	internal Boolean isDefaultStyleSheet { get; set; }

	// RVA: 0x6a19810 VA: 0x7599031810
	public Boolean get_importedWithErrors() { }
	// RVA: 0x6a19818 VA: 0x7599031818
	internal Void set_importedWithErrors(Boolean value) { }
	// RVA: 0x6a19824 VA: 0x7599031824
	public Boolean get_importedWithWarnings() { }
	// RVA: 0x6a1982c VA: 0x759903182c
	internal Void set_importedWithWarnings(Boolean value) { }
	// RVA: 0x6a19838 VA: 0x7599031838
	internal StyleRule[] get_rules() { }
	// RVA: 0x6a19840 VA: 0x7599031840
	internal Void set_rules(StyleRule[] value) { }
	// RVA: 0x6a19dcc VA: 0x7599031dcc
	internal StyleComplexSelector[] get_complexSelectors() { }
	// RVA: 0x6a19dd4 VA: 0x7599031dd4
	internal Void set_complexSelectors(StyleComplexSelector[] value) { }
	// RVA: 0x6a19df0 VA: 0x7599031df0
	internal List`1 get_flattenedRecursiveImports() { }
	// RVA: 0x6a19df8 VA: 0x7599031df8
	public Int32 get_contentHash() { }
	// RVA: 0x6a19e00 VA: 0x7599031e00
	public Void set_contentHash(Int32 value) { }
	// RVA: 0x6a19e08 VA: 0x7599031e08
	internal Boolean get_isDefaultStyleSheet() { }
	// RVA: 0x6a19e10 VA: 0x7599031e10
	internal Void set_isDefaultStyleSheet(Boolean value) { }
	// RVA: 0x VA: 0x0
	private static Boolean TryCheckAccess(T[] list, StyleValueType type, StyleValueHandle handle, out T value) { }
	// RVA: 0x VA: 0x0
	private static T CheckAccess(T[] list, StyleValueType type, StyleValueHandle handle) { }
	// RVA: 0x6a19f70 VA: 0x7599031f70
	internal virtual Void OnEnable() { }
	// RVA: 0x6a19f74 VA: 0x7599031f74
	internal Void FlattenImportedStyleSheetsRecursive() { }
	// RVA: 0x6a19ffc VA: 0x7599031ffc
	private Void FlattenImportedStyleSheetsRecursive(StyleSheet sheet) { }
	// RVA: 0x6a1985c VA: 0x759903185c
	private Void SetupReferences() { }
	// RVA: 0x6a1a214 VA: 0x7599032214
	internal StyleValueKeyword ReadKeyword(StyleValueHandle handle) { }
	// RVA: 0x6a1a21c VA: 0x759903221c
	internal Single ReadFloat(StyleValueHandle handle) { }
	// RVA: 0x6a1a2f8 VA: 0x75990322f8
	internal Boolean TryReadFloat(StyleValueHandle handle, out Single value) { }
	// RVA: 0x6a1a3ec VA: 0x75990323ec
	internal Dimension ReadDimension(StyleValueHandle handle) { }
	// RVA: 0x6a1a4dc VA: 0x75990324dc
	internal Boolean TryReadDimension(StyleValueHandle handle, out Dimension value) { }
	// RVA: 0x6a1a5f8 VA: 0x75990325f8
	internal Color ReadColor(StyleValueHandle handle) { }
	// RVA: 0x6a1a67c VA: 0x759903267c
	internal Boolean TryReadColor(StyleValueHandle handle, out Color value) { }
	// RVA: 0x6a1a708 VA: 0x7599032708
	internal String ReadString(StyleValueHandle handle) { }
	// RVA: 0x6a1a78c VA: 0x759903278c
	internal Boolean TryReadString(StyleValueHandle handle, out String value) { }
	// RVA: 0x6a1a818 VA: 0x7599032818
	internal String ReadEnum(StyleValueHandle handle) { }
	// RVA: 0x6a1a89c VA: 0x759903289c
	internal Boolean TryReadEnum(StyleValueHandle handle, out String value) { }
	// RVA: 0x6a1a928 VA: 0x7599032928
	internal String ReadVariable(StyleValueHandle handle) { }
	// RVA: 0x6a1a9ac VA: 0x75990329ac
	internal Boolean TryReadVariable(StyleValueHandle handle, out String value) { }
	// RVA: 0x6a1aa38 VA: 0x7599032a38
	internal String ReadResourcePath(StyleValueHandle handle) { }
	// RVA: 0x6a1aabc VA: 0x7599032abc
	internal Boolean TryReadResourcePath(StyleValueHandle handle, out String value) { }
	// RVA: 0x6a1ab48 VA: 0x7599032b48
	internal Object ReadAssetReference(StyleValueHandle handle) { }
	// RVA: 0x6a1abcc VA: 0x7599032bcc
	internal String ReadMissingAssetReferenceUrl(StyleValueHandle handle) { }
	// RVA: 0x6a1ac50 VA: 0x7599032c50
	internal Boolean TryReadAssetReference(StyleValueHandle handle, out Object value) { }
	// RVA: 0x6a1acdc VA: 0x7599032cdc
	internal StyleValueFunction ReadFunction(StyleValueHandle handle) { }
	// RVA: 0x6a1ace4 VA: 0x7599032ce4
	internal String ReadFunctionName(StyleValueHandle handle) { }
	// RVA: 0x6a1af2c VA: 0x7599032f2c
	internal ScalableImage ReadScalableImage(StyleValueHandle handle) { }
	// RVA: 0x6a1a150 VA: 0x7599032150
	private static Boolean CustomStartsWith(String originalString, String pattern) { }
	// RVA: 0x6a1afb0 VA: 0x7599032fb0
	public Void .ctor() { }
	// RVA: 0x6a1afb8 VA: 0x7599032fb8
	private static Void .cctor() { }
}
```