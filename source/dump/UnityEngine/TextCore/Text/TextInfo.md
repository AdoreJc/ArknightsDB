# TextInfo

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `Int32 characterCount`

- `Int32 spriteCount`

- `Int32 spaceCount`

- `Int32 wordCount`

- `Int32 linkCount`

- `Int32 lineCount`

- `Int32 pageCount`

- `Int32 materialCount`

- `Boolean isDirty`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
internal class TextInfo
{
	private static Vector2 s_InfinityVectorPositive; // 0x0
	private static Vector2 s_InfinityVectorNegative; // 0x8
	public Int32 characterCount; // 0x10
	public Int32 spriteCount; // 0x14
	public Int32 spaceCount; // 0x18
	public Int32 wordCount; // 0x1c
	public Int32 linkCount; // 0x20
	public Int32 lineCount; // 0x24
	public Int32 pageCount; // 0x28
	public Int32 materialCount; // 0x2c
	public TextElementInfo[] textElementInfo; // 0x30
	public WordInfo[] wordInfo; // 0x38
	public LinkInfo[] linkInfo; // 0x40
	public LineInfo[] lineInfo; // 0x48
	public PageInfo[] pageInfo; // 0x50
	public MeshInfo[] meshInfo; // 0x58
	public Boolean isDirty; // 0x60


	// RVA: 0x690ccd0 VA: 0x7598f24cd0
	public Void .ctor() { }
	// RVA: 0x690ce4c VA: 0x7598f24e4c
	internal Void Clear() { }
	// RVA: 0x690cea8 VA: 0x7598f24ea8
	internal Void ClearMeshInfo(Boolean updateMesh) { }
	// RVA: 0x690cf64 VA: 0x7598f24f64
	internal Void ClearLineInfo() { }
	// RVA: 0x VA: 0x0
	internal static Void Resize(ref T[] array, Int32 size) { }
	// RVA: 0x VA: 0x0
	internal static Void Resize(ref T[] array, Int32 size, Boolean isBlockAllocated) { }
	// RVA: 0x690d0dc VA: 0x7598f250dc
	private static Void .cctor() { }
}
```