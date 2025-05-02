# AtlasMaxRect

**Namespace:** `HG.Rendering.Runtime`


## Fields

- `Int32 m_usedRectSize`

- `Int32 m_maxFreeRectWidth`

- `Int32 m_maxFreeRectHeight`


## Properties

- `Boolean empty`

- `Int32 maxFreeRectWidth`

- `Int32 maxFreeRectHeight`


## Methods

- `Boolean get_empty()`

- `Int32 get_maxFreeRectWidth()`

- `Int32 get_maxFreeRectHeight()`

- `RectInt InsertRect(Int32, Int32)`

- `RectInt InsertRectBestShortSideFit(Int32, Int32)`

- `RectInt InsertRectContactPoint(Int32, Int32)`

- `RectInt InsertRectBestLongSideFit(Int32, Int32)`

- `RectInt InsertRectBestAreaFit(Int32, Int32)`

- `Void InsertRects(List`1, List`1, FreeRectChoiceHeuristic)`

- `Void RemoveRect(RectInt)`

- `Void FreeRects(List`1)`

- `Void Reset()`

- `Void _PlaceRect(RectInt)`

- `RectInt _ScoreRect(Int32, Int32, FreeRectChoiceHeuristic, out, out)`

- `Boolean _SplitFreeNode(RectInt, RectInt)`

- `Void _InsertNewFreeRectangle(RectInt, ref)`

- `Void _PruneFreeList()`

- `Void _RecalculateMaxFreeRectWidthHeight()`

- `Void _PlaceFreeRect(RectInt)`

- `Void _AlignRectWidth(ref, RectInt)`

- `Void _AlignRectHeight(ref, RectInt)`

- `Void _MergeFreeRect(ref)`

- `Boolean _IsContainedIn(RectInt, RectInt)`

- `Int32 _CommonIntervalCount(Int32, Int32, Int32, Int32)`

- `Int32 _ContactPointScoreNode(Int32, Int32, Int32, Int32)`

- `RectInt _FindPositionForNewNodeBestShortSideFit(Int32, Int32, out, out)`

- `RectInt _FindPositionForNewNodeBottomLeft(Int32, Int32, out, out)`

- `RectInt _FindPositionForNewNodeContactPoint(Int32, Int32, out)`

- `RectInt _FindPositionForNewNodeBestLongSideFit(Int32, Int32, out, out)`

- `RectInt _FindPositionForNewNodeBestAreaFit(Int32, Int32, out, out)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : HG.Rendering.Runtime
public class AtlasMaxRect
{
	private readonly Int32 m_binWidth; // 0x10
	private readonly Int32 m_binHeight; // 0x14
	private readonly List`1 m_newFreeRectangles; // 0x18
	private readonly List`1 m_freeRectangles; // 0x20
	private readonly Dictionary`2 m_usedRectangles; // 0x28
	private Int32 m_usedRectSize; // 0x30
	private Int32 m_maxFreeRectWidth; // 0x34
	private Int32 m_maxFreeRectHeight; // 0x38

	public Boolean empty { get; }
	public Int32 maxFreeRectWidth { get; }
	public Int32 maxFreeRectHeight { get; }

	// RVA: 0x66c2d28 VA: 0x7598cdad28
	public Void .ctor(Int32 width, Int32 height) { }
	// RVA: 0x66c2f30 VA: 0x7598cdaf30
	public Boolean get_empty() { }
	// RVA: 0x66c2f40 VA: 0x7598cdaf40
	public Int32 get_maxFreeRectWidth() { }
	// RVA: 0x66c2f48 VA: 0x7598cdaf48
	public Int32 get_maxFreeRectHeight() { }
	// RVA: 0x66c2f50 VA: 0x7598cdaf50
	public RectInt InsertRect(Int32 width, Int32 height) { }
	// RVA: 0x66c3364 VA: 0x7598cdb364
	public RectInt InsertRectBestShortSideFit(Int32 width, Int32 height) { }
	// RVA: 0x66c3654 VA: 0x7598cdb654
	public RectInt InsertRectContactPoint(Int32 width, Int32 height) { }
	// RVA: 0x66c38a4 VA: 0x7598cdb8a4
	public RectInt InsertRectBestLongSideFit(Int32 width, Int32 height) { }
	// RVA: 0x66c3b94 VA: 0x7598cdbb94
	public RectInt InsertRectBestAreaFit(Int32 width, Int32 height) { }
	// RVA: 0x66c3efc VA: 0x7598cdbefc
	public Void InsertRects(List`1 rects, List`1 dst, FreeRectChoiceHeuristic method) { }
	// RVA: 0x66c425c VA: 0x7598cdc25c
	public Void RemoveRect(RectInt rect) { }
	// RVA: 0x66c4a80 VA: 0x7598cdca80
	public Void FreeRects(List`1 rects) { }
	// RVA: 0x66c4ec0 VA: 0x7598cdcec0
	public Void Reset() { }
	// RVA: 0x66c3188 VA: 0x7598cdb188
	private Void _PlaceRect(RectInt node) { }
	// RVA: 0x66c4188 VA: 0x7598cdc188
	private RectInt _ScoreRect(Int32 width, Int32 height, FreeRectChoiceHeuristic method, out Int32 score1, out Int32 score2) { }
	// RVA: 0x66c4fd0 VA: 0x7598cdcfd0
	private Boolean _SplitFreeNode(RectInt freeNode, RectInt usedNode) { }
	// RVA: 0x66c5998 VA: 0x7598cdd998
	private Void _InsertNewFreeRectangle(RectInt newFreeRect, ref Int32 newFreeRectanglesLastSize) { }
	// RVA: 0x66c5520 VA: 0x7598cdd520
	private Void _PruneFreeList() { }
	// RVA: 0x66c498c VA: 0x7598cdc98c
	private Void _RecalculateMaxFreeRectWidthHeight() { }
	// RVA: 0x66c4510 VA: 0x7598cdc510
	private Void _PlaceFreeRect(RectInt node) { }
	// RVA: 0x66c6160 VA: 0x7598cde160
	private Void _AlignRectWidth(ref RectInt src, RectInt dst) { }
	// RVA: 0x66c61e4 VA: 0x7598cde1e4
	private Void _AlignRectHeight(ref RectInt src, RectInt dst) { }
	// RVA: 0x66c5cd4 VA: 0x7598cddcd4
	private Void _MergeFreeRect(ref RectInt r) { }
	// RVA: 0x66c5bc8 VA: 0x7598cddbc8
	private Boolean _IsContainedIn(RectInt a, RectInt b) { }
	// RVA: 0x66c6268 VA: 0x7598cde268
	private Int32 _CommonIntervalCount(Int32 i1Start, Int32 i1End, Int32 i2Start, Int32 i2End) { }
	// RVA: 0x66c6294 VA: 0x7598cde294
	private Int32 _ContactPointScoreNode(Int32 x, Int32 y, Int32 width, Int32 height) { }
	// RVA: 0x66c33b8 VA: 0x7598cdb3b8
	private RectInt _FindPositionForNewNodeBestShortSideFit(Int32 width, Int32 height, out Int32 bestShortSideFit, out Int32 bestLongSideFit) { }
	// RVA: 0x66c5770 VA: 0x7598cdd770
	private RectInt _FindPositionForNewNodeBottomLeft(Int32 width, Int32 height, out Int32 bestY, out Int32 bestX) { }
	// RVA: 0x66c36a4 VA: 0x7598cdb6a4
	private RectInt _FindPositionForNewNodeContactPoint(Int32 width, Int32 height, out Int32 bestContactScore) { }
	// RVA: 0x66c38f8 VA: 0x7598cdb8f8
	private RectInt _FindPositionForNewNodeBestLongSideFit(Int32 width, Int32 height, out Int32 bestShortSideFit, out Int32 bestLongSideFit) { }
	// RVA: 0x66c3be8 VA: 0x7598cdbbe8
	private RectInt _FindPositionForNewNodeBestAreaFit(Int32 width, Int32 height, out Int32 bestAreaFit, out Int32 bestShortSideFit) { }
	// RVA: 0x66c497c VA: 0x7598cdc97c
	private static Int64 _Tuple(Int32 x, Int32 y) { }
}
```