# ResourceManager

**Namespace:** `System.Resources`


## Fields

- `String BaseNameField`

- `Hashtable ResourceSets`

- `String moduleDir`

- `Assembly MainAssembly`

- `Type _locationInfo`

- `Type _userResourceSet`

- `CultureInfo _neutralResourcesCulture`

- `CultureNameResourceSetPair _lastUsedResourceCache`

- `Boolean _ignoreCase`

- `Boolean UseManifest`

- `Boolean UseSatelliteAssem`

- `UltimateResourceFallbackLocation _fallbackLoc`

- `Version _satelliteContractVersion`

- `Boolean _lookedForSatelliteContractVersion`

- `Assembly _callingAssembly`

- `RuntimeAssembly m_callingAssembly`

- `IResourceGroveler resourceGroveler`


## Properties

- `UltimateResourceFallbackLocation FallbackLocation`


## Methods

- `Void Init()`

- `Void OnDeserializing(StreamingContext)`

- `Void OnDeserialized(StreamingContext)`

- `Void OnSerializing(StreamingContext)`

- `Void CommonAssemblyInit()`

- `UltimateResourceFallbackLocation get_FallbackLocation()`

- `ResourceSet InternalGetResourceSet(CultureInfo, Boolean, Boolean, ref)`

- `Void SetAppXConfiguration()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Resources
public class ResourceManager
{
	protected String BaseNameField; // 0x10
	protected Hashtable ResourceSets; // 0x18
	private Dictionary`2 _resourceSets; // 0x20
	private String moduleDir; // 0x28
	protected Assembly MainAssembly; // 0x30
	private Type _locationInfo; // 0x38
	private Type _userResourceSet; // 0x40
	private CultureInfo _neutralResourcesCulture; // 0x48
	private CultureNameResourceSetPair _lastUsedResourceCache; // 0x50
	private Boolean _ignoreCase; // 0x58
	private Boolean UseManifest; // 0x59
	private Boolean UseSatelliteAssem; // 0x5a
	private UltimateResourceFallbackLocation _fallbackLoc; // 0x5c
	private Version _satelliteContractVersion; // 0x60
	private Boolean _lookedForSatelliteContractVersion; // 0x68
	private Assembly _callingAssembly; // 0x70
	private RuntimeAssembly m_callingAssembly; // 0x78
	private IResourceGroveler resourceGroveler; // 0x80
	public static readonly Int32 MagicNumber; // 0x0
	public static readonly Int32 HeaderVersionNumber; // 0x4
	private static readonly Type _minResourceSet; // 0x8
	internal static readonly String ResReaderTypeName; // 0x10
	internal static readonly String ResSetTypeName; // 0x18
	internal static readonly String MscorlibName; // 0x20
	internal static readonly Int32 DEBUG; // 0x28

	public virtual String BaseName { get; }
	public virtual Boolean IgnoreCase { get; }
	protected UltimateResourceFallbackLocation FallbackLocation { get; }

	// RVA: 0x5fdd100 VA: 0x75985f5100
	private Void Init() { }
	// RVA: 0x5fdd234 VA: 0x75985f5234
	protected Void .ctor() { }
	// RVA: 0x5fdd32c VA: 0x75985f532c
	public Void .ctor(Type resourceSource) { }
	// RVA: 0x5fdd850 VA: 0x75985f5850
	private Void OnDeserializing(StreamingContext ctx) { }
	// RVA: 0x5fdd888 VA: 0x75985f5888
	private Void OnDeserialized(StreamingContext ctx) { }
	// RVA: 0x5fddab4 VA: 0x75985f5ab4
	private Void OnSerializing(StreamingContext ctx) { }
	// RVA: 0x5fdd6ac VA: 0x75985f56ac
	private Void CommonAssemblyInit() { }
	// RVA: 0x5fddb38 VA: 0x75985f5b38
	public virtual String get_BaseName() { }
	// RVA: 0x5fddb40 VA: 0x75985f5b40
	public virtual Boolean get_IgnoreCase() { }
	// RVA: 0x5fddb48 VA: 0x75985f5b48
	protected UltimateResourceFallbackLocation get_FallbackLocation() { }
	// RVA: 0x5fddb50 VA: 0x75985f5b50
	protected virtual String GetResourceFileName(CultureInfo culture) { }
	// RVA: 0x5fddc8c VA: 0x75985f5c8c
	public virtual ResourceSet GetResourceSet(CultureInfo culture, Boolean createIfNotExists, Boolean tryParents) { }
	// RVA: 0x5fde188 VA: 0x75985f6188
	protected virtual ResourceSet InternalGetResourceSet(CultureInfo culture, Boolean createIfNotExists, Boolean tryParents) { }
	// RVA: 0x5fde1ac VA: 0x75985f61ac
	private ResourceSet InternalGetResourceSet(CultureInfo requestedCulture, Boolean createIfNotExists, Boolean tryParents, ref StackCrawlMark stackMark) { }
	// RVA: 0x5fddfe0 VA: 0x75985f5fe0
	private static Void AddResourceSet(Dictionary`2 localResourceSets, String cultureName, ref ResourceSet rs) { }
	// RVA: 0x5fdea08 VA: 0x75985f6a08
	protected static Version GetSatelliteContractVersion(Assembly a) { }
	// RVA: 0x5fdf188 VA: 0x75985f7188
	protected static CultureInfo GetNeutralResourcesLanguage(Assembly a) { }
	// RVA: 0x5fdcea0 VA: 0x75985f4ea0
	internal static Boolean CompareNames(String asmTypeName1, String typeName2, AssemblyName asmName2) { }
	// RVA: 0x5fdd6a8 VA: 0x75985f56a8
	private Void SetAppXConfiguration() { }
	// RVA: 0x5fdf1a0 VA: 0x75985f71a0
	private static Void .cctor() { }
}
```