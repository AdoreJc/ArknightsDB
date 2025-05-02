# HTTPCacheFileInfo

**Namespace:** `BestHTTP.Caching`


## Fields

- `Uri <Uri>k__BackingField`

- `DateTime <LastAccess>k__BackingField`

- `Int32 <BodyLength>k__BackingField`

- `String <ETag>k__BackingField`

- `String <LastModified>k__BackingField`

- `DateTime <Expires>k__BackingField`

- `Int64 <Age>k__BackingField`

- `Int64 <MaxAge>k__BackingField`

- `DateTime <Date>k__BackingField`

- `Boolean <MustRevalidate>k__BackingField`

- `DateTime <Received>k__BackingField`

- `String <ConstructedPath>k__BackingField`

- `UInt64 <MappedNameIDX>k__BackingField`


## Properties

- `Int32 BodyLength`

- `String ETag`

- `String LastModified`

- `DateTime Expires`

- `Int64 Age`

- `Int64 MaxAge`

- `DateTime Date`

- `Boolean MustRevalidate`

- `DateTime Received`

- `String ConstructedPath`


## Methods

- `Int32 get_BodyLength()`

- `Void set_BodyLength(Int32)`

- `String get_ETag()`

- `Void set_ETag(String)`

- `String get_LastModified()`

- `Void set_LastModified(String)`

- `DateTime get_Expires()`

- `Void set_Expires(DateTime)`

- `Int64 get_Age()`

- `Void set_Age(Int64)`

- `Int64 get_MaxAge()`

- `Void set_MaxAge(Int64)`

- `DateTime get_Date()`

- `Void set_Date(DateTime)`

- `Boolean get_MustRevalidate()`

- `Void set_MustRevalidate(Boolean)`

- `DateTime get_Received()`

- `Void set_Received(DateTime)`

- `String get_ConstructedPath()`

- `Void set_ConstructedPath(String)`

- `String GetPath()`

- `Boolean IsExists()`

- `Void Reset()`

- `Void SetUpCachingValues(HTTPResponse)`

- `Stream GetBodyStream(out)`

- `Int32 CompareTo(HTTPCacheFileInfo)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Caching
public class HTTPCacheFileInfo : IComparable`1
{
	private Uri <Uri>k__BackingField; // 0x10
	private DateTime <LastAccess>k__BackingField; // 0x18
	private Int32 <BodyLength>k__BackingField; // 0x20
	private String <ETag>k__BackingField; // 0x28
	private String <LastModified>k__BackingField; // 0x30
	private DateTime <Expires>k__BackingField; // 0x38
	private Int64 <Age>k__BackingField; // 0x40
	private Int64 <MaxAge>k__BackingField; // 0x48
	private DateTime <Date>k__BackingField; // 0x50
	private Boolean <MustRevalidate>k__BackingField; // 0x58
	private DateTime <Received>k__BackingField; // 0x60
	private String <ConstructedPath>k__BackingField; // 0x68
	private UInt64 <MappedNameIDX>k__BackingField; // 0x70

	internal Uri Uri { get; set; }
	internal DateTime LastAccess { get; set; }
	public Int32 BodyLength { get; set; }
	private String ETag { get; set; }
	private String LastModified { get; set; }
	private DateTime Expires { get; set; }
	private Int64 Age { get; set; }
	private Int64 MaxAge { get; set; }
	private DateTime Date { get; set; }
	private Boolean MustRevalidate { get; set; }
	private DateTime Received { get; set; }
	private String ConstructedPath { get; set; }
	internal UInt64 MappedNameIDX { get; set; }

	// RVA: 0x6634bd0 VA: 0x7598c4cbd0
	internal Uri get_Uri() { }
	// RVA: 0x6634bd8 VA: 0x7598c4cbd8
	internal Void set_Uri(Uri value) { }
	// RVA: 0x6634be0 VA: 0x7598c4cbe0
	internal DateTime get_LastAccess() { }
	// RVA: 0x6634be8 VA: 0x7598c4cbe8
	internal Void set_LastAccess(DateTime value) { }
	// RVA: 0x6634bf0 VA: 0x7598c4cbf0
	public Int32 get_BodyLength() { }
	// RVA: 0x6634bf8 VA: 0x7598c4cbf8
	public Void set_BodyLength(Int32 value) { }
	// RVA: 0x6634c00 VA: 0x7598c4cc00
	private String get_ETag() { }
	// RVA: 0x6634c08 VA: 0x7598c4cc08
	private Void set_ETag(String value) { }
	// RVA: 0x6634c10 VA: 0x7598c4cc10
	private String get_LastModified() { }
	// RVA: 0x6634c18 VA: 0x7598c4cc18
	private Void set_LastModified(String value) { }
	// RVA: 0x6634c20 VA: 0x7598c4cc20
	private DateTime get_Expires() { }
	// RVA: 0x6634c28 VA: 0x7598c4cc28
	private Void set_Expires(DateTime value) { }
	// RVA: 0x6634c30 VA: 0x7598c4cc30
	private Int64 get_Age() { }
	// RVA: 0x6634c38 VA: 0x7598c4cc38
	private Void set_Age(Int64 value) { }
	// RVA: 0x6634c40 VA: 0x7598c4cc40
	private Int64 get_MaxAge() { }
	// RVA: 0x6634c48 VA: 0x7598c4cc48
	private Void set_MaxAge(Int64 value) { }
	// RVA: 0x6634c50 VA: 0x7598c4cc50
	private DateTime get_Date() { }
	// RVA: 0x6634c58 VA: 0x7598c4cc58
	private Void set_Date(DateTime value) { }
	// RVA: 0x6634c60 VA: 0x7598c4cc60
	private Boolean get_MustRevalidate() { }
	// RVA: 0x6634c68 VA: 0x7598c4cc68
	private Void set_MustRevalidate(Boolean value) { }
	// RVA: 0x6634c74 VA: 0x7598c4cc74
	private DateTime get_Received() { }
	// RVA: 0x6634c7c VA: 0x7598c4cc7c
	private Void set_Received(DateTime value) { }
	// RVA: 0x6634c84 VA: 0x7598c4cc84
	private String get_ConstructedPath() { }
	// RVA: 0x6634c8c VA: 0x7598c4cc8c
	private Void set_ConstructedPath(String value) { }
	// RVA: 0x6634c94 VA: 0x7598c4cc94
	internal UInt64 get_MappedNameIDX() { }
	// RVA: 0x6634c9c VA: 0x7598c4cc9c
	internal Void set_MappedNameIDX(UInt64 value) { }
	// RVA: 0x6634ca4 VA: 0x7598c4cca4
	internal Void .ctor(Uri uri) { }
	// RVA: 0x6634d18 VA: 0x7598c4cd18
	internal Void .ctor(Uri uri, DateTime lastAcces, Int32 bodyLength) { }
	// RVA: 0x6634f38 VA: 0x7598c4cf38
	internal Void .ctor(Uri uri, BinaryReader reader, Int32 version) { }
	// RVA: 0x6635138 VA: 0x7598c4d138
	internal Void SaveTo(BinaryWriter writer) { }
	// RVA: 0x66352f0 VA: 0x7598c4d2f0
	public String GetPath() { }
	// RVA: 0x663541c VA: 0x7598c4d41c
	public Boolean IsExists() { }
	// RVA: 0x66357ac VA: 0x7598c4d7ac
	internal Void Delete() { }
	// RVA: 0x66358f8 VA: 0x7598c4d8f8
	private Void Reset() { }
	// RVA: 0x66359dc VA: 0x7598c4d9dc
	private Void SetUpCachingValues(HTTPResponse response) { }
	// RVA: 0x6635cac VA: 0x7598c4dcac
	internal Boolean WillExpireInTheFuture() { }
	// RVA: 0x6635e60 VA: 0x7598c4de60
	internal Void SetUpRevalidationHeaders(HTTPRequest request) { }
	// RVA: 0x6635f20 VA: 0x7598c4df20
	public Stream GetBodyStream(out Int32 length) { }
	// RVA: 0x6636018 VA: 0x7598c4e018
	internal HTTPResponse ReadResponseTo(HTTPRequest request) { }
	// RVA: 0x6636294 VA: 0x7598c4e294
	internal Void Store(HTTPResponse response) { }
	// RVA: 0x6636968 VA: 0x7598c4e968
	internal Stream GetSaveStream(HTTPResponse response) { }
	// RVA: 0x6637184 VA: 0x7598c4f184
	public Int32 CompareTo(HTTPCacheFileInfo other) { }
}
```