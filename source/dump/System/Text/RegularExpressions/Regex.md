# Regex

**Namespace:** `System.Text.RegularExpressions`


## Properties

- `RegexOptions Options`

- `Boolean RightToLeft`


## Methods

- `CachedCodeEntry GetCachedCode(CachedCodeEntryKey, Boolean)`

- `CachedCodeEntry GetCachedCodeEntryInternal(CachedCodeEntryKey, Boolean)`

- `Void FillCacheDictionary()`

- `Boolean IsMatch(String)`

- `Boolean IsMatch(String, Int32)`

- `Match Match(String)`

- `Match Match(String, Int32)`

- `MatchCollection Matches(String, Int32)`

- `String Replace(String, String)`

- `String Replace(String, String, Int32, Int32)`

- `RegexOptions get_Options()`

- `Boolean get_RightToLeft()`

- `String GroupNameFromNumber(Int32)`

- `Int32 GroupNumberFromName(String)`

- `Void InitializeReferences()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class Regex : ISerializable
{
	private const Int32 CacheDictionarySwitchLimit; // 0x0
	private static Int32 s_cacheSize; // 0x0
	private static readonly Dictionary`2 s_cache; // 0x8
	private static Int32 s_cacheCount; // 0x10
	private static CachedCodeEntry s_cacheFirst; // 0x18
	private static CachedCodeEntry s_cacheLast; // 0x20
	private static readonly TimeSpan s_maximumMatchTimeout; // 0x28
	private const String DefaultMatchTimeout_ConfigKeyName; // 0x0
	internal static readonly TimeSpan s_defaultMatchTimeout; // 0x30
	public static readonly TimeSpan InfiniteMatchTimeout; // 0x38
	protected internal TimeSpan internalMatchTimeout; // 0x10
	internal const Int32 MaxOptionShift; // 0x0
	protected internal String pattern; // 0x18
	protected internal RegexOptions roptions; // 0x20
	protected internal RegexRunnerFactory factory; // 0x28
	protected internal Hashtable caps; // 0x30
	protected internal Hashtable capnames; // 0x38
	protected internal String[] capslist; // 0x40
	protected internal Int32 capsize; // 0x48
	internal ExclusiveReference _runnerref; // 0x50
	internal WeakReference`1 _replref; // 0x58
	internal RegexCode _code; // 0x60
	internal Boolean _refsInitialized; // 0x68

	public RegexOptions Options { get; }
	public Boolean RightToLeft { get; }

	// RVA: 0x63798dc VA: 0x75989918dc
	private CachedCodeEntry GetCachedCode(CachedCodeEntryKey key, Boolean isToAdd) { }
	// RVA: 0x6379a04 VA: 0x7598991a04
	private CachedCodeEntry GetCachedCodeEntryInternal(CachedCodeEntryKey key, Boolean isToAdd) { }
	// RVA: 0x637a2bc VA: 0x75989922bc
	private Void FillCacheDictionary() { }
	// RVA: 0x637a3c0 VA: 0x75989923c0
	private static Boolean TryGetCacheValue(CachedCodeEntryKey key, out CachedCodeEntry entry) { }
	// RVA: 0x637a4dc VA: 0x75989924dc
	private static Boolean TryGetCacheValueSmall(CachedCodeEntryKey key, out CachedCodeEntry entry) { }
	// RVA: 0x6379f00 VA: 0x7598991f00
	private static CachedCodeEntry LookupCachedAndPromote(CachedCodeEntryKey key) { }
	// RVA: 0x637a5b8 VA: 0x75989925b8
	public static Boolean IsMatch(String input, String pattern) { }
	// RVA: 0x637a62c VA: 0x759899262c
	public static Boolean IsMatch(String input, String pattern, RegexOptions options, TimeSpan matchTimeout) { }
	// RVA: 0x637ab38 VA: 0x7598992b38
	public Boolean IsMatch(String input) { }
	// RVA: 0x637abb4 VA: 0x7598992bb4
	public Boolean IsMatch(String input, Int32 startat) { }
	// RVA: 0x637ac34 VA: 0x7598992c34
	public static Match Match(String input, String pattern) { }
	// RVA: 0x637aca8 VA: 0x7598992ca8
	public static Match Match(String input, String pattern, RegexOptions options, TimeSpan matchTimeout) { }
	// RVA: 0x637ad34 VA: 0x7598992d34
	public Match Match(String input) { }
	// RVA: 0x637ada4 VA: 0x7598992da4
	public Match Match(String input, Int32 startat) { }
	// RVA: 0x637ae18 VA: 0x7598992e18
	public MatchCollection Matches(String input, Int32 startat) { }
	// RVA: 0x637aeec VA: 0x7598992eec
	public static String Replace(String input, String pattern, String replacement) { }
	// RVA: 0x637af68 VA: 0x7598992f68
	public static String Replace(String input, String pattern, String replacement, RegexOptions options, TimeSpan matchTimeout) { }
	// RVA: 0x637affc VA: 0x7598992ffc
	public String Replace(String input, String replacement) { }
	// RVA: 0x637b070 VA: 0x7598993070
	public String Replace(String input, String replacement, Int32 count, Int32 startat) { }
	// RVA: 0x637b150 VA: 0x7598993150
	public static String[] Split(String input, String pattern) { }
	// RVA: 0x637b1c4 VA: 0x75989931c4
	public static String[] Split(String input, String pattern, RegexOptions options, TimeSpan matchTimeout) { }
	// RVA: 0x637b250 VA: 0x7598993250
	public String[] Split(String input) { }
	// RVA: 0x637b2c4 VA: 0x75989932c4
	public String[] Split(String input, Int32 count, Int32 startat) { }
	// RVA: 0x637b388 VA: 0x7598993388
	private static String[] Split(Regex regex, String input, Int32 count, Int32 startat) { }
	// RVA: 0x637b9d4 VA: 0x75989939d4
	private static Void .cctor() { }
	// RVA: 0x637bd5c VA: 0x7598993d5c
	protected internal static Void ValidateMatchTimeout(TimeSpan matchTimeout) { }
	// RVA: 0x637bb1c VA: 0x7598993b1c
	private static TimeSpan InitDefaultMatchTimeout() { }
	// RVA: 0x637beb8 VA: 0x7598993eb8
	public Void .ctor(String pattern) { }
	// RVA: 0x637bf30 VA: 0x7598993f30
	public Void .ctor(String pattern, RegexOptions options) { }
	// RVA: 0x637bfac VA: 0x7598993fac
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo si, StreamingContext context) { }
	// RVA: 0x637a6b8 VA: 0x75989926b8
	private Void .ctor(String pattern, RegexOptions options, TimeSpan matchTimeout, Boolean addToCache) { }
	// RVA: 0x637c13c VA: 0x759899413c
	public RegexOptions get_Options() { }
	// RVA: 0x637b9c8 VA: 0x75989939c8
	public Boolean get_RightToLeft() { }
	// RVA: 0x637c144 VA: 0x7598994144
	public override String ToString() { }
	// RVA: 0x6376dd4 VA: 0x759898edd4
	public String GroupNameFromNumber(Int32 i) { }
	// RVA: 0x637694c VA: 0x759898e94c
	public Int32 GroupNumberFromName(String name) { }
	// RVA: 0x637c024 VA: 0x7598994024
	protected Void InitializeReferences() { }
	// RVA: 0x6377d04 VA: 0x759898fd04
	internal Match Run(Boolean quick, Int32 prevlen, String input, Int32 beginning, Int32 length, Int32 startat) { }
	// RVA: 0x637aba8 VA: 0x7598992ba8
	protected internal Boolean UseOptionR() { }
	// RVA: 0x637c14c VA: 0x759899414c
	internal Boolean UseOptionInvariant() { }
}
```