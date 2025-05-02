# Uri

**Namespace:** `System`


## Fields

- `String m_String`

- `String m_originalUnicodeString`

- `UriParser m_Syntax`

- `String m_DnsSafeHost`

- `Flags m_Flags`

- `UriInfo m_Info`

- `Boolean m_iriParsing`


## Properties

- `Boolean IsImplicitFile`

- `Boolean IsUncOrDosPath`

- `Boolean IsDosPath`

- `Boolean IsUncPath`

- `Flags HostType`

- `UriParser Syntax`

- `Boolean IsNotAbsoluteUri`

- `Boolean AllowIdn`

- `UInt16 SecuredPathIndex`

- `String AbsolutePath`

- `String PrivateAbsolutePath`

- `String AbsoluteUri`

- `String LocalPath`

- `String Authority`

- `UriHostNameType HostNameType`

- `Boolean IsDefaultPort`

- `Boolean IsFile`

- `Boolean IsLoopback`

- `String PathAndQuery`

- `Boolean IsUnc`

- `String Host`

- `Int32 Port`

- `String Query`

- `String Fragment`

- `String Scheme`

- `Boolean OriginalStringSwitched`

- `String OriginalString`

- `String DnsSafeHost`

- `Boolean IsAbsoluteUri`

- `Boolean UserEscaped`

- `String UserInfo`


## Methods

- `Boolean get_IsImplicitFile()`

- `Boolean get_IsUncOrDosPath()`

- `Boolean get_IsDosPath()`

- `Boolean get_IsUncPath()`

- `Flags get_HostType()`

- `UriParser get_Syntax()`

- `Boolean get_IsNotAbsoluteUri()`

- `Boolean get_AllowIdn()`

- `Boolean AllowIdnStatic(UriParser, Flags)`

- `Boolean IsIntranet(String)`

- `Void SetUserDrivenParsing()`

- `UInt16 get_SecuredPathIndex()`

- `Boolean NotAny(Flags)`

- `Boolean InFact(Flags)`

- `UriInfo EnsureUriInfo()`

- `Void EnsureParseRemaining()`

- `Void EnsureHostString(Boolean)`

- `Void CreateUri(Uri, String, Boolean)`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `String get_AbsolutePath()`

- `String get_PrivateAbsolutePath()`

- `String get_AbsoluteUri()`

- `String get_LocalPath()`

- `String get_Authority()`

- `UriHostNameType get_HostNameType()`

- `Boolean get_IsDefaultPort()`

- `Boolean get_IsFile()`

- `Boolean get_IsLoopback()`

- `String get_PathAndQuery()`

- `Boolean get_IsUnc()`

- `String get_Host()`

- `String GetLocalPath()`

- `Int32 get_Port()`

- `String get_Query()`

- `String get_Fragment()`

- `String get_Scheme()`

- `Boolean get_OriginalStringSwitched()`

- `String get_OriginalString()`

- `String get_DnsSafeHost()`

- `Boolean get_IsAbsoluteUri()`

- `Boolean get_UserEscaped()`

- `String get_UserInfo()`

- `ParsingError PrivateParseMinimal()`

- `Void PrivateParseMinimalIri(String, UInt16)`

- `Void CreateUriInfo(Flags)`

- `Void CreateHostString()`

- `Void GetHostViaCustomSyntax()`

- `String GetEscapedParts(UriComponents)`

- `String GetUnescapedParts(UriComponents, UriFormat)`

- `String ReCreateParts(UriComponents, UInt16, UriFormat)`

- `String GetUriPartsFromUserString(UriComponents)`

- `Void ParseRemaining()`

- `UInt16 CheckAuthorityHelper(Char*, UInt16, UInt16, ref, ref, UriParser, ref)`

- `Void CheckAuthorityHelperHandleDnsIri(Char*, UInt16, Int32, Int32, Boolean, Boolean, UriParser, String, ref, ref, ref, ref)`

- `Void CheckAuthorityHelperHandleAnyHostIri(Char*, Int32, Int32, Boolean, Boolean, UriParser, ref, ref, ref)`

- `Void FindEndOfComponent(String, ref, UInt16, Char)`

- `Void FindEndOfComponent(Char*, ref, UInt16, Char)`

- `Check CheckCanonical(Char*, ref, UInt16, Char)`

- `Void CreateThis(String, Boolean, UriKind)`

- `Void InitializeUri(ParsingError, UriKind, out)`

- `Boolean CheckForConfigLoad(String)`

- `Boolean CheckForUnicode(String)`

- `Boolean CheckForEscapedUnreserved(String)`

- `String GetComponents(UriComponents, UriFormat)`

- `String GetRelativeSerializationString(UriFormat)`

- `Boolean IsBaseOf(Uri)`

- `Void CreateThisFromUri(Uri)`


## Dump
```C#
// Dll : System.dll
// Namespace : System
public class Uri : ISerializable
{
	public static readonly String UriSchemeFile; // 0x0
	public static readonly String UriSchemeFtp; // 0x8
	public static readonly String UriSchemeGopher; // 0x10
	public static readonly String UriSchemeHttp; // 0x18
	public static readonly String UriSchemeHttps; // 0x20
	internal static readonly String UriSchemeWs; // 0x28
	internal static readonly String UriSchemeWss; // 0x30
	public static readonly String UriSchemeMailto; // 0x38
	public static readonly String UriSchemeNews; // 0x40
	public static readonly String UriSchemeNntp; // 0x48
	public static readonly String UriSchemeNetTcp; // 0x50
	public static readonly String UriSchemeNetPipe; // 0x58
	public static readonly String SchemeDelimiter; // 0x60
	private const Int32 c_Max16BitUtf8SequenceLength; // 0x0
	internal const Int32 c_MaxUriBufferSize; // 0x0
	private const Int32 c_MaxUriSchemeName; // 0x0
	private String m_String; // 0x10
	private String m_originalUnicodeString; // 0x18
	private UriParser m_Syntax; // 0x20
	private String m_DnsSafeHost; // 0x28
	private Flags m_Flags; // 0x30
	private UriInfo m_Info; // 0x38
	private Boolean m_iriParsing; // 0x40
	private static Boolean s_ConfigInitialized; // 0x68
	private static Boolean s_ConfigInitializing; // 0x69
	private static UriIdnScope s_IdnScope; // 0x6c
	private static Boolean s_IriParsing; // 0x70
	private static Boolean useDotNetRelativeOrAbsolute; // 0x71
	private const UriKind DotNetRelativeOrAbsolute; // 0x0
	internal static readonly Boolean IsWindowsFileSystem; // 0x72
	private static Object s_initLock; // 0x78
	private const UriFormat V1ToStringUnescape; // 0x0
	internal const Char c_DummyChar; // 0x0
	internal const Char c_EOL; // 0x0
	internal static readonly Char[] HexLowerChars; // 0x80
	private static readonly Char[] _WSchars; // 0x88

	private Boolean IsImplicitFile { get; }
	private Boolean IsUncOrDosPath { get; }
	private Boolean IsDosPath { get; }
	private Boolean IsUncPath { get; }
	private Flags HostType { get; }
	private UriParser Syntax { get; }
	private Boolean IsNotAbsoluteUri { get; }
	private Boolean AllowIdn { get; }
	internal Boolean UserDrivenParsing { get; }
	private UInt16 SecuredPathIndex { get; }
	public String AbsolutePath { get; }
	private String PrivateAbsolutePath { get; }
	public String AbsoluteUri { get; }
	public String LocalPath { get; }
	public String Authority { get; }
	public UriHostNameType HostNameType { get; }
	public Boolean IsDefaultPort { get; }
	public Boolean IsFile { get; }
	public Boolean IsLoopback { get; }
	public String PathAndQuery { get; }
	public String[] Segments { get; }
	public Boolean IsUnc { get; }
	public String Host { get; }
	private static Object InitializeLock { get; }
	public Int32 Port { get; }
	public String Query { get; }
	public String Fragment { get; }
	public String Scheme { get; }
	private Boolean OriginalStringSwitched { get; }
	public String OriginalString { get; }
	public String DnsSafeHost { get; }
	public Boolean IsAbsoluteUri { get; }
	public Boolean UserEscaped { get; }
	public String UserInfo { get; }
	internal Boolean HasAuthority { get; }

	// RVA: 0x6314d10 VA: 0x759892cd10
	private Boolean get_IsImplicitFile() { }
	// RVA: 0x6314d1c VA: 0x759892cd1c
	private Boolean get_IsUncOrDosPath() { }
	// RVA: 0x6314d2c VA: 0x759892cd2c
	private Boolean get_IsDosPath() { }
	// RVA: 0x6314d38 VA: 0x759892cd38
	private Boolean get_IsUncPath() { }
	// RVA: 0x6314d44 VA: 0x759892cd44
	private Flags get_HostType() { }
	// RVA: 0x6314d50 VA: 0x759892cd50
	private UriParser get_Syntax() { }
	// RVA: 0x6314d58 VA: 0x759892cd58
	private Boolean get_IsNotAbsoluteUri() { }
	// RVA: 0x6314d68 VA: 0x759892cd68
	internal static Boolean IriParsingStatic(UriParser syntax) { }
	// RVA: 0x6314df4 VA: 0x759892cdf4
	private Boolean get_AllowIdn() { }
	// RVA: 0x6314ec0 VA: 0x759892cec0
	private Boolean AllowIdnStatic(UriParser syntax, Flags flags) { }
	// RVA: 0x6314f94 VA: 0x759892cf94
	private Boolean IsIntranet(String schemeHost) { }
	// RVA: 0x6314f9c VA: 0x759892cf9c
	internal Boolean get_UserDrivenParsing() { }
	// RVA: 0x6314fa8 VA: 0x759892cfa8
	private Void SetUserDrivenParsing() { }
	// RVA: 0x6314fbc VA: 0x759892cfbc
	private UInt16 get_SecuredPathIndex() { }
	// RVA: 0x6314eb0 VA: 0x759892ceb0
	private Boolean NotAny(Flags flags) { }
	// RVA: 0x6315018 VA: 0x759892d018
	private Boolean InFact(Flags flags) { }
	// RVA: 0x6314f88 VA: 0x759892cf88
	private static Boolean StaticNotAny(Flags allFlags, Flags checkFlags) { }
	// RVA: 0x6315028 VA: 0x759892d028
	private static Boolean StaticInFact(Flags allFlags, Flags checkFlags) { }
	// RVA: 0x6315034 VA: 0x759892d034
	private UriInfo EnsureUriInfo() { }
	// RVA: 0x631560c VA: 0x759892d60c
	private Void EnsureParseRemaining() { }
	// RVA: 0x631623c VA: 0x759892e23c
	private Void EnsureHostString(Boolean allowDnsOptimization) { }
	// RVA: 0x63166ac VA: 0x759892e6ac
	public Void .ctor(String uriString) { }
	// RVA: 0x6316900 VA: 0x759892e900
	public Void .ctor(String uriString, UriKind uriKind) { }
	// RVA: 0x6316988 VA: 0x759892e988
	public Void .ctor(Uri baseUri, String relativeUri) { }
	// RVA: 0x6316a60 VA: 0x759892ea60
	private Void CreateUri(Uri baseUri, String relativeUri, Boolean dontEscape) { }
	// RVA: 0x6317270 VA: 0x759892f270
	public Void .ctor(Uri baseUri, Uri relativeUri) { }
	// RVA: 0x63174a8 VA: 0x759892f4a8
	private static ParsingError GetCombinedString(Uri baseUri, String relativeStr, Boolean dontEscape, ref String result) { }
	// RVA: 0x63183a4 VA: 0x75989303a4
	private static UriFormatException GetException(ParsingError err) { }
	// RVA: 0x6318544 VA: 0x7598930544
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6318648 VA: 0x7598930648
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x631864c VA: 0x759893064c
	protected Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6318728 VA: 0x7598930728
	public String get_AbsolutePath() { }
	// RVA: 0x63187f0 VA: 0x75989307f0
	private String get_PrivateAbsolutePath() { }
	// RVA: 0x63188c0 VA: 0x75989308c0
	public String get_AbsoluteUri() { }
	// RVA: 0x63189ec VA: 0x75989309ec
	public String get_LocalPath() { }
	// RVA: 0x6319054 VA: 0x7598931054
	public String get_Authority() { }
	// RVA: 0x63190d0 VA: 0x75989310d0
	public UriHostNameType get_HostNameType() { }
	// RVA: 0x63191d0 VA: 0x75989311d0
	public Boolean get_IsDefaultPort() { }
	// RVA: 0x6319280 VA: 0x7598931280
	public Boolean get_IsFile() { }
	// RVA: 0x6319348 VA: 0x7598931348
	public Boolean get_IsLoopback() { }
	// RVA: 0x63193d0 VA: 0x75989313d0
	public String get_PathAndQuery() { }
	// RVA: 0x63194a0 VA: 0x75989314a0
	public String[] get_Segments() { }
	// RVA: 0x63196b0 VA: 0x75989316b0
	public Boolean get_IsUnc() { }
	// RVA: 0x631972c VA: 0x759893172c
	public String get_Host() { }
	// RVA: 0x63197a8 VA: 0x75989317a8
	private static Boolean StaticIsFile(UriParser syntax) { }
	// RVA: 0x63197c0 VA: 0x75989317c0
	private static Object get_InitializeLock() { }
	// RVA: 0x6319894 VA: 0x7598931894
	private static Void InitializeUriConfig() { }
	// RVA: 0x6318a60 VA: 0x7598930a60
	private String GetLocalPath() { }
	// RVA: 0x6319fdc VA: 0x7598931fdc
	public Int32 get_Port() { }
	// RVA: 0x631a0a8 VA: 0x75989320a8
	public String get_Query() { }
	// RVA: 0x631a1d8 VA: 0x75989321d8
	public String get_Fragment() { }
	// RVA: 0x631a308 VA: 0x7598932308
	public String get_Scheme() { }
	// RVA: 0x631a380 VA: 0x7598932380
	private Boolean get_OriginalStringSwitched() { }
	// RVA: 0x6317850 VA: 0x759892f850
	public String get_OriginalString() { }
	// RVA: 0x631a3c8 VA: 0x75989323c8
	public String get_DnsSafeHost() { }
	// RVA: 0x6316a50 VA: 0x759892ea50
	public Boolean get_IsAbsoluteUri() { }
	// RVA: 0x631a624 VA: 0x7598932624
	public Boolean get_UserEscaped() { }
	// RVA: 0x631a630 VA: 0x7598932630
	public String get_UserInfo() { }
	// RVA: 0x631a6ac VA: 0x75989326ac
	internal static Boolean IsGenDelim(Char ch) { }
	// RVA: 0x631a6f8 VA: 0x75989326f8
	public static Boolean CheckSchemeName(String schemeName) { }
	// RVA: 0x631a8e0 VA: 0x75989328e0
	public static Boolean IsHexDigit(Char character) { }
	// RVA: 0x631a91c VA: 0x759893291c
	public static Int32 FromHex(Char digit) { }
	// RVA: 0x631a9cc VA: 0x75989329cc
	public override Int32 GetHashCode() { }
	// RVA: 0x631abb8 VA: 0x7598932bb8
	public override String ToString() { }
	// RVA: 0x631aea8 VA: 0x7598932ea8
	public static Boolean op_Equality(Uri uri1, Uri uri2) { }
	// RVA: 0x63170d4 VA: 0x759892f0d4
	public static Boolean op_Inequality(Uri uri1, Uri uri2) { }
	// RVA: 0x631aedc VA: 0x7598932edc
	public override Boolean Equals(Object comparand) { }
	// RVA: 0x631b5ac VA: 0x75989335ac
	internal static String InternalEscapeString(String rawString) { }
	// RVA: 0x631b68c VA: 0x759893368c
	private static ParsingError ParseScheme(String uriString, ref Flags flags, ref UriParser syntax) { }
	// RVA: 0x631bce0 VA: 0x7598933ce0
	internal UriFormatException ParseMinimal() { }
	// RVA: 0x631bd60 VA: 0x7598933d60
	private ParsingError PrivateParseMinimal() { }
	// RVA: 0x631d24c VA: 0x759893524c
	private Void PrivateParseMinimalIri(String newHost, UInt16 idx) { }
	// RVA: 0x6315058 VA: 0x759892d058
	private Void CreateUriInfo(Flags cF) { }
	// RVA: 0x631629c VA: 0x759892e29c
	private Void CreateHostString() { }
	// RVA: 0x631d788 VA: 0x7598935788
	private static String CreateHostStringHelper(String str, UInt16 idx, UInt16 end, ref Flags flags, ref String scopeId) { }
	// RVA: 0x631d340 VA: 0x7598935340
	private Void GetHostViaCustomSyntax() { }
	// RVA: 0x6318724 VA: 0x7598930724
	internal String GetParts(UriComponents uriParts, UriFormat formatAs) { }
	// RVA: 0x631df40 VA: 0x7598935f40
	private String GetEscapedParts(UriComponents uriParts) { }
	// RVA: 0x6319f0c VA: 0x7598931f0c
	private String GetUnescapedParts(UriComponents uriParts, UriFormat formatAs) { }
	// RVA: 0x631e5b8 VA: 0x75989365b8
	private String ReCreateParts(UriComponents parts, UInt16 nonCanonical, UriFormat formatAs) { }
	// RVA: 0x631e008 VA: 0x7598936008
	private String GetUriPartsFromUserString(UriComponents uriParts) { }
	// RVA: 0x631561c VA: 0x759892d61c
	private Void ParseRemaining() { }
	// RVA: 0x631b76c VA: 0x759893376c
	private static UInt16 ParseSchemeCheckImplicitFile(Char* uriString, UInt16 length, ref ParsingError err, ref Flags flags, ref UriParser syntax) { }
	// RVA: 0x631f950 VA: 0x7598937950
	private static Boolean CheckKnownSchemes(Int64* lptr, UInt16 nChars, ref UriParser syntax) { }
	// RVA: 0x6317714 VA: 0x759892f714
	private static ParsingError CheckSchemeSyntax(Char* ptr, UInt16 length, ref UriParser syntax) { }
	// RVA: 0x631c408 VA: 0x7598934408
	private UInt16 CheckAuthorityHelper(Char* pString, UInt16 idx, UInt16 length, ref ParsingError err, ref Flags flags, UriParser syntax, ref String newHost) { }
	// RVA: 0x631fe58 VA: 0x7598937e58
	private Void CheckAuthorityHelperHandleDnsIri(Char* pString, UInt16 start, Int32 end, Int32 startInput, Boolean iriParsing, Boolean hasUnicode, UriParser syntax, String userInfoString, ref Flags flags, ref Boolean justNormalized, ref String newHost, ref ParsingError err) { }
	// RVA: 0x63201ec VA: 0x75989381ec
	private Void CheckAuthorityHelperHandleAnyHostIri(Char* pString, Int32 startInput, Int32 end, Boolean iriParsing, Boolean hasUnicode, UriParser syntax, ref Flags flags, ref String newHost, ref ParsingError err) { }
	// RVA: 0x631f8ac VA: 0x75989378ac
	private Void FindEndOfComponent(String input, ref UInt16 idx, UInt16 end, Char delim) { }
	// RVA: 0x6320678 VA: 0x7598938678
	private Void FindEndOfComponent(Char* str, ref UInt16 idx, UInt16 end, Char delim) { }
	// RVA: 0x631d96c VA: 0x759893596c
	private Check CheckCanonical(Char* str, ref UInt16 idx, UInt16 end, Char delim) { }
	// RVA: 0x631f244 VA: 0x7598937244
	private Char[] GetCanonicalPath(Char[] dest, ref Int32 pos, UriFormat formatAs) { }
	// RVA: 0x632070c VA: 0x759893870c
	private static Void UnescapeOnly(Char* pch, Int32 start, ref Int32 end, Char ch1, Char ch2, Char ch3) { }
	// RVA: 0x6319a34 VA: 0x7598931a34
	private static Char[] Compress(Char[] dest, UInt16 start, ref Int32 destLength, UriParser syntax) { }
	// RVA: 0x631ab18 VA: 0x7598932b18
	internal static Int32 CalculateCaseInsensitiveHashCode(String text) { }
	// RVA: 0x6317878 VA: 0x759892f878
	private static String CombineUri(Uri basePart, String relativePart, UriFormat uriFormat) { }
	// RVA: 0x6320928 VA: 0x7598938928
	internal Boolean get_HasAuthority() { }
	// RVA: 0x631c3c8 VA: 0x75989343c8
	private static Boolean IsLWS(Char ch) { }
	// RVA: 0x631a838 VA: 0x7598932838
	private static Boolean IsAsciiLetter(Char character) { }
	// RVA: 0x631a864 VA: 0x7598932864
	internal static Boolean IsAsciiLetterOrDigit(Char character) { }
	// RVA: 0x6320934 VA: 0x7598938934
	internal static Boolean IsBidiControlCharacter(Char ch) { }
	// RVA: 0x6320500 VA: 0x7598938500
	internal static String StripBidiControlCharacter(Char* strToClean, Int32 start, Int32 length) { }
	// RVA: 0x6316730 VA: 0x759892e730
	private Void CreateThis(String uri, Boolean dontEscape, UriKind uriKind) { }
	// RVA: 0x632097c VA: 0x759893897c
	private Void InitializeUri(ParsingError err, UriKind uriKind, out UriFormatException e) { }
	// RVA: 0x6320f18 VA: 0x7598938f18
	private Boolean CheckForConfigLoad(String data) { }
	// RVA: 0x6320fc4 VA: 0x7598938fc4
	private Boolean CheckForUnicode(String data) { }
	// RVA: 0x63210dc VA: 0x75989390dc
	private Boolean CheckForEscapedUnreserved(String data) { }
	// RVA: 0x631b4dc VA: 0x75989334dc
	public static Boolean TryCreate(String uriString, UriKind uriKind, out Uri result) { }
	// RVA: 0x63214fc VA: 0x75989394fc
	public static Boolean TryCreate(Uri baseUri, String relativeUri, out Uri result) { }
	// RVA: 0x63215e4 VA: 0x75989395e4
	public static Boolean TryCreate(Uri baseUri, Uri relativeUri, out Uri result) { }
	// RVA: 0x631dd64 VA: 0x7598935d64
	public String GetComponents(UriComponents components, UriFormat format) { }
	// RVA: 0x632199c VA: 0x759893999c
	public static Int32 Compare(Uri uri1, Uri uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType) { }
	// RVA: 0x6321ac0 VA: 0x7598939ac0
	public static String UnescapeDataString(String stringToUnescape) { }
	// RVA: 0x6321c68 VA: 0x7598939c68
	public static String EscapeUriString(String stringToEscape) { }
	// RVA: 0x6321d98 VA: 0x7598939d98
	public static String EscapeDataString(String stringToEscape) { }
	// RVA: 0x631f900 VA: 0x7598937900
	internal String EscapeUnescapeIri(String input, Int32 start, Int32 end, UriComponents component) { }
	// RVA: 0x6321ec8 VA: 0x7598939ec8
	private Void .ctor(Flags flags, UriParser uriParser, String uri) { }
	// RVA: 0x6321288 VA: 0x7598939288
	internal static Uri CreateHelper(String uriString, Boolean dontEscape, UriKind uriKind, ref UriFormatException e) { }
	// RVA: 0x6316bfc VA: 0x759892ebfc
	internal static Uri ResolveHelper(Uri baseUri, Uri relativeUri, ref String newUriString, ref Boolean userEscaped, out UriFormatException e) { }
	// RVA: 0x632177c VA: 0x759893977c
	private String GetRelativeSerializationString(UriFormat format) { }
	// RVA: 0x631ac90 VA: 0x7598932c90
	internal String GetComponentsHelper(UriComponents uriComponents, UriFormat uriFormat) { }
	// RVA: 0x6321f1c VA: 0x7598939f1c
	public Boolean IsBaseOf(Uri uri) { }
	// RVA: 0x6321fd4 VA: 0x7598939fd4
	internal Boolean IsBaseOfHelper(Uri uriLink) { }
	// RVA: 0x631711c VA: 0x759892f11c
	private Void CreateThisFromUri(Uri otherUri) { }
	// RVA: 0x63221d8 VA: 0x759893a1d8
	private static Void .cctor() { }
}
```