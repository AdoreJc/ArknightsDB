# BundleRouter

**Namespace:** `Torappu.Resource.AB`


## Fields

- `String <streamingResPath>k__BackingField`

- `String <persistentResPath>k__BackingField`

- `Mode <mode>k__BackingField`


## Properties

- `String streamingResPath`

- `String persistentResPath`

- `Mode mode`


## Methods

- `String get_streamingResPath()`

- `Void set_streamingResPath(String)`

- `String get_persistentResPath()`

- `Void set_persistentResPath(String)`

- `Mode get_mode()`

- `Void set_mode(Mode)`

- `String GetFullPath(String)`

- `Void GetFullPathInfo(String, out, out)`

- `String GetStreamingOnlyPath(String)`

- `Boolean SelectAndCheckManifestPath(out, out, out)`

- `Boolean _ValidatePersistentInitialBundles(out, out)`

- `Boolean _TryGetStreamingManifestPath(out, out)`

- `Void _InitPersistResInfo()`

- `String _GetPersistABPath(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource.AB
public class BundleRouter : IBundleRouter
{
	private String <streamingResPath>k__BackingField; // 0x10
	private String <persistentResPath>k__BackingField; // 0x18
	private Mode <mode>k__BackingField; // 0x20
	private Dictionary`2 m_persistRefInfo; // 0x28

	public String streamingResPath { get; set; }
	public String persistentResPath { get; set; }
	public Mode mode { get; set; }

	// RVA: 0x374f924 VA: 0x7595d67924
	public String get_streamingResPath() { }
	// RVA: 0x374f92c VA: 0x7595d6792c
	private Void set_streamingResPath(String value) { }
	// RVA: 0x374f934 VA: 0x7595d67934
	public String get_persistentResPath() { }
	// RVA: 0x374f93c VA: 0x7595d6793c
	private Void set_persistentResPath(String value) { }
	// RVA: 0x374f944 VA: 0x7595d67944
	public Mode get_mode() { }
	// RVA: 0x374f94c VA: 0x7595d6794c
	private Void set_mode(Mode value) { }
	// RVA: 0x374bf34 VA: 0x7595d63f34
	public Void .ctor() { }
	// RVA: 0x374fbd4 VA: 0x7595d67bd4
	public String GetFullPath(String path) { }
	// RVA: 0x374b9dc VA: 0x7595d639dc
	public Void GetFullPathInfo(String path, out String fullPath, out Boolean isInteralAsset) { }
	// RVA: 0x374fd34 VA: 0x7595d67d34
	public String GetStreamingOnlyPath(String path) { }
	// RVA: 0x3748c28 VA: 0x7595d60c28
	public Boolean SelectAndCheckManifestPath(out String name, out String path, out Boolean isStreaming) { }
	// RVA: 0x374fda0 VA: 0x7595d67da0
	private Boolean _ValidatePersistentInitialBundles(out String manifestName, out String path) { }
	// RVA: 0x375029c VA: 0x7595d6829c
	private Boolean _TryGetStreamingManifestPath(out String name, out String path) { }
	// RVA: 0x373e538 VA: 0x7595d56538
	public static String StaticStreamingOnlyPath(String path) { }
	// RVA: 0x37503c0 VA: 0x7595d683c0
	public static String GetRuntimePlatformKey() { }
	// RVA: 0x374f954 VA: 0x7595d67954
	public static String GenerateStreamingResPath() { }
	// RVA: 0x3750490 VA: 0x7595d68490
	public static String GetPersistentRootPath() { }
	// RVA: 0x3750498 VA: 0x7595d68498
	public static String LegacyGeneratePersistentResPath() { }
	// RVA: 0x3740014 VA: 0x7595d58014
	public static String GeneratePersistentResPath() { }
	// RVA: 0x373f62c VA: 0x7595d5762c
	public static String GenerateCacheResPath() { }
	// RVA: 0x3750518 VA: 0x7595d68518
	public static String GetDownloadSDKWorkspace() { }
	// RVA: 0x3750584 VA: 0x7595d68584
	public static String GetGameUpdateSDKWorkspace() { }
	// RVA: 0x374fa34 VA: 0x7595d67a34
	private Void _InitPersistResInfo() { }
	// RVA: 0x374fbf8 VA: 0x7595d67bf8
	private String _GetPersistABPath(String resPath) { }
}
```