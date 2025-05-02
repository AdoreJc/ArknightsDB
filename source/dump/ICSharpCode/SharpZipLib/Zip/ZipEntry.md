# ZipEntry

**Namespace:** `ICSharpCode.SharpZipLib.Zip`


## Fields

- `Known known`

- `Int32 externalFileAttributes`

- `UInt16 versionMadeBy`

- `String name`

- `UInt64 size`

- `UInt64 compressedSize`

- `UInt16 versionToExtract`

- `UInt32 crc`

- `UInt32 dosTime`

- `CompressionMethod method`

- `String comment`

- `Int32 flags`

- `Int64 zipFileIndex`

- `Int64 offset`

- `Boolean forceZip64_`

- `Byte cryptoCheckValue_`


## Properties

- `Boolean HasCrc`

- `Boolean IsCrypted`

- `Int32 Flags`

- `Int64 Offset`

- `Int32 ExternalFileAttributes`

- `Int32 HostSystem`

- `Int32 Version`

- `Boolean CanDecompress`

- `Boolean LocalHeaderRequiresZip64`

- `Boolean CentralHeaderRequiresZip64`

- `Int64 DosTime`

- `DateTime DateTime`

- `String Name`

- `Int64 Size`

- `Int64 CompressedSize`

- `Int64 Crc`

- `CompressionMethod CompressionMethod`

- `String Comment`

- `Boolean IsDirectory`


## Methods

- `Boolean get_HasCrc()`

- `Boolean get_IsCrypted()`

- `Void set_IsCrypted(Boolean)`

- `Int32 get_Flags()`

- `Void set_Flags(Int32)`

- `Int64 get_Offset()`

- `Void set_Offset(Int64)`

- `Int32 get_ExternalFileAttributes()`

- `Boolean HasDosAttributes(Int32)`

- `Int32 get_HostSystem()`

- `Int32 get_Version()`

- `Boolean get_CanDecompress()`

- `Void ForceZip64()`

- `Boolean IsZip64Forced()`

- `Boolean get_LocalHeaderRequiresZip64()`

- `Boolean get_CentralHeaderRequiresZip64()`

- `Int64 get_DosTime()`

- `Void set_DosTime(Int64)`

- `Void set_DateTime(DateTime)`

- `String get_Name()`

- `Int64 get_Size()`

- `Void set_Size(Int64)`

- `Int64 get_CompressedSize()`

- `Void set_CompressedSize(Int64)`

- `Int64 get_Crc()`

- `Void set_Crc(Int64)`

- `CompressionMethod get_CompressionMethod()`

- `Void set_CompressionMethod(CompressionMethod)`

- `Void set_ExtraData(Byte[])`

- `Void ProcessAESExtraData(ZipExtraData)`

- `String get_Comment()`

- `Boolean get_IsDirectory()`

- `Boolean IsCompressionMethodSupported()`

- `Object Clone()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip
public class ZipEntry : ICloneable
{
	internal Int32 AESKeySize; // 0x10
	private Known known; // 0x14
	private Int32 externalFileAttributes; // 0x18
	private UInt16 versionMadeBy; // 0x1c
	private String name; // 0x20
	private UInt64 size; // 0x28
	private UInt64 compressedSize; // 0x30
	private UInt16 versionToExtract; // 0x38
	private UInt32 crc; // 0x3c
	private UInt32 dosTime; // 0x40
	private CompressionMethod method; // 0x44
	private Byte[] extra; // 0x48
	private String comment; // 0x50
	private Int32 flags; // 0x58
	private Int64 zipFileIndex; // 0x60
	private Int64 offset; // 0x68
	private Boolean forceZip64_; // 0x70
	private Byte cryptoCheckValue_; // 0x71

	public Boolean HasCrc { get; }
	public Boolean IsCrypted { get; set; }
	internal Byte CryptoCheckValue { get; set; }
	public Int32 Flags { get; set; }
	public Int64 Offset { get; set; }
	public Int32 ExternalFileAttributes { get; }
	public Int32 HostSystem { get; }
	public Int32 Version { get; }
	public Boolean CanDecompress { get; }
	public Boolean LocalHeaderRequiresZip64 { get; }
	public Boolean CentralHeaderRequiresZip64 { get; }
	public Int64 DosTime { get; set; }
	public DateTime DateTime { set; }
	public String Name { get; }
	public Int64 Size { get; set; }
	public Int64 CompressedSize { get; set; }
	public Int64 Crc { get; set; }
	public CompressionMethod CompressionMethod { get; set; }
	internal CompressionMethod CompressionMethodForHeader { get; }
	public Byte[] ExtraData { get; set; }
	internal Int32 AESSaltLen { get; }
	internal Int32 AESOverheadSize { get; }
	public String Comment { get; }
	public Boolean IsDirectory { get; }

	// RVA: 0x5ecd434 VA: 0x75984e5434
	public Void .ctor(String name) { }
	// RVA: 0x5ecd5f4 VA: 0x75984e55f4
	internal Void .ctor(String name, Int32 versionRequiredToExtract) { }
	// RVA: 0x5ecd444 VA: 0x75984e5444
	internal Void .ctor(String name, Int32 versionRequiredToExtract, Int32 madeByInfo, CompressionMethod method) { }
	// RVA: 0x5ecd758 VA: 0x75984e5758
	public Boolean get_HasCrc() { }
	// RVA: 0x5ecd764 VA: 0x75984e5764
	public Boolean get_IsCrypted() { }
	// RVA: 0x5ecd770 VA: 0x75984e5770
	public Void set_IsCrypted(Boolean value) { }
	// RVA: 0x5ecd78c VA: 0x75984e578c
	internal Byte get_CryptoCheckValue() { }
	// RVA: 0x5ecd794 VA: 0x75984e5794
	internal Void set_CryptoCheckValue(Byte value) { }
	// RVA: 0x5ecd79c VA: 0x75984e579c
	public Int32 get_Flags() { }
	// RVA: 0x5ecd7a4 VA: 0x75984e57a4
	public Void set_Flags(Int32 value) { }
	// RVA: 0x5ecd7ac VA: 0x75984e57ac
	public Int64 get_Offset() { }
	// RVA: 0x5ecd7b4 VA: 0x75984e57b4
	public Void set_Offset(Int64 value) { }
	// RVA: 0x5ecd7bc VA: 0x75984e57bc
	public Int32 get_ExternalFileAttributes() { }
	// RVA: 0x5ecd7d4 VA: 0x75984e57d4
	private Boolean HasDosAttributes(Int32 attributes) { }
	// RVA: 0x5ecd804 VA: 0x75984e5804
	public Int32 get_HostSystem() { }
	// RVA: 0x5ecd80c VA: 0x75984e580c
	public Int32 get_Version() { }
	// RVA: 0x5ecd978 VA: 0x75984e5978
	public Boolean get_CanDecompress() { }
	// RVA: 0x5ecda08 VA: 0x75984e5a08
	public Void ForceZip64() { }
	// RVA: 0x5ecda14 VA: 0x75984e5a14
	public Boolean IsZip64Forced() { }
	// RVA: 0x5ecda1c VA: 0x75984e5a1c
	public Boolean get_LocalHeaderRequiresZip64() { }
	// RVA: 0x5ecd8b0 VA: 0x75984e58b0
	public Boolean get_CentralHeaderRequiresZip64() { }
	// RVA: 0x5ecda7c VA: 0x75984e5a7c
	public Int64 get_DosTime() { }
	// RVA: 0x5ecda94 VA: 0x75984e5a94
	public Void set_DosTime(Int64 value) { }
	// RVA: 0x5ecd600 VA: 0x75984e5600
	public Void set_DateTime(DateTime value) { }
	// RVA: 0x5ecdaa8 VA: 0x75984e5aa8
	public String get_Name() { }
	// RVA: 0x5ecdab0 VA: 0x75984e5ab0
	public Int64 get_Size() { }
	// RVA: 0x5ecdac8 VA: 0x75984e5ac8
	public Void set_Size(Int64 value) { }
	// RVA: 0x5ecdadc VA: 0x75984e5adc
	public Int64 get_CompressedSize() { }
	// RVA: 0x5ecdaf4 VA: 0x75984e5af4
	public Void set_CompressedSize(Int64 value) { }
	// RVA: 0x5ecdb08 VA: 0x75984e5b08
	public Int64 get_Crc() { }
	// RVA: 0x5ecdb20 VA: 0x75984e5b20
	public Void set_Crc(Int64 value) { }
	// RVA: 0x5ecdb34 VA: 0x75984e5b34
	public CompressionMethod get_CompressionMethod() { }
	// RVA: 0x5ecdb3c VA: 0x75984e5b3c
	public Void set_CompressionMethod(CompressionMethod value) { }
	// RVA: 0x5ecdbac VA: 0x75984e5bac
	internal CompressionMethod get_CompressionMethodForHeader() { }
	// RVA: 0x5ecdbc8 VA: 0x75984e5bc8
	public Byte[] get_ExtraData() { }
	// RVA: 0x5ecdbd0 VA: 0x75984e5bd0
	public Void set_ExtraData(Byte[] value) { }
	// RVA: 0x5ecdcb8 VA: 0x75984e5cb8
	internal Int32 get_AESSaltLen() { }
	// RVA: 0x5ecdcd0 VA: 0x75984e5cd0
	internal Int32 get_AESOverheadSize() { }
	// RVA: 0x5ecdcec VA: 0x75984e5cec
	internal Void ProcessExtraData(Boolean localHeader) { }
	// RVA: 0x5ece3bc VA: 0x75984e63bc
	private Void ProcessAESExtraData(ZipExtraData extraData) { }
	// RVA: 0x5ece408 VA: 0x75984e6408
	public String get_Comment() { }
	// RVA: 0x5ecd8e0 VA: 0x75984e58e0
	public Boolean get_IsDirectory() { }
	// RVA: 0x5ecd9f8 VA: 0x75984e59f8
	public Boolean IsCompressionMethodSupported() { }
	// RVA: 0x5ece410 VA: 0x75984e6410
	public Object Clone() { }
	// RVA: 0x5ece500 VA: 0x75984e6500
	public override String ToString() { }
	// RVA: 0x5ecdba0 VA: 0x75984e5ba0
	public static Boolean IsCompressionMethodSupported(CompressionMethod method) { }
}
```