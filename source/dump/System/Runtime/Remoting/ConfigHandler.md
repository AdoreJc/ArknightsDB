# ConfigHandler

**Namespace:** `System.Runtime.Remoting`


## Fields

- `ArrayList typeEntries`

- `ArrayList channelInstances`

- `ChannelData currentChannel`

- `Stack currentProviderData`

- `String currentClientUrl`

- `String appName`

- `String currentXmlPath`

- `Boolean onlyDelayedChannels`


## Methods

- `Void ValidatePath(String, String[])`

- `Boolean CheckPath(String)`

- `Void OnStartParsing(SmallXmlParser)`

- `Void OnProcessingInstruction(String, String)`

- `Void OnIgnorableWhitespace(String)`

- `Void OnStartElement(String, IAttrList)`

- `Void ParseElement(String, IAttrList)`

- `Void OnEndElement(String)`

- `Void ReadCustomProviderData(String, IAttrList)`

- `Void ReadLifetine(IAttrList)`

- `TimeSpan ParseTime(String)`

- `Void ReadChannel(IAttrList, Boolean)`

- `ProviderData ReadProvider(String, IAttrList, Boolean)`

- `Void ReadClientActivated(IAttrList)`

- `Void ReadServiceActivated(IAttrList)`

- `Void ReadClientWellKnown(IAttrList)`

- `Void ReadServiceWellKnown(IAttrList)`

- `Void ReadInteropXml(IAttrList, Boolean)`

- `Void ReadPreload(IAttrList)`

- `String GetNotNull(IAttrList, String)`

- `String ExtractAssembly(ref)`

- `Void OnChars(String)`

- `Void OnEndParsing(SmallXmlParser)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class ConfigHandler : IContentHandler
{
	private ArrayList typeEntries; // 0x10
	private ArrayList channelInstances; // 0x18
	private ChannelData currentChannel; // 0x20
	private Stack currentProviderData; // 0x28
	private String currentClientUrl; // 0x30
	private String appName; // 0x38
	private String currentXmlPath; // 0x40
	private Boolean onlyDelayedChannels; // 0x48


	// RVA: 0x5f7ee4c VA: 0x7598596e4c
	public Void .ctor(Boolean onlyDelayedChannels) { }
	// RVA: 0x5f825c8 VA: 0x759859a5c8
	private Void ValidatePath(String element, String[] paths) { }
	// RVA: 0x5f826ac VA: 0x759859a6ac
	private Boolean CheckPath(String path) { }
	// RVA: 0x5f8278c VA: 0x759859a78c
	public Void OnStartParsing(SmallXmlParser parser) { }
	// RVA: 0x5f82790 VA: 0x759859a790
	public Void OnProcessingInstruction(String name, String text) { }
	// RVA: 0x5f82794 VA: 0x759859a794
	public Void OnIgnorableWhitespace(String s) { }
	// RVA: 0x5f82798 VA: 0x759859a798
	public Void OnStartElement(String name, IAttrList attrs) { }
	// RVA: 0x5f82960 VA: 0x759859a960
	public Void ParseElement(String name, IAttrList attrs) { }
	// RVA: 0x5f85544 VA: 0x759859d544
	public Void OnEndElement(String name) { }
	// RVA: 0x5f83b78 VA: 0x759859bb78
	private Void ReadCustomProviderData(String name, IAttrList attrs) { }
	// RVA: 0x5f83ed8 VA: 0x759859bed8
	private Void ReadLifetine(IAttrList attrs) { }
	// RVA: 0x5f855dc VA: 0x759859d5dc
	private TimeSpan ParseTime(String s) { }
	// RVA: 0x5f8442c VA: 0x759859c42c
	private Void ReadChannel(IAttrList attrs, Boolean isTemplate) { }
	// RVA: 0x5f8480c VA: 0x759859c80c
	private ProviderData ReadProvider(String name, IAttrList attrs, Boolean isTemplate) { }
	// RVA: 0x5f84f14 VA: 0x759859cf14
	private Void ReadClientActivated(IAttrList attrs) { }
	// RVA: 0x5f8505c VA: 0x759859d05c
	private Void ReadServiceActivated(IAttrList attrs) { }
	// RVA: 0x5f84c2c VA: 0x759859cc2c
	private Void ReadClientWellKnown(IAttrList attrs) { }
	// RVA: 0x5f84d24 VA: 0x759859cd24
	private Void ReadServiceWellKnown(IAttrList attrs) { }
	// RVA: 0x5f85128 VA: 0x759859d128
	private Void ReadInteropXml(IAttrList attrs, Boolean isElement) { }
	// RVA: 0x5f852c4 VA: 0x759859d2c4
	private Void ReadPreload(IAttrList attrs) { }
	// RVA: 0x5f85b74 VA: 0x759859db74
	private String GetNotNull(IAttrList attrs, String name) { }
	// RVA: 0x5f85cac VA: 0x759859dcac
	private String ExtractAssembly(ref String type) { }
	// RVA: 0x5f86660 VA: 0x759859e660
	public Void OnChars(String ch) { }
	// RVA: 0x5f86664 VA: 0x759859e664
	public Void OnEndParsing(SmallXmlParser parser) { }
}
```