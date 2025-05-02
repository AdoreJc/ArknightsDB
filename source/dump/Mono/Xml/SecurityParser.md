# SecurityParser

**Namespace:** `Mono.Xml`


## Fields

- `SecurityElement root`

- `SecurityElement current`

- `Stack stack`


## Methods

- `Void LoadXml(String)`

- `SecurityElement ToXml()`

- `Void OnStartParsing(SmallXmlParser)`

- `Void OnProcessingInstruction(String, String)`

- `Void OnIgnorableWhitespace(String)`

- `Void OnStartElement(String, IAttrList)`

- `Void OnEndElement(String)`

- `Void OnChars(String)`

- `Void OnEndParsing(SmallXmlParser)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Xml
internal class SecurityParser : SmallXmlParser, IContentHandler
{
	private SecurityElement root; // 0x68
	private SecurityElement current; // 0x70
	private Stack stack; // 0x78


	// RVA: 0x5ef8d48 VA: 0x7598510d48
	public Void .ctor() { }
	// RVA: 0x5ef8f0c VA: 0x7598510f0c
	public Void LoadXml(String xml) { }
	// RVA: 0x5ef918c VA: 0x759851118c
	public SecurityElement ToXml() { }
	// RVA: 0x5ef9194 VA: 0x7598511194
	public Void OnStartParsing(SmallXmlParser parser) { }
	// RVA: 0x5ef9198 VA: 0x7598511198
	public Void OnProcessingInstruction(String name, String text) { }
	// RVA: 0x5ef919c VA: 0x759851119c
	public Void OnIgnorableWhitespace(String s) { }
	// RVA: 0x5ef91a0 VA: 0x75985111a0
	public Void OnStartElement(String name, IAttrList attrs) { }
	// RVA: 0x5ef9444 VA: 0x7598511444
	public Void OnEndElement(String name) { }
	// RVA: 0x5ef94dc VA: 0x75985114dc
	public Void OnChars(String ch) { }
	// RVA: 0x5ef955c VA: 0x759851155c
	public Void OnEndParsing(SmallXmlParser parser) { }
}
```