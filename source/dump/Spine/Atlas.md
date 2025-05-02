# Atlas

**Namespace:** `Spine`


## Fields

- `TextureLoader textureLoader`


## Methods

- `Void Load(TextReader, String, TextureLoader)`

- `Void FlipV()`

- `AtlasRegion FindRegion(String)`

- `Void Dispose()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Atlas : IEnumerable`1, IEnumerable
{
	private readonly List`1 pages; // 0x10
	private List`1 regions; // 0x18
	private TextureLoader textureLoader; // 0x20

	public List`1 Regions { get; }
	public List`1 Pages { get; }

	// RVA: 0x61cf8c8 VA: 0x75987e78c8
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x61cf958 VA: 0x75987e7958
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x61cf9e8 VA: 0x75987e79e8
	public List`1 get_Regions() { }
	// RVA: 0x61cf9f0 VA: 0x75987e79f0
	public List`1 get_Pages() { }
	// RVA: 0x61cf9f8 VA: 0x75987e79f8
	public Void .ctor(TextReader reader, String dir, TextureLoader textureLoader) { }
	// RVA: 0x61d06f4 VA: 0x75987e86f4
	public Void .ctor(List`1 pages, List`1 regions) { }
	// RVA: 0x61cfb00 VA: 0x75987e7b00
	private Void Load(TextReader reader, String imagesDir, TextureLoader textureLoader) { }
	// RVA: 0x61d09e8 VA: 0x75987e89e8
	private static String ReadValue(TextReader reader) { }
	// RVA: 0x61d0824 VA: 0x75987e8824
	private static Int32 ReadTuple(TextReader reader, String[] tuple) { }
	// RVA: 0x61d0aac VA: 0x75987e8aac
	public Void FlipV() { }
	// RVA: 0x61d0b64 VA: 0x75987e8b64
	public AtlasRegion FindRegion(String name) { }
	// RVA: 0x61d0c38 VA: 0x75987e8c38
	public Void Dispose() { }
}
```