# ArchiveNewsDetailObjView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _titlePart`

- `GameObject _imgPart`

- `GameObject _textPart`

- `Text _titleText`

- `Text _titleAuthor`

- `Text _readCount`

- `Image _imgPartImg`

- `Text _textPartText`


## Methods

- `Void RenderTitlePart(NewsItemModel, ArchiveNewsModel)`

- `Void RenderTextPart(String)`

- `Void RenderImgPart(Sprite)`

- `Int32 _CalReadCount(NewsItemModel, ArchiveNewsModel)`

- `String _FormatReadCount(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveNewsDetailObjView : MonoBehaviour, IHotfixable
{
	private const Int32 BOUND1; // 0x0
	private const Int32 BOUND2; // 0x0
	private const Int32 DIVIDER1; // 0x0
	private const Int32 DIVIDER2; // 0x0
	private GameObject _titlePart; // 0x18
	private GameObject _imgPart; // 0x20
	private GameObject _textPart; // 0x28
	private Text _titleText; // 0x30
	private Text _titleAuthor; // 0x38
	private Text _readCount; // 0x40
	private Image _imgPartImg; // 0x48
	private Text _textPartText; // 0x50
	private static DelegateBridge __Hotfix0_RenderTitlePart; // 0x0
	private static DelegateBridge __Hotfix0_RenderTextPart; // 0x8
	private static DelegateBridge __Hotfix0_RenderImgPart; // 0x10
	private static DelegateBridge __Hotfix0__CalReadCount; // 0x18
	private static DelegateBridge __Hotfix0__FormatReadCount; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3063d4c VA: 0x759567bd4c
	public Void RenderTitlePart(NewsItemModel model, ArchiveNewsModel newsModel) { }
	// RVA: 0x306444c VA: 0x759567c44c
	public Void RenderTextPart(String textContent) { }
	// RVA: 0x306452c VA: 0x759567c52c
	public Void RenderImgPart(Sprite newsPic) { }
	// RVA: 0x3063ee8 VA: 0x759567bee8
	private Int32 _CalReadCount(NewsItemModel model, ArchiveNewsModel newsModel) { }
	// RVA: 0x30642c8 VA: 0x759567c2c8
	private String _FormatReadCount(Int32 readCount) { }
	// RVA: 0x3064604 VA: 0x759567c604
	public Void .ctor() { }
}
```