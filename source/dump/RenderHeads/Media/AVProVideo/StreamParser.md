# StreamParser

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `String _url`

- `StreamType _streamType`

- `Boolean _autoLoad`

- `Stream _parser`

- `Boolean _loaded`

- `StreamParserEvent _events`


## Properties

- `StreamParserEvent Events`

- `Boolean Loaded`

- `Stream Root`


## Methods

- `StreamParserEvent get_Events()`

- `Void LoadFile()`

- `Boolean get_Loaded()`

- `Stream get_Root()`

- `Void ParseStream()`

- `Void Start()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class StreamParser : MonoBehaviour
{
	public String _url; // 0x18
	public StreamType _streamType; // 0x20
	public Boolean _autoLoad; // 0x24
	private Stream _parser; // 0x28
	private Boolean _loaded; // 0x30
	private List`1 _substreams; // 0x38
	private List`1 _chunks; // 0x40
	private StreamParserEvent _events; // 0x48

	public StreamParserEvent Events { get; }
	public Boolean Loaded { get; }
	public Stream Root { get; }
	public List`1 SubStreams { get; }
	public List`1 Chunks { get; }

	// RVA: 0x6688ad8 VA: 0x7598ca0ad8
	public StreamParserEvent get_Events() { }
	// RVA: 0x6688b4c VA: 0x7598ca0b4c
	private Void LoadFile() { }
	// RVA: 0x6688e10 VA: 0x7598ca0e10
	public Boolean get_Loaded() { }
	// RVA: 0x6688e18 VA: 0x7598ca0e18
	public Stream get_Root() { }
	// RVA: 0x6688e30 VA: 0x7598ca0e30
	public List`1 get_SubStreams() { }
	// RVA: 0x6688e48 VA: 0x7598ca0e48
	public List`1 get_Chunks() { }
	// RVA: 0x6688e60 VA: 0x7598ca0e60
	public Void ParseStream() { }
	// RVA: 0x6688f10 VA: 0x7598ca0f10
	private Void Start() { }
	// RVA: 0x6688f20 VA: 0x7598ca0f20
	public Void .ctor() { }
}
```