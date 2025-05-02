# EnumerationOptions

**Namespace:** `System.IO`


## Fields

- `Boolean <RecurseSubdirectories>k__BackingField`

- `Boolean <IgnoreInaccessible>k__BackingField`

- `FileAttributes <AttributesToSkip>k__BackingField`

- `MatchType <MatchType>k__BackingField`

- `MatchCasing <MatchCasing>k__BackingField`

- `Boolean <ReturnSpecialDirectories>k__BackingField`


## Properties

- `Boolean RecurseSubdirectories`

- `Boolean IgnoreInaccessible`

- `FileAttributes AttributesToSkip`

- `MatchType MatchType`

- `MatchCasing MatchCasing`

- `Boolean ReturnSpecialDirectories`


## Methods

- `Boolean get_RecurseSubdirectories()`

- `Void set_RecurseSubdirectories(Boolean)`

- `Boolean get_IgnoreInaccessible()`

- `Void set_IgnoreInaccessible(Boolean)`

- `FileAttributes get_AttributesToSkip()`

- `Void set_AttributesToSkip(FileAttributes)`

- `MatchType get_MatchType()`

- `Void set_MatchType(MatchType)`

- `MatchCasing get_MatchCasing()`

- `Boolean get_ReturnSpecialDirectories()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class EnumerationOptions
{
	private static readonly EnumerationOptions <Compatible>k__BackingField; // 0x0
	private static readonly EnumerationOptions <CompatibleRecursive>k__BackingField; // 0x8
	private static readonly EnumerationOptions <Default>k__BackingField; // 0x10
	private Boolean <RecurseSubdirectories>k__BackingField; // 0x10
	private Boolean <IgnoreInaccessible>k__BackingField; // 0x11
	private FileAttributes <AttributesToSkip>k__BackingField; // 0x14
	private MatchType <MatchType>k__BackingField; // 0x18
	private MatchCasing <MatchCasing>k__BackingField; // 0x1c
	private Boolean <ReturnSpecialDirectories>k__BackingField; // 0x20

	internal static EnumerationOptions Compatible { get; }
	private static EnumerationOptions CompatibleRecursive { get; }
	internal static EnumerationOptions Default { get; }
	public Boolean RecurseSubdirectories { get; set; }
	public Boolean IgnoreInaccessible { get; set; }
	public FileAttributes AttributesToSkip { get; set; }
	public MatchType MatchType { get; set; }
	public MatchCasing MatchCasing { get; }
	public Boolean ReturnSpecialDirectories { get; }

	// RVA: 0x6008b38 VA: 0x7598620b38
	internal static EnumerationOptions get_Compatible() { }
	// RVA: 0x6008b90 VA: 0x7598620b90
	private static EnumerationOptions get_CompatibleRecursive() { }
	// RVA: 0x6008be8 VA: 0x7598620be8
	internal static EnumerationOptions get_Default() { }
	// RVA: 0x6008c40 VA: 0x7598620c40
	public Void .ctor() { }
	// RVA: 0x6007ecc VA: 0x759861fecc
	internal static EnumerationOptions FromSearchOption(SearchOption searchOption) { }
	// RVA: 0x6008c68 VA: 0x7598620c68
	public Boolean get_RecurseSubdirectories() { }
	// RVA: 0x6008c70 VA: 0x7598620c70
	public Void set_RecurseSubdirectories(Boolean value) { }
	// RVA: 0x6008c7c VA: 0x7598620c7c
	public Boolean get_IgnoreInaccessible() { }
	// RVA: 0x6008c84 VA: 0x7598620c84
	public Void set_IgnoreInaccessible(Boolean value) { }
	// RVA: 0x6008c90 VA: 0x7598620c90
	public FileAttributes get_AttributesToSkip() { }
	// RVA: 0x6008c98 VA: 0x7598620c98
	public Void set_AttributesToSkip(FileAttributes value) { }
	// RVA: 0x6008ca0 VA: 0x7598620ca0
	public MatchType get_MatchType() { }
	// RVA: 0x6008ca8 VA: 0x7598620ca8
	public Void set_MatchType(MatchType value) { }
	// RVA: 0x6008cb0 VA: 0x7598620cb0
	public MatchCasing get_MatchCasing() { }
	// RVA: 0x6008cb8 VA: 0x7598620cb8
	public Boolean get_ReturnSpecialDirectories() { }
	// RVA: 0x6008cc0 VA: 0x7598620cc0
	private static Void .cctor() { }
}
```