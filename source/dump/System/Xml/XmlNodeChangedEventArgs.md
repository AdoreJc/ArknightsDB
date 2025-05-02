# XmlNodeChangedEventArgs

**Namespace:** `System.Xml`


## Fields

- `XmlNodeChangedAction action`

- `XmlNode node`

- `XmlNode oldParent`

- `XmlNode newParent`

- `String oldValue`

- `String newValue`


## Properties

- `XmlNodeChangedAction Action`


## Methods

- `XmlNodeChangedAction get_Action()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlNodeChangedEventArgs : EventArgs
{
	private XmlNodeChangedAction action; // 0x10
	private XmlNode node; // 0x18
	private XmlNode oldParent; // 0x20
	private XmlNode newParent; // 0x28
	private String oldValue; // 0x30
	private String newValue; // 0x38

	public XmlNodeChangedAction Action { get; }

	// RVA: 0x62b7358 VA: 0x75988cf358
	public Void .ctor(XmlNode node, XmlNode oldParent, XmlNode newParent, String oldValue, String newValue, XmlNodeChangedAction action) { }
	// RVA: 0x62b7434 VA: 0x75988cf434
	public XmlNodeChangedAction get_Action() { }
}
```