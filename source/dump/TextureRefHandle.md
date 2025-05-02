# TextureRefHandle

**Namespace:** ` `


## Fields

- `Int32 refCount`

- `RectInt rect`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class TextureRefHandle
{
	private static readonly LocalGenericPool`1 s_textureRefHandlePool; // 0x0
	public Int32 refCount; // 0x10
	public RectInt rect; // 0x14


	// RVA: 0x6788ce4 VA: 0x7598da0ce4
	private static Void _PoolOnly_Reset(TextureRefHandle inst) { }
	// RVA: 0x6788960 VA: 0x7598da0960
	public static TextureRefHandle Alloc(Int32 refCount, in RectInt rect) { }
	// RVA: 0x6788b44 VA: 0x7598da0b44
	public static Void Release(TextureRefHandle inst) { }
	// RVA: 0x6788cfc VA: 0x7598da0cfc
	public Void .ctor() { }
	// RVA: 0x6788d04 VA: 0x7598da0d04
	private static Void .cctor() { }
}
```