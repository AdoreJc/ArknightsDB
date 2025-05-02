# ConfigurationException

**Namespace:** `System.Configuration`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class ConfigurationException : SystemException
{

	public virtual String BareMessage { get; }
	public virtual String Filename { get; }
	public virtual Int32 Line { get; }

	// RVA: 0x6363f4c VA: 0x759897bf4c
	public Void .ctor() { }
	// RVA: 0x6363f84 VA: 0x759897bf84
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6363fbc VA: 0x759897bfbc
	public Void .ctor(String message) { }
	// RVA: 0x6363ff4 VA: 0x759897bff4
	public Void .ctor(String message, Exception inner) { }
	// RVA: 0x636402c VA: 0x759897c02c
	public Void .ctor(String message, Exception inner, String filename, Int32 line) { }
	// RVA: 0x6364064 VA: 0x759897c064
	public Void .ctor(String message, Exception inner, XmlNode node) { }
	// RVA: 0x636409c VA: 0x759897c09c
	public Void .ctor(String message, String filename, Int32 line) { }
	// RVA: 0x63640d4 VA: 0x759897c0d4
	public Void .ctor(String message, XmlNode node) { }
	// RVA: 0x636410c VA: 0x759897c10c
	public virtual String get_BareMessage() { }
	// RVA: 0x6364144 VA: 0x759897c144
	public virtual String get_Filename() { }
	// RVA: 0x636417c VA: 0x759897c17c
	public virtual Int32 get_Line() { }
	// RVA: 0x63641b4 VA: 0x759897c1b4
	public static String GetXmlNodeFilename(XmlNode node) { }
	// RVA: 0x63641ec VA: 0x759897c1ec
	public static Int32 GetXmlNodeLineNumber(XmlNode node) { }
}
```