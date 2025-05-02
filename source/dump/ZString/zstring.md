# zstring

**Namespace:** `ZString`


## Fields

- `Boolean isShallow`

- `String _value`

- `Boolean _disposed`


## Properties

- `Int32 Length`

- `Char Item`


## Methods

- `Void dispose()`

- `Int32 get_Length()`

- `String Intern()`

- `Char get_Item(Int32)`

- `Void set_Item(Int32, Char)`

- `zstring ToUpper()`

- `zstring ToLower()`

- `zstring Remove(Int32)`

- `zstring Remove(Int32, Int32)`

- `zstring Insert(Char, Int32, Int32)`

- `zstring Insert(String, Int32)`

- `zstring Replace(Char, Char)`

- `zstring Replace(String, String)`

- `zstring Substring(Int32)`

- `zstring Substring(Int32, Int32)`

- `Boolean Contains(String)`

- `Boolean Contains(Char)`

- `Int32 LastIndexOf(String)`

- `Int32 LastIndexOf(Char)`

- `Int32 IndexOf(Char)`

- `Int32 IndexOf(Char, Int32)`

- `Int32 IndexOf(Char, Int32, Int32)`

- `Int32 IndexOf(String)`

- `Int32 IndexOf(String, Int32)`

- `Int32 IndexOf(String, Int32, Int32)`

- `Boolean EndsWith(String)`

- `Boolean StartsWith(String)`

- `zstring Concat(zstring)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : ZString
public class zstring
{
	private static Queue`1[] g_cache; // 0x0
	private static Dictionary`2 g_secCache; // 0x8
	private static Stack`1 g_shallowCache; // 0x10
	private static Stack`1 g_blocks; // 0x18
	private static Stack`1 g_open_blocks; // 0x20
	private static Dictionary`2 g_intern_table; // 0x28
	public static zstring_block g_current_block; // 0x30
	private static List`1 g_finds; // 0x38
	private static zstring[] g_format_args; // 0x40
	private static Boolean g_isInited; // 0x48
	private const Int32 INITIAL_BLOCK_CAPACITY; // 0x0
	private const Int32 INITIAL_CACHE_CAPACITY; // 0x0
	private const Int32 INITIAL_STACK_CAPACITY; // 0x0
	private const Int32 INITIAL_INTERN_CAPACITY; // 0x0
	private const Int32 INITIAL_OPEN_CAPACITY; // 0x0
	private const Int32 INITIAL_SHALLOW_CAPACITY; // 0x0
	private const Char NEW_ALLOC_CHAR; // 0x0
	private Boolean isShallow; // 0x10
	private String _value; // 0x18
	private Boolean _disposed; // 0x20
	private static Int32 m_charLen; // 0x4c
	public static UInt32 DecimalAccuracy; // 0x50

	public Int32 Length { get; }
	public Char Item { get; set; }

	// RVA: 0x6468ab4 VA: 0x7598a80ab4
	private Void .ctor() { }
	// RVA: 0x6468afc VA: 0x7598a80afc
	private Void .ctor(Int32 length) { }
	// RVA: 0x6468b40 VA: 0x7598a80b40
	private Void .ctor(String value, Boolean shallow) { }
	// RVA: 0x6468bc0 VA: 0x7598a80bc0
	private static Void .cctor() { }
	// RVA: 0x646914c VA: 0x7598a8114c
	private Void dispose() { }
	// RVA: 0x6469328 VA: 0x7598a81328
	private static zstring get(String value) { }
	// RVA: 0x6469608 VA: 0x7598a81608
	private static zstring getShallow(String value) { }
	// RVA: 0x64697fc VA: 0x7598a817fc
	private static String __intern(String value) { }
	// RVA: 0x6469964 VA: 0x7598a81964
	private static Void getStackInCache(Int32 index, out Queue`1 outStack) { }
	// RVA: 0x64693ac VA: 0x7598a813ac
	private static zstring get(Int32 length) { }
	// RVA: 0x6469b00 VA: 0x7598a81b00
	private static Int32 get_digit_count(Int64 value) { }
	// RVA: 0x6469b3c VA: 0x7598a81b3c
	private static UInt32 get_digit_count(UInt32 value) { }
	// RVA: 0x6469b74 VA: 0x7598a81b74
	private static Int32 get_digit_count(Int32 value) { }
	// RVA: 0x6469bb4 VA: 0x7598a81bb4
	private static Int32 internal_index_of(String input, Char value, Int32 start) { }
	// RVA: 0x6469cb4 VA: 0x7598a81cb4
	private static Int32 internal_index_of(String input, String value) { }
	// RVA: 0x6469f34 VA: 0x7598a81f34
	private static Int32 internal_index_of(String input, String value, Int32 start) { }
	// RVA: 0x6469fb0 VA: 0x7598a81fb0
	private static zstring internal_format(String input, Int32 num_args) { }
	// RVA: 0x6469c30 VA: 0x7598a81c30
	private static Int32 internal_index_of(String input, Char value, Int32 start, Int32 count) { }
	// RVA: 0x6469d24 VA: 0x7598a81d24
	private static Int32 internal_index_of(String input, String value, Int32 start, Int32 count) { }
	// RVA: 0x646a42c VA: 0x7598a8242c
	private static zstring internal_remove(String input, Int32 start, Int32 count) { }
	// RVA: 0x646a794 VA: 0x7598a82794
	private static Void internal_remove(String dst, String src, Int32 start, Int32 count) { }
	// RVA: 0x646a834 VA: 0x7598a82834
	private static zstring internal_replace(String value, String old_value, String new_value) { }
	// RVA: 0x646ac58 VA: 0x7598a82c58
	private static zstring internal_insert(String value, Char to_insert, Int32 start, Int32 count) { }
	// RVA: 0x646ae84 VA: 0x7598a82e84
	private static zstring internal_insert(String input, String to_insert, Int32 start) { }
	// RVA: 0x646b158 VA: 0x7598a83158
	private static zstring internal_concat(String s1, String s2) { }
	// RVA: 0x646b070 VA: 0x7598a83070
	private static Void internal_insert(String dst, String src, String to_insert, Int32 start) { }
	// RVA: 0x646b2c8 VA: 0x7598a832c8
	private static Void longcpy(Char* dst, Int64 value, Int32 start, Int32 count) { }
	// RVA: 0x646b310 VA: 0x7598a83310
	private static Void intcpy(Char* dst, Int32 value, Int32 start, Int32 count) { }
	// RVA: 0x646b35c VA: 0x7598a8335c
	private static Void _memcpy4(Byte* dest, Byte* src, Int32 size) { }
	// RVA: 0x646b3e8 VA: 0x7598a833e8
	private static Void _memcpy2(Byte* dest, Byte* src, Int32 size) { }
	// RVA: 0x646b464 VA: 0x7598a83464
	private static Void memcpy(Char* dest, Char* src, Int32 count) { }
	// RVA: 0x646b4dc VA: 0x7598a834dc
	private static Void byteMemcpy(Byte* dest, Byte* src, Int32 byteCount) { }
	// RVA: 0x646b55c VA: 0x7598a8355c
	private static Void memcpy(String dst, Char src) { }
	// RVA: 0x646b5a4 VA: 0x7598a835a4
	private static Void memcpy(String dst, Char src, Int32 index) { }
	// RVA: 0x6469518 VA: 0x7598a81518
	private static Void memcpy(String dst, String src) { }
	// RVA: 0x646b250 VA: 0x7598a83250
	private static Void memcpy(Char* dst, Char* src, Int32 length, Int32 src_offset) { }
	// RVA: 0x646b5d8 VA: 0x7598a835d8
	private static Void memcpy(String dst, String src, Int32 length, Int32 src_offset) { }
	// RVA: 0x646930c VA: 0x7598a8130c
	public Int32 get_Length() { }
	// RVA: 0x6468cc0 VA: 0x7598a80cc0
	public static Void Initialize(Int32 cache_capacity, Int32 stack_capacity, Int32 block_capacity, Int32 intern_capacity, Int32 open_capacity, Int32 shallowCache_capacity) { }
	// RVA: 0x646b700 VA: 0x7598a83700
	public static Void Reset() { }
	// RVA: 0x646ba7c VA: 0x7598a83a7c
	public static IDisposable Block() { }
	// RVA: 0x646bbe8 VA: 0x7598a83be8
	public String Intern() { }
	// RVA: 0x646bc40 VA: 0x7598a83c40
	public static String Intern(String value) { }
	// RVA: 0x646bc94 VA: 0x7598a83c94
	public static Void Intern(String[] values) { }
	// RVA: 0x646bd34 VA: 0x7598a83d34
	public Char get_Item(Int32 i) { }
	// RVA: 0x646bd50 VA: 0x7598a83d50
	public Void set_Item(Int32 i, Char value) { }
	// RVA: 0x646bdd0 VA: 0x7598a83dd0
	public override Int32 GetHashCode() { }
	// RVA: 0x646bdf0 VA: 0x7598a83df0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x646be90 VA: 0x7598a83e90
	public override String ToString() { }
	// RVA: 0x646be98 VA: 0x7598a83e98
	public static zstring op_Implicit(Boolean value) { }
	// RVA: 0x646bf28 VA: 0x7598a83f28
	public static zstring op_Implicit(Int64 value) { }
	// RVA: 0x646c100 VA: 0x7598a84100
	public static zstring op_Implicit(Int32 value) { }
	// RVA: 0x646c2e4 VA: 0x7598a842e4
	public static zstring op_Implicit(Single value) { }
	// RVA: 0x646a740 VA: 0x7598a82740
	public static zstring op_Implicit(String value) { }
	// RVA: 0x646c6b0 VA: 0x7598a846b0
	public static zstring shallow(String value) { }
	// RVA: 0x646c704 VA: 0x7598a84704
	public static String op_Implicit(zstring value) { }
	// RVA: 0x646c71c VA: 0x7598a8471c
	public static zstring op_Addition(zstring left, zstring right) { }
	// RVA: 0x646c78c VA: 0x7598a8478c
	public static Boolean op_Equality(zstring left, zstring right) { }
	// RVA: 0x646be60 VA: 0x7598a83e60
	public static Boolean op_Inequality(zstring left, zstring right) { }
	// RVA: 0x646c7b8 VA: 0x7598a847b8
	public zstring ToUpper() { }
	// RVA: 0x646c914 VA: 0x7598a84914
	public zstring ToLower() { }
	// RVA: 0x646ca70 VA: 0x7598a84a70
	public zstring Remove(Int32 start) { }
	// RVA: 0x646ca90 VA: 0x7598a84a90
	public zstring Remove(Int32 start, Int32 count) { }
	// RVA: 0x646cb00 VA: 0x7598a84b00
	public zstring Insert(Char value, Int32 start, Int32 count) { }
	// RVA: 0x646cb80 VA: 0x7598a84b80
	public zstring Insert(String value, Int32 start) { }
	// RVA: 0x646cbf0 VA: 0x7598a84bf0
	public zstring Replace(Char old_value, Char new_value) { }
	// RVA: 0x646cce0 VA: 0x7598a84ce0
	public zstring Replace(String old_value, String new_value) { }
	// RVA: 0x646cd50 VA: 0x7598a84d50
	public zstring Substring(Int32 start) { }
	// RVA: 0x646cd70 VA: 0x7598a84d70
	public zstring Substring(Int32 start, Int32 count) { }
	// RVA: 0x646ced0 VA: 0x7598a84ed0
	public Boolean Contains(String value) { }
	// RVA: 0x646cf08 VA: 0x7598a84f08
	public Boolean Contains(Char value) { }
	// RVA: 0x646cf40 VA: 0x7598a84f40
	public Int32 LastIndexOf(String value) { }
	// RVA: 0x646cff4 VA: 0x7598a84ff4
	public Int32 LastIndexOf(Char value) { }
	// RVA: 0x646cf20 VA: 0x7598a84f20
	public Int32 IndexOf(Char value) { }
	// RVA: 0x646d114 VA: 0x7598a85114
	public Int32 IndexOf(Char value, Int32 start) { }
	// RVA: 0x646d094 VA: 0x7598a85094
	public Int32 IndexOf(Char value, Int32 start, Int32 count) { }
	// RVA: 0x646cee8 VA: 0x7598a84ee8
	public Int32 IndexOf(String value) { }
	// RVA: 0x646d204 VA: 0x7598a85204
	public Int32 IndexOf(String value, Int32 start) { }
	// RVA: 0x646d184 VA: 0x7598a85184
	public Int32 IndexOf(String value, Int32 start, Int32 count) { }
	// RVA: 0x646d224 VA: 0x7598a85224
	public Boolean EndsWith(String postfix) { }
	// RVA: 0x646d310 VA: 0x7598a85310
	public Boolean StartsWith(String prefix) { }
	// RVA: 0x646d3f8 VA: 0x7598a853f8
	public static Int32 GetCacheCount(Int32 length) { }
	// RVA: 0x646d47c VA: 0x7598a8547c
	public zstring Concat(zstring value) { }
	// RVA: 0x646d4ec VA: 0x7598a854ec
	public static zstring Concat(zstring s0, zstring s1) { }
	// RVA: 0x646d550 VA: 0x7598a85550
	public static zstring Concat(zstring s0, zstring s1, zstring s2) { }
	// RVA: 0x646d5c0 VA: 0x7598a855c0
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3) { }
	// RVA: 0x646d644 VA: 0x7598a85644
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3, zstring s4) { }
	// RVA: 0x646d6d4 VA: 0x7598a856d4
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3, zstring s4, zstring s5) { }
	// RVA: 0x646d778 VA: 0x7598a85778
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3, zstring s4, zstring s5, zstring s6) { }
	// RVA: 0x646d828 VA: 0x7598a85828
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3, zstring s4, zstring s5, zstring s6, zstring s7) { }
	// RVA: 0x646d8ec VA: 0x7598a858ec
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3, zstring s4, zstring s5, zstring s6, zstring s7, zstring s8) { }
	// RVA: 0x646d9bc VA: 0x7598a859bc
	public static zstring Concat(zstring s0, zstring s1, zstring s2, zstring s3, zstring s4, zstring s5, zstring s6, zstring s7, zstring s8, zstring s9) { }
	// RVA: 0x646daa0 VA: 0x7598a85aa0
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3, zstring arg4, zstring arg5, zstring arg6, zstring arg7, zstring arg8, zstring arg9) { }
	// RVA: 0x646e02c VA: 0x7598a8602c
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3, zstring arg4, zstring arg5, zstring arg6, zstring arg7, zstring arg8) { }
	// RVA: 0x646e538 VA: 0x7598a86538
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3, zstring arg4, zstring arg5, zstring arg6, zstring arg7) { }
	// RVA: 0x646e9c4 VA: 0x7598a869c4
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3, zstring arg4, zstring arg5, zstring arg6) { }
	// RVA: 0x646edd4 VA: 0x7598a86dd4
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3, zstring arg4, zstring arg5) { }
	// RVA: 0x646f160 VA: 0x7598a87160
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3, zstring arg4) { }
	// RVA: 0x646f470 VA: 0x7598a87470
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2, zstring arg3) { }
	// RVA: 0x646f6fc VA: 0x7598a876fc
	public static zstring Format(String input, zstring arg0, zstring arg1, zstring arg2) { }
	// RVA: 0x646f90c VA: 0x7598a8790c
	public static zstring Format(String input, zstring arg0, zstring arg1) { }
	// RVA: 0x646fa98 VA: 0x7598a87a98
	public static zstring Format(String input, zstring arg0) { }
	// RVA: 0x646fba8 VA: 0x7598a87ba8
	public static zstring FloatToZstring(Single value, UInt32 DecimalAccuracy) { }
	// RVA: 0x646fc28 VA: 0x7598a87c28
	public static Boolean IsNullOrEmpty(zstring str) { }
	// RVA: 0x646fca0 VA: 0x7598a87ca0
	public static Boolean IsPrefix(zstring str, String value) { }
	// RVA: 0x646fcb0 VA: 0x7598a87cb0
	public static Boolean isPostfix(zstring str, String postfix) { }
}
```