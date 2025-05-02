# ManifestBasedResourceGroveler

**Namespace:** `System.Resources`


## Fields

- `ResourceManagerMediator _mediator`


## Methods

- `ResourceSet GrovelForResourceSet(CultureInfo, Dictionary`2, Boolean, Boolean, ref)`

- `CultureInfo UltimateFallbackFixup(CultureInfo)`

- `Stream GetManifestResourceStream(RuntimeAssembly, String, ref)`

- `Stream CaseInsensitiveManifestResourceStreamLookup(RuntimeAssembly, String)`

- `RuntimeAssembly GetSatelliteAssembly(CultureInfo, ref)`

- `Boolean CanUseDefaultResourceClasses(String, String)`

- `String GetSatelliteAssemblyName()`

- `Void HandleSatelliteMissing()`

- `Void HandleResourceStreamMissing(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Resources
internal class ManifestBasedResourceGroveler : IResourceGroveler
{
	private ResourceManagerMediator _mediator; // 0x10


	// RVA: 0x5fdaf2c VA: 0x75985f2f2c
	public Void .ctor(ResourceManagerMediator mediator) { }
	// RVA: 0x5fdaf5c VA: 0x75985f2f5c
	public ResourceSet GrovelForResourceSet(CultureInfo culture, Dictionary`2 localResourceSets, Boolean tryParents, Boolean createIfNotExists, ref StackCrawlMark stackMark) { }
	// RVA: 0x5fdb218 VA: 0x75985f3218
	private CultureInfo UltimateFallbackFixup(CultureInfo lookForCulture) { }
	// RVA: 0x5fdc590 VA: 0x75985f4590
	internal static CultureInfo GetNeutralResourcesLanguage(Assembly a, ref UltimateResourceFallbackLocation fallbackLocation) { }
	// RVA: 0x5fdb910 VA: 0x75985f3910
	internal ResourceSet CreateResourceSet(Stream store, Assembly assembly) { }
	// RVA: 0x5fdb82c VA: 0x75985f382c
	private Stream GetManifestResourceStream(RuntimeAssembly satellite, String fileName, ref StackCrawlMark stackMark) { }
	// RVA: 0x5fdcaa0 VA: 0x75985f4aa0
	private Stream CaseInsensitiveManifestResourceStreamLookup(RuntimeAssembly satellite, String name) { }
	// RVA: 0x5fdb328 VA: 0x75985f3328
	private RuntimeAssembly GetSatelliteAssembly(CultureInfo lookForCulture, ref StackCrawlMark stackMark) { }
	// RVA: 0x5fdc944 VA: 0x75985f4944
	private Boolean CanUseDefaultResourceClasses(String readerTypeName, String resSetTypeName) { }
	// RVA: 0x5fdce38 VA: 0x75985f4e38
	private String GetSatelliteAssemblyName() { }
	// RVA: 0x5fdb4b8 VA: 0x75985f34b8
	private Void HandleSatelliteMissing() { }
	// RVA: 0x5fdc290 VA: 0x75985f4290
	private Void HandleResourceStreamMissing(String fileName) { }
	// RVA: 0x5fdc8c4 VA: 0x75985f48c4
	private static Boolean GetNeutralResourcesLanguageAttribute(Assembly assembly, ref String cultureName, ref Int16 fallbackLocation) { }
}
```