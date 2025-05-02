# StageZoneHomeThemeMainlineView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _objMainlineProcessing`

- `Image _imgChapter`

- `Image _imgMainMagnify`

- `Image _imgMainProcessing`

- `Text _textZoneIndex`

- `Text _textZoneName`

- `Text _textProgressCode`

- `GameObject _objMainlineActDisplay`

- `Image _imgMainActDisplay`

- `Sprite _imgLogo`

- `ZoneHomeMainlineEntryItemModel m_viewModel`

- `ActivityThemeData m_themeData`


## Methods

- `Void _RenderMainlineProcessingPart()`

- `Void _RenderMainlineActDisplayPart()`

- `Void EventOnThemeClicked()`

- `String _GetChapterSpriteName(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeThemeMainlineView : Plugin
{
	private GameObject _objMainlineProcessing; // 0x20
	private Image _imgChapter; // 0x28
	private Image _imgMainMagnify; // 0x30
	private Image _imgMainProcessing; // 0x38
	private Text _textZoneIndex; // 0x40
	private Text _textZoneName; // 0x48
	private Text _textProgressCode; // 0x50
	private GameObject _objMainlineActDisplay; // 0x58
	private Image _imgMainActDisplay; // 0x60
	private Sprite _imgLogo; // 0x68
	private ZoneHomeMainlineEntryItemModel m_viewModel; // 0x70
	private ActivityThemeData m_themeData; // 0x78
	private const String CHAPTER_NAME_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_GetThemeLogo; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0__RenderMainlineProcessingPart; // 0x10
	private static DelegateBridge __Hotfix0__RenderMainlineActDisplayPart; // 0x18
	private static DelegateBridge __Hotfix0_EventOnThemeClicked; // 0x20
	private static DelegateBridge __Hotfix0__GetChapterSpriteName; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f0d678 VA: 0x7595525678
	public override Sprite GetThemeLogo() { }
	// RVA: 0x2f0d6e0 VA: 0x75955256e0
	protected override Void OnDataUpdated(Param param) { }
	// RVA: 0x2f0d988 VA: 0x7595525988
	private Void _RenderMainlineProcessingPart() { }
	// RVA: 0x2f0d890 VA: 0x7595525890
	private Void _RenderMainlineActDisplayPart() { }
	// RVA: 0x2f0dcd0 VA: 0x7595525cd0
	public Void EventOnThemeClicked() { }
	// RVA: 0x2f0dc38 VA: 0x7595525c38
	private String _GetChapterSpriteName(String chapterId) { }
	// RVA: 0x2f0dd3c VA: 0x7595525d3c
	public Void .ctor() { }
}
```