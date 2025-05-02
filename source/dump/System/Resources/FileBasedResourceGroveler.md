# FileBasedResourceGroveler

**Namespace:** `System.Resources`


## Fields

- `ResourceManagerMediator _mediator`


## Methods

- `ResourceSet GrovelForResourceSet(CultureInfo, Dictionary`2, Boolean, Boolean, ref)`

- `String FindResourceFile(CultureInfo, String)`

- `ResourceSet CreateResourceSet(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Resources
internal class FileBasedResourceGroveler : IResourceGroveler
{
	private ResourceManagerMediator _mediator; // 0x10


	// RVA: 0x5fda7ec VA: 0x75985f27ec
	public Void .ctor(ResourceManagerMediator mediator) { }
	// RVA: 0x5fda81c VA: 0x75985f281c
	public ResourceSet GrovelForResourceSet(CultureInfo culture, Dictionary`2 localResourceSets, Boolean tryParents, Boolean createIfNotExists, ref StackCrawlMark stackMark) { }
	// RVA: 0x5fdab90 VA: 0x75985f2b90
	private String FindResourceFile(CultureInfo culture, String fileName) { }
	// RVA: 0x5fdac50 VA: 0x75985f2c50
	private ResourceSet CreateResourceSet(String file) { }
}
```