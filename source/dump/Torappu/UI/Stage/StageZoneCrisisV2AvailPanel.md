# StageZoneCrisisV2AvailPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIAtlasImage _backImg`

- `UIAtlasImage _titleImg`

- `UIAtlasImage _medalBackImg`

- `SimpleLayoutContent _content`

- `Text _remainTime`

- `Text _seasonName`

- `Text _stageName`

- `GameObject _availMedalPart`

- `GameObject _unavailMedalPart`

- `Image _medalIcon`

- `UIPageFinder m_finder`

- `Boolean m_IsInited`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void RenderSeason(CrisisV2ZoneGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneCrisisV2AvailPanel : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _backImg; // 0x18
	private UIAtlasImage _titleImg; // 0x20
	private UIAtlasImage _medalBackImg; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private Text _remainTime; // 0x38
	private Text _seasonName; // 0x40
	private Text _stageName; // 0x48
	private GameObject _availMedalPart; // 0x50
	private GameObject _unavailMedalPart; // 0x58
	private Image _medalIcon; // 0x60
	private Graphic[] _themeColorGraphicList; // 0x68
	private UIPageFinder m_finder; // 0x70
	private Boolean m_IsInited; // 0x80
	private Adapter m_adapter; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderSeason; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2fb29cc VA: 0x75955ca9cc
	private Void _InitIfNot() { }
	// RVA: 0x2fb2b08 VA: 0x75955cab08
	public Void RenderSeason(CrisisV2ZoneGroupViewModel viewModel) { }
	// RVA: 0x2fb3010 VA: 0x75955cb010
	public Void .ctor() { }
}
```