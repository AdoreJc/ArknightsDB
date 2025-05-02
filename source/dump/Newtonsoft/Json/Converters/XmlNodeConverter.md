# XmlNodeConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Fields

- `String <DeserializeRootElementName>k__BackingField`

- `Boolean <WriteArrayAttribute>k__BackingField`

- `Boolean <OmitRootObject>k__BackingField`


## Properties

- `String DeserializeRootElementName`

- `Boolean WriteArrayAttribute`

- `Boolean OmitRootObject`


## Methods

- `String get_DeserializeRootElementName()`

- `Boolean get_WriteArrayAttribute()`

- `Boolean get_OmitRootObject()`

- `IXmlNode WrapXml(Object)`

- `Void PushParentNamespaces(IXmlNode, XmlNamespaceManager)`

- `String ResolveFullName(IXmlNode, XmlNamespaceManager)`

- `String GetPropertyName(IXmlNode, XmlNamespaceManager)`

- `Boolean IsArray(IXmlNode)`

- `Void SerializeGroupedNodes(JsonWriter, IXmlNode, XmlNamespaceManager, Boolean)`

- `Void SerializeNode(JsonWriter, IXmlNode, XmlNamespaceManager, Boolean)`

- `Void DeserializeValue(JsonReader, IXmlDocument, XmlNamespaceManager, String, IXmlNode)`

- `Void ReadElement(JsonReader, IXmlDocument, IXmlNode, String, XmlNamespaceManager)`

- `Void CreateElement(JsonReader, IXmlDocument, IXmlNode, String, XmlNamespaceManager, String, Dictionary`2)`

- `String ConvertTokenToXmlValue(JsonReader)`

- `Void ReadArrayElements(JsonReader, IXmlDocument, String, IXmlNode, XmlNamespaceManager)`

- `Void AddJsonArrayAttribute(IXmlElement, IXmlDocument)`

- `Void CreateInstruction(JsonReader, IXmlDocument, IXmlNode, String)`

- `Void CreateDocumentType(JsonReader, IXmlDocument, IXmlNode)`

- `IXmlElement CreateElement(String, IXmlDocument, String, XmlNamespaceManager)`

- `Void DeserializeNode(JsonReader, IXmlDocument, XmlNamespaceManager, IXmlNode)`

- `Boolean IsNamespaceAttribute(String, out)`

- `Boolean ValueAttributes(List`1)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class XmlNodeConverter : JsonConverter
{
	private String <DeserializeRootElementName>k__BackingField; // 0x10
	private Boolean <WriteArrayAttribute>k__BackingField; // 0x18
	private Boolean <OmitRootObject>k__BackingField; // 0x19

	public String DeserializeRootElementName { get; }
	public Boolean WriteArrayAttribute { get; }
	public Boolean OmitRootObject { get; }

	// RVA: 0x61af220 VA: 0x75987c7220
	public String get_DeserializeRootElementName() { }
	// RVA: 0x61af228 VA: 0x75987c7228
	public Boolean get_WriteArrayAttribute() { }
	// RVA: 0x61af230 VA: 0x75987c7230
	public Boolean get_OmitRootObject() { }
	// RVA: 0x61af238 VA: 0x75987c7238
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61af35c VA: 0x75987c735c
	private IXmlNode WrapXml(Object value) { }
	// RVA: 0x61af478 VA: 0x75987c7478
	private Void PushParentNamespaces(IXmlNode node, XmlNamespaceManager manager) { }
	// RVA: 0x61b11e0 VA: 0x75987c91e0
	private String ResolveFullName(IXmlNode node, XmlNamespaceManager manager) { }
	// RVA: 0x61b14fc VA: 0x75987c94fc
	private String GetPropertyName(IXmlNode node, XmlNamespaceManager manager) { }
	// RVA: 0x61b1924 VA: 0x75987c9924
	private Boolean IsArray(IXmlNode node) { }
	// RVA: 0x61b1d10 VA: 0x75987c9d10
	private Void SerializeGroupedNodes(JsonWriter writer, IXmlNode node, XmlNamespaceManager manager, Boolean writePropertyName) { }
	// RVA: 0x61afae8 VA: 0x75987c7ae8
	private Void SerializeNode(JsonWriter writer, IXmlNode node, XmlNamespaceManager manager, Boolean writePropertyName) { }
	// RVA: 0x61b2294 VA: 0x75987ca294
	private static Boolean AllSameName(IXmlNode node) { }
	// RVA: 0x61b2754 VA: 0x75987ca754
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61b3740 VA: 0x75987cb740
	private Void DeserializeValue(JsonReader reader, IXmlDocument document, XmlNamespaceManager manager, String propertyName, IXmlNode currentNode) { }
	// RVA: 0x61b2da4 VA: 0x75987cada4
	private Void ReadElement(JsonReader reader, IXmlDocument document, IXmlNode currentNode, String propertyName, XmlNamespaceManager manager) { }
	// RVA: 0x61b514c VA: 0x75987cd14c
	private Void CreateElement(JsonReader reader, IXmlDocument document, IXmlNode currentNode, String elementName, XmlNamespaceManager manager, String elementPrefix, Dictionary`2 attributeNameValues) { }
	// RVA: 0x61b4ec0 VA: 0x75987ccec0
	private static Void AddAttribute(JsonReader reader, IXmlDocument document, IXmlNode currentNode, String attributeName, XmlNamespaceManager manager, String attributePrefix) { }
	// RVA: 0x61b5974 VA: 0x75987cd974
	private String ConvertTokenToXmlValue(JsonReader reader) { }
	// RVA: 0x61b44c4 VA: 0x75987cc4c4
	private Void ReadArrayElements(JsonReader reader, IXmlDocument document, String propertyName, IXmlNode currentNode, XmlNamespaceManager manager) { }
	// RVA: 0x61b5f74 VA: 0x75987cdf74
	private Void AddJsonArrayAttribute(IXmlElement element, IXmlDocument document) { }
	// RVA: 0x61b4850 VA: 0x75987cc850
	private Dictionary`2 ReadAttributeElements(JsonReader reader, XmlNamespaceManager manager) { }
	// RVA: 0x61b3cd0 VA: 0x75987cbcd0
	private Void CreateInstruction(JsonReader reader, IXmlDocument document, IXmlNode currentNode, String propertyName) { }
	// RVA: 0x61b411c VA: 0x75987cc11c
	private Void CreateDocumentType(JsonReader reader, IXmlDocument document, IXmlNode currentNode) { }
	// RVA: 0x61b57cc VA: 0x75987cd7cc
	private IXmlElement CreateElement(String elementName, IXmlDocument document, String elementPrefix, XmlNamespaceManager manager) { }
	// RVA: 0x61b307c VA: 0x75987cb07c
	private Void DeserializeNode(JsonReader reader, IXmlDocument document, XmlNamespaceManager manager, IXmlNode currentNode) { }
	// RVA: 0x61b62b4 VA: 0x75987ce2b4
	private Boolean IsNamespaceAttribute(String attributeName, out String prefix) { }
	// RVA: 0x61b2540 VA: 0x75987ca540
	private Boolean ValueAttributes(List`1 c) { }
	// RVA: 0x61b63ac VA: 0x75987ce3ac
	public override Boolean CanConvert(Type valueType) { }
	// RVA: 0x61b64a4 VA: 0x75987ce4a4
	public Void .ctor() { }
}
```