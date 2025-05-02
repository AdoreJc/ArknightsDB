# SmallXmlParser

**Namespace:** `Mono.Xml`


## Fields

- `IContentHandler handler`

- `TextReader reader`

- `Stack elementNames`

- `Stack xmlSpaces`

- `String xmlSpace`

- `StringBuilder buffer`

- `Boolean isWhitespace`

- `AttrListImpl attributes`

- `Int32 line`

- `Int32 column`

- `Boolean resetColumn`


## Methods

- `Exception Error(String)`

- `Exception UnexpectedEndError()`

- `Boolean IsNameChar(Char, Boolean)`

- `Boolean IsWhitespace(Int32)`

- `Void SkipWhitespaces()`

- `Void HandleWhitespaces()`

- `Void SkipWhitespaces(Boolean)`

- `Int32 Peek()`

- `Int32 Read()`

- `Void Expect(Int32)`

- `String ReadUntil(Char, Boolean)`

- `String ReadName()`

- `Void Parse(TextReader, IContentHandler)`

- `Void Cleanup()`

- `Void ReadContent()`

- `Void HandleBufferedContent()`

- `Void ReadCharacters()`

- `Void ReadReference()`

- `Int32 ReadCharacterReference()`

- `Void ReadAttribute(AttrListImpl)`

- `Void ReadCDATASection()`

- `Void ReadComment()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Xml
internal class SmallXmlParser
{
	private IContentHandler handler; // 0x10
	private TextReader reader; // 0x18
	private Stack elementNames; // 0x20
	private Stack xmlSpaces; // 0x28
	private String xmlSpace; // 0x30
	private StringBuilder buffer; // 0x38
	private Char[] nameBuffer; // 0x40
	private Boolean isWhitespace; // 0x48
	private AttrListImpl attributes; // 0x50
	private Int32 line; // 0x58
	private Int32 column; // 0x5c
	private Boolean resetColumn; // 0x60


	// RVA: 0x5ef8db8 VA: 0x7598510db8
	public Void .ctor() { }
	// RVA: 0x5ef9618 VA: 0x7598511618
	private Exception Error(String msg) { }
	// RVA: 0x5ef975c VA: 0x759851175c
	private Exception UnexpectedEndError() { }
	// RVA: 0x5ef9848 VA: 0x7598511848
	private Boolean IsNameChar(Char c, Boolean start) { }
	// RVA: 0x5ef9944 VA: 0x7598511944
	private Boolean IsWhitespace(Int32 c) { }
	// RVA: 0x5ef9974 VA: 0x7598511974
	public Void SkipWhitespaces() { }
	// RVA: 0x5ef9a28 VA: 0x7598511a28
	private Void HandleWhitespaces() { }
	// RVA: 0x5ef997c VA: 0x759851197c
	public Void SkipWhitespaces(Boolean expected) { }
	// RVA: 0x5ef9b50 VA: 0x7598511b50
	private Int32 Peek() { }
	// RVA: 0x5ef9ae8 VA: 0x7598511ae8
	private Int32 Read() { }
	// RVA: 0x5ef9b70 VA: 0x7598511b70
	public Void Expect(Int32 c) { }
	// RVA: 0x5ef9c30 VA: 0x7598511c30
	private String ReadUntil(Char until, Boolean handleReferences) { }
	// RVA: 0x5ef9ed4 VA: 0x7598511ed4
	public String ReadName() { }
	// RVA: 0x5ef8fa8 VA: 0x7598510fa8
	public Void Parse(TextReader input, IContentHandler handler) { }
	// RVA: 0x5efa8b0 VA: 0x75985128b0
	private Void Cleanup() { }
	// RVA: 0x5efa08c VA: 0x759851208c
	public Void ReadContent() { }
	// RVA: 0x5efa778 VA: 0x7598512778
	private Void HandleBufferedContent() { }
	// RVA: 0x5efacf0 VA: 0x7598512cf0
	private Void ReadCharacters() { }
	// RVA: 0x5ef9d0c VA: 0x7598511d0c
	private Void ReadReference() { }
	// RVA: 0x5efad78 VA: 0x7598512d78
	private Int32 ReadCharacterReference() { }
	// RVA: 0x5efab80 VA: 0x7598512b80
	private Void ReadAttribute(AttrListImpl a) { }
	// RVA: 0x5efa9f8 VA: 0x75985129f8
	private Void ReadCDATASection() { }
	// RVA: 0x5efaaf8 VA: 0x7598512af8
	private Void ReadComment() { }
}
```