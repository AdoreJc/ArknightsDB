# Uri

**Namespace:** `Mono.Security`


## Fields

- `Boolean isUnixFilePath`

- `String source`

- `String scheme`

- `String host`

- `Int32 port`

- `String path`

- `String query`

- `String fragment`

- `String userinfo`

- `Boolean isUnc`

- `Boolean isOpaquePart`

- `Boolean userEscaped`

- `String cachedToString`

- `String cachedLocalPath`

- `Int32 cachedHashCode`

- `Boolean reduce`


## Properties

- `String AbsolutePath`

- `Boolean IsFile`

- `Boolean IsUnc`

- `String LocalPath`


## Methods

- `String get_AbsolutePath()`

- `Boolean get_IsFile()`

- `Boolean get_IsUnc()`

- `String get_LocalPath()`

- `String GetLeftPart(UriPartial)`

- `Void Parse()`

- `String Unescape(String)`

- `Void ParseAsWindowsUNC(String)`

- `Void ParseAsWindowsAbsoluteFilePath(String)`

- `Void ParseAsUnixAbsoluteFilePath(String)`

- `Void Parse(String)`

- `String GetOpaqueWiseSchemeDelimiter()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Security
internal class Uri
{
	private Boolean isUnixFilePath; // 0x10
	private String source; // 0x18
	private String scheme; // 0x20
	private String host; // 0x28
	private Int32 port; // 0x30
	private String path; // 0x38
	private String query; // 0x40
	private String fragment; // 0x48
	private String userinfo; // 0x50
	private Boolean isUnc; // 0x58
	private Boolean isOpaquePart; // 0x59
	private Boolean userEscaped; // 0x5a
	private String cachedToString; // 0x60
	private String cachedLocalPath; // 0x68
	private Int32 cachedHashCode; // 0x70
	private Boolean reduce; // 0x74
	private static readonly String hexUpperChars; // 0x0
	public static readonly String SchemeDelimiter; // 0x8
	public static readonly String UriSchemeFile; // 0x10
	public static readonly String UriSchemeFtp; // 0x18
	public static readonly String UriSchemeGopher; // 0x20
	public static readonly String UriSchemeHttp; // 0x28
	public static readonly String UriSchemeHttps; // 0x30
	public static readonly String UriSchemeMailto; // 0x38
	public static readonly String UriSchemeNews; // 0x40
	public static readonly String UriSchemeNntp; // 0x48
	private static UriScheme[] schemes; // 0x50

	public String AbsolutePath { get; }
	public Boolean IsFile { get; }
	public Boolean IsUnc { get; }
	public String LocalPath { get; }

	// RVA: 0x5f04de0 VA: 0x759851cde0
	public Void .ctor(String uriString) { }
	// RVA: 0x5f04de8 VA: 0x759851cde8
	public Void .ctor(String uriString, Boolean dontEscape) { }
	// RVA: 0x5f04fac VA: 0x759851cfac
	public String get_AbsolutePath() { }
	// RVA: 0x5f04fb4 VA: 0x759851cfb4
	public Boolean get_IsFile() { }
	// RVA: 0x5f0501c VA: 0x759851d01c
	public Boolean get_IsUnc() { }
	// RVA: 0x5f05024 VA: 0x759851d024
	public String get_LocalPath() { }
	// RVA: 0x5f05310 VA: 0x759851d310
	public override Boolean Equals(Object comparant) { }
	// RVA: 0x5f05540 VA: 0x759851d540
	public override Int32 GetHashCode() { }
	// RVA: 0x5f05614 VA: 0x759851d614
	public String GetLeftPart(UriPartial part) { }
	// RVA: 0x5f05b88 VA: 0x759851db88
	public static Int32 FromHex(Char digit) { }
	// RVA: 0x5f05c28 VA: 0x759851dc28
	public static String HexEscape(Char character) { }
	// RVA: 0x5f05d94 VA: 0x759851dd94
	public static Char HexUnescape(String pattern, ref Int32 index) { }
	// RVA: 0x5f060b0 VA: 0x759851e0b0
	public static Boolean IsHexDigit(Char digit) { }
	// RVA: 0x5f060ec VA: 0x759851e0ec
	public static Boolean IsHexEncoding(String pattern, Int32 index) { }
	// RVA: 0x5f0621c VA: 0x759851e21c
	public override String ToString() { }
	// RVA: 0x5f06498 VA: 0x759851e498
	protected static String EscapeString(String str) { }
	// RVA: 0x5f064f8 VA: 0x759851e4f8
	internal static String EscapeString(String str, Boolean escapeReserved, Boolean escapeHex, Boolean escapeBrackets) { }
	// RVA: 0x5f04efc VA: 0x759851cefc
	protected Void Parse() { }
	// RVA: 0x5f05308 VA: 0x759851d308
	protected String Unescape(String str) { }
	// RVA: 0x5f0630c VA: 0x759851e30c
	internal String Unescape(String str, Boolean excludeSharp) { }
	// RVA: 0x5f0743c VA: 0x759851f43c
	private Void ParseAsWindowsUNC(String uriString) { }
	// RVA: 0x5f07630 VA: 0x759851f630
	private Void ParseAsWindowsAbsoluteFilePath(String uriString) { }
	// RVA: 0x5f077f0 VA: 0x759851f7f0
	private Void ParseAsUnixAbsoluteFilePath(String uriString) { }
	// RVA: 0x5f067f4 VA: 0x759851e7f4
	private Void Parse(String uriString) { }
	// RVA: 0x5f07b7c VA: 0x759851fb7c
	private static String Reduce(String path) { }
	// RVA: 0x5f07ec0 VA: 0x759851fec0
	internal static String GetSchemeDelimiter(String scheme) { }
	// RVA: 0x5f05a7c VA: 0x759851da7c
	internal static Int32 GetDefaultPort(String scheme) { }
	// RVA: 0x5f059f8 VA: 0x759851d9f8
	private String GetOpaqueWiseSchemeDelimiter() { }
	// RVA: 0x5f079b8 VA: 0x759851f9b8
	private static Boolean IsPredefinedScheme(String scheme) { }
	// RVA: 0x5f07fc0 VA: 0x759851ffc0
	private static Void .cctor() { }
}
```