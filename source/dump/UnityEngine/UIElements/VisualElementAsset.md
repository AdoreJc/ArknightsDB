# VisualElementAsset

**Namespace:** `UnityEngine.UIElements`


## Fields

- `String m_Name`

- `Int32 m_Id`

- `Int32 m_OrderInDocument`

- `Int32 m_ParentId`

- `Int32 m_RuleIndex`

- `String m_Text`

- `PickingMode m_PickingMode`

- `String m_FullTypeName`

- `Boolean m_SkipClone`


## Properties

- `Int32 id`

- `Int32 orderInDocument`

- `Int32 parentId`

- `Int32 ruleIndex`

- `String fullTypeName`

- `Boolean hasStylesheetPaths`

- `Boolean hasStylesheets`


## Methods

- `Int32 get_id()`

- `Int32 get_orderInDocument()`

- `Int32 get_parentId()`

- `Int32 get_ruleIndex()`

- `String get_fullTypeName()`

- `Boolean get_hasStylesheetPaths()`

- `Boolean get_hasStylesheets()`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`

- `Void AddProperty(String, String)`

- `Void SetOrAddProperty(String, String)`

- `Boolean TryGetAttributeValue(String, out)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualElementAsset : IUxmlAttributes, ISerializationCallbackReceiver
{
	private String m_Name; // 0x10
	private Int32 m_Id; // 0x18
	private Int32 m_OrderInDocument; // 0x1c
	private Int32 m_ParentId; // 0x20
	private Int32 m_RuleIndex; // 0x24
	private String m_Text; // 0x28
	private PickingMode m_PickingMode; // 0x30
	private String m_FullTypeName; // 0x38
	private String[] m_Classes; // 0x40
	private List`1 m_StylesheetPaths; // 0x48
	private List`1 m_Stylesheets; // 0x50
	private Boolean m_SkipClone; // 0x58
	private List`1 m_Properties; // 0x60

	public Int32 id { get; }
	public Int32 orderInDocument { get; }
	public Int32 parentId { get; }
	public Int32 ruleIndex { get; }
	public String fullTypeName { get; }
	public String[] classes { get; }
	public List`1 stylesheetPaths { get; }
	public Boolean hasStylesheetPaths { get; }
	public List`1 stylesheets { get; }
	public Boolean hasStylesheets { get; }
	internal Boolean skipClone { get; }

	// RVA: 0x6a21320 VA: 0x7599039320
	public Int32 get_id() { }
	// RVA: 0x6a21328 VA: 0x7599039328
	public Int32 get_orderInDocument() { }
	// RVA: 0x6a21330 VA: 0x7599039330
	public Int32 get_parentId() { }
	// RVA: 0x6a21338 VA: 0x7599039338
	public Int32 get_ruleIndex() { }
	// RVA: 0x6a21340 VA: 0x7599039340
	public String get_fullTypeName() { }
	// RVA: 0x6a21348 VA: 0x7599039348
	public String[] get_classes() { }
	// RVA: 0x6a21350 VA: 0x7599039350
	public List`1 get_stylesheetPaths() { }
	// RVA: 0x6a213dc VA: 0x75990393dc
	public Boolean get_hasStylesheetPaths() { }
	// RVA: 0x6a213ec VA: 0x75990393ec
	public List`1 get_stylesheets() { }
	// RVA: 0x6a21478 VA: 0x7599039478
	public Boolean get_hasStylesheets() { }
	// RVA: 0x6a21488 VA: 0x7599039488
	internal Boolean get_skipClone() { }
	// RVA: 0x6a21490 VA: 0x7599039490
	public Void OnBeforeSerialize() { }
	// RVA: 0x6a21494 VA: 0x7599039494
	public Void OnAfterDeserialize() { }
	// RVA: 0x6a2161c VA: 0x759903961c
	public Void AddProperty(String propertyName, String propertyValue) { }
	// RVA: 0x6a21620 VA: 0x7599039620
	private Void SetOrAddProperty(String propertyName, String propertyValue) { }
	// RVA: 0x6a21840 VA: 0x7599039840
	public Boolean TryGetAttributeValue(String propertyName, out String value) { }
}
```