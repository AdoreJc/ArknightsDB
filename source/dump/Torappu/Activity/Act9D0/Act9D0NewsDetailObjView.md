# Act9D0NewsDetailObjView

**Namespace:** `Torappu.Activity.Act9D0`


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

- `Void RenderTitlePart(Act9D0NewsViewModel, Int32, Dictionary`2)`

- `Void RenderTextPart(String)`

- `Void RenderImgPart(Sprite)`

- `Int32 _CalReadCount(Act9D0NewsViewModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsDetailObjView : MonoBehaviour, IHotfixable
{
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
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31a871c VA: 0x75957c071c
	public Void RenderTitlePart(Act9D0NewsViewModel viewModel, Int32 unlockCount, Dictionary`2 miscHub) { }
	// RVA: 0x31a8c98 VA: 0x75957c0c98
	public Void RenderTextPart(String textContent) { }
	// RVA: 0x31a8d78 VA: 0x75957c0d78
	public Void RenderImgPart(Sprite newsPic) { }
	// RVA: 0x31a8a9c VA: 0x75957c0a9c
	private Int32 _CalReadCount(Act9D0NewsViewModel viewModel, Int32 unlockMission) { }
	// RVA: 0x31a8e50 VA: 0x75957c0e50
	public Void .ctor() { }
}
```