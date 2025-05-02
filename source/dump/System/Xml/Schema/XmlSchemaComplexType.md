# XmlSchemaComplexType

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlSchemaDerivationMethod block`

- `XmlSchemaParticle contentTypeParticle`

- `XmlSchemaAnyAttribute attributeWildcard`

- `Byte pvFlags`


## Properties

- `XmlSchemaParticle ContentTypeParticle`


## Methods

- `XmlSchemaParticle get_ContentTypeParticle()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaComplexType : XmlSchemaType
{
	private XmlSchemaDerivationMethod block; // 0x3c
	private XmlSchemaParticle contentTypeParticle; // 0x40
	private XmlSchemaAnyAttribute attributeWildcard; // 0x48
	private static XmlSchemaComplexType anyTypeLax; // 0x0
	private static XmlSchemaComplexType anyTypeSkip; // 0x8
	private static XmlSchemaComplexType untypedAnyType; // 0x10
	private Byte pvFlags; // 0x50

	internal static XmlSchemaComplexType AnyType { get; }
	internal static ContentValidator AnyTypeContentValidator { get; }
	public override Boolean IsMixed { set; }
	public XmlSchemaParticle ContentTypeParticle { get; }

	// RVA: 0x62ee198 VA: 0x7598906198
	private static Void .cctor() { }
	// RVA: 0x62ee3c0 VA: 0x75989063c0
	private static XmlSchemaComplexType CreateAnyType(XmlSchemaContentProcessing processContents) { }
	// RVA: 0x62ee708 VA: 0x7598906708
	public Void .ctor() { }
	// RVA: 0x62eec94 VA: 0x7598906c94
	internal static XmlSchemaComplexType get_AnyType() { }
	// RVA: 0x62ee7ec VA: 0x75989067ec
	internal static ContentValidator get_AnyTypeContentValidator() { }
	// RVA: 0x62eecec VA: 0x7598906cec
	public override Void set_IsMixed(Boolean value) { }
	// RVA: 0x62eed08 VA: 0x7598906d08
	public XmlSchemaParticle get_ContentTypeParticle() { }
	// RVA: 0x62eed10 VA: 0x7598906d10
	internal Void SetContentTypeParticle(XmlSchemaParticle value) { }
	// RVA: 0x62eed18 VA: 0x7598906d18
	internal Void SetAttributeWildcard(XmlSchemaAnyAttribute value) { }
}
```