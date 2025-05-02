# Match

**Namespace:** `System.Text.RegularExpressions`


## Methods

- `Match NextMatch()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Text.RegularExpressions
public class Match : Group
{
	internal GroupCollection _groupcoll; // 0x40
	internal Regex _regex; // 0x48
	internal Int32 _textbeg; // 0x50
	internal Int32 _textpos; // 0x54
	internal Int32 _textend; // 0x58
	internal Int32 _textstart; // 0x5c
	internal Int32[][] _matches; // 0x60
	internal Int32[] _matchcount; // 0x68
	internal Boolean _balancing; // 0x70
	private static readonly Match <Empty>k__BackingField; // 0x0

	public static Match Empty { get; }
	public virtual GroupCollection Groups { get; }

	// RVA: 0x63779bc VA: 0x759898f9bc
	internal Void .ctor(Regex regex, Int32 capcount, String text, Int32 begpos, Int32 len, Int32 startpos) { }
	// RVA: 0x6377b58 VA: 0x759898fb58
	public static Match get_Empty() { }
	// RVA: 0x6377bb0 VA: 0x759898fbb0
	internal virtual Void Reset(Regex regex, String text, Int32 textbeg, Int32 textend, Int32 textstart) { }
	// RVA: 0x6377c54 VA: 0x759898fc54
	public virtual GroupCollection get_Groups() { }
	// RVA: 0x6377cd4 VA: 0x759898fcd4
	public Match NextMatch() { }
	// RVA: 0x6377f94 VA: 0x759898ff94
	internal virtual ReadOnlySpan`1 GroupToStringImpl(Int32 groupnum) { }
	// RVA: 0x637812c VA: 0x759899012c
	internal ReadOnlySpan`1 LastGroupToStringImpl() { }
	// RVA: 0x6378154 VA: 0x7598990154
	internal virtual Void AddMatch(Int32 cap, Int32 start, Int32 len) { }
	// RVA: 0x637838c VA: 0x759899038c
	internal virtual Void BalanceMatch(Int32 cap) { }
	// RVA: 0x6378464 VA: 0x7598990464
	internal virtual Void RemoveMatch(Int32 cap) { }
	// RVA: 0x637849c VA: 0x759899049c
	internal virtual Boolean IsMatched(Int32 cap) { }
	// RVA: 0x637852c VA: 0x759899052c
	internal virtual Int32 MatchIndex(Int32 cap) { }
	// RVA: 0x63785b8 VA: 0x75989905b8
	internal virtual Int32 MatchLength(Int32 cap) { }
	// RVA: 0x6378644 VA: 0x7598990644
	internal virtual Void Tidy(Int32 textpos) { }
	// RVA: 0x63787a8 VA: 0x75989907a8
	private static Void .cctor() { }
	// RVA: 0x637884c VA: 0x759899084c
	internal Void .ctor() { }
}
```