# VisualTreeAsset

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_ImportedWithErrors`

- `Boolean m_ImportedWithWarnings`

- `Int32 m_ContentContainerId`

- `Int32 m_ContentHash`


## Properties

- `Boolean importedWithErrors`

- `Boolean importedWithWarnings`

- `Int32 contentHash`


## Methods

- `Boolean get_importedWithErrors()`

- `Boolean get_importedWithWarnings()`

- `TemplateContainer Instantiate()`

- `TemplateContainer Instantiate(String)`

- `TemplateContainer CloneTree()`

- `TemplateContainer CloneTree(String)`

- `Void CloneTree(VisualElement)`

- `Void CloneTree(VisualElement, out, out)`

- `VisualElement CloneSetupRecursively(VisualElementAsset, Dictionary`2, CreationContext)`

- `Int32 get_contentHash()`

- `Void set_contentHash(Int32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class VisualTreeAsset : ScriptableObject
{
	internal static String LinkedVEAInTemplatePropertyName; // 0x0
	private Boolean m_ImportedWithErrors; // 0x18
	private Boolean m_ImportedWithWarnings; // 0x19
	private static readonly Dictionary`2 s_TemporarySlotInsertionPoints; // 0x8
	private List`1 m_Usings; // 0x20
	internal StyleSheet inlineSheet; // 0x28
	private List`1 m_VisualElementAssets; // 0x30
	private List`1 m_TemplateAssets; // 0x38
	private List`1 m_Slots; // 0x40
	private Int32 m_ContentContainerId; // 0x48
	private Int32 m_ContentHash; // 0x4c

	public Boolean importedWithErrors { get; set; }
	public Boolean importedWithWarnings { get; set; }
	public IEnumerable`1 templateDependencies { get; }
	public IEnumerable`1 stylesheets { get; }
	internal List`1 visualElementAssets { get; set; }
	internal List`1 templateAssets { get; set; }
	internal List`1 slots { get; set; }
	internal Int32 contentContainerId { get; set; }
	public Int32 contentHash { get; set; }

	// RVA: 0x6a22e74 VA: 0x759903ae74
	public Boolean get_importedWithErrors() { }
	// RVA: 0x6a22e7c VA: 0x759903ae7c
	internal Void set_importedWithErrors(Boolean value) { }
	// RVA: 0x6a22e88 VA: 0x759903ae88
	public Boolean get_importedWithWarnings() { }
	// RVA: 0x6a22e90 VA: 0x759903ae90
	internal Void set_importedWithWarnings(Boolean value) { }
	// RVA: 0x6a22e9c VA: 0x759903ae9c
	internal Int32 GetNextChildSerialNumber() { }
	// RVA: 0x6a22efc VA: 0x759903aefc
	public IEnumerable`1 get_templateDependencies() { }
	// RVA: 0x6a22fb0 VA: 0x759903afb0
	public IEnumerable`1 get_stylesheets() { }
	// RVA: 0x6a23064 VA: 0x759903b064
	internal List`1 get_visualElementAssets() { }
	// RVA: 0x6a2306c VA: 0x759903b06c
	internal Void set_visualElementAssets(List`1 value) { }
	// RVA: 0x6a23074 VA: 0x759903b074
	internal List`1 get_templateAssets() { }
	// RVA: 0x6a2307c VA: 0x759903b07c
	internal Void set_templateAssets(List`1 value) { }
	// RVA: 0x6a23084 VA: 0x759903b084
	internal List`1 get_slots() { }
	// RVA: 0x6a2308c VA: 0x759903b08c
	internal Void set_slots(List`1 value) { }
	// RVA: 0x6a23094 VA: 0x759903b094
	internal Int32 get_contentContainerId() { }
	// RVA: 0x6a2309c VA: 0x759903b09c
	internal Void set_contentContainerId(Int32 value) { }
	// RVA: 0x6a230a4 VA: 0x759903b0a4
	public TemplateContainer Instantiate() { }
	// RVA: 0x6a2393c VA: 0x759903b93c
	public TemplateContainer Instantiate(String bindingPath) { }
	// RVA: 0x6a23978 VA: 0x759903b978
	public TemplateContainer CloneTree() { }
	// RVA: 0x6a2397c VA: 0x759903b97c
	public TemplateContainer CloneTree(String bindingPath) { }
	// RVA: 0x6a23980 VA: 0x759903b980
	public Void CloneTree(VisualElement target) { }
	// RVA: 0x6a2399c VA: 0x759903b99c
	public Void CloneTree(VisualElement target, out Int32 firstElementIndex, out Int32 elementAddedCount) { }
	// RVA: 0x6a23224 VA: 0x759903b224
	internal Void CloneTree(VisualElement target, Dictionary`2 slotInsertionPoints, List`1 attributeOverrides) { }
	// RVA: 0x6a23e48 VA: 0x759903be48
	private VisualElement CloneSetupRecursively(VisualElementAsset root, Dictionary`2 idToChildren, CreationContext context) { }
	// RVA: 0x6a24f3c VA: 0x759903cf3c
	private static Int32 CompareForOrder(VisualElementAsset a, VisualElementAsset b) { }
	// RVA: 0x6a24e70 VA: 0x759903ce70
	internal Boolean TryGetSlotInsertionPoint(Int32 insertionPointId, out String slotName) { }
	// RVA: 0x6a24f70 VA: 0x759903cf70
	internal VisualTreeAsset ResolveTemplate(String templateName) { }
	// RVA: 0x6a2484c VA: 0x759903c84c
	internal static VisualElement Create(VisualElementAsset asset, CreationContext ctx) { }
	// RVA: 0x6a23b78 VA: 0x759903bb78
	private static Void AssignClassListFromAssetToElement(VisualElementAsset asset, VisualElement element) { }
	// RVA: 0x6a23be4 VA: 0x759903bbe4
	private static Void AssignStyleSheetFromAssetToElement(VisualElementAsset asset, VisualElement element) { }
	// RVA: 0x6a25390 VA: 0x759903d390
	public Int32 get_contentHash() { }
	// RVA: 0x6a25398 VA: 0x759903d398
	public Void set_contentHash(Int32 value) { }
	// RVA: 0x6a253a0 VA: 0x759903d3a0
	public Void .ctor() { }
	// RVA: 0x6a253a8 VA: 0x759903d3a8
	private static Void .cctor() { }
	// RVA: 0x6a25234 VA: 0x759903d234
	internal static VisualElement <Create>g__CreateError|49_0(ref <>c__DisplayClass49_0 ) { }
}
```