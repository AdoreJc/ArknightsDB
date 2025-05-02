# TemplateActivityMissionItem

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Text _missionDetail`

- `ShowProgressType _showProgressType`

- `Image _progress`

- `Slider _progressSlider`

- `Text _progressDetail`

- `Text _progressSliderDetail`

- `SimpleLayoutContent _content`

- `MonoBehaviour _plugin`

- `Graphic _uiColoredImg`

- `Color _availColor`

- `Color _notAvailColor`

- `Single _scalerFactor`

- `String m_textProgressFormatCanClaim`

- `String m_textProgressFormatCannotClaim`

- `String m_textDetailColorCanClaim`

- `String m_textDetailColorCannotClaim`

- `UIStringEvent onMissionGetRewardClick`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `TemplateMissionViewModel m_cacheViewModel`


## Properties

- `TemplateActivityMissionPlugin plugin`

- `Adapter adatper`

- `TemplateMissionViewModel viewModel`


## Methods

- `TemplateActivityMissionPlugin get_plugin()`

- `Adapter get_adatper()`

- `Void _InitIfNot()`

- `TemplateMissionViewModel get_viewModel()`

- `Boolean _ShowProgressWithText()`

- `Boolean _ShowProgressWithProgressBar()`

- `Boolean _ShowProgressWithProgressSlider()`

- `Void _BasicRender()`

- `Void _FillProgress()`

- `Void _InitTextFormatOrColor(Dictionary`2, String, out, String)`

- `Void OnClick()`

- `Void Render(TemplateMissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMissionItem : MonoBehaviour, IHotfixable
{
	private List`1 onAbleToGetPart; // 0x18
	private List`1 onAlreadyGetPart; // 0x20
	private List`1 onCannotGetPart; // 0x28
	private List`1 onAvailPart; // 0x30
	private Text _missionDetail; // 0x38
	private ShowProgressType _showProgressType; // 0x40
	private Image _progress; // 0x48
	private Slider _progressSlider; // 0x50
	private Text _progressDetail; // 0x58
	private Text _progressSliderDetail; // 0x60
	private SimpleLayoutContent _content; // 0x68
	private MonoBehaviour _plugin; // 0x70
	private Graphic _uiColoredImg; // 0x78
	private Color _availColor; // 0x80
	private Color _notAvailColor; // 0x90
	private Single _scalerFactor; // 0xa0
	private String m_textProgressFormatCanClaim; // 0xa8
	private String m_textProgressFormatCannotClaim; // 0xb0
	private String m_textDetailColorCanClaim; // 0xb8
	private String m_textDetailColorCannotClaim; // 0xc0
	private const String DEFAULT_TEXT_PROGRESS_FORMAT; // 0x0
	private const String DEFAULT_TEXT_DETAIL_COLOR; // 0x0
	public UIStringEvent onMissionGetRewardClick; // 0xc8
	private Adapter m_adapter; // 0xd0
	private Boolean m_isInited; // 0xd8
	private TemplateMissionViewModel m_cacheViewModel; // 0xe0
	private static DelegateBridge __Hotfix0_get_plugin; // 0x0
	private static DelegateBridge __Hotfix0_get_adatper; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_get_viewModel; // 0x18
	private static DelegateBridge __Hotfix0__ShowProgressWithText; // 0x20
	private static DelegateBridge __Hotfix0__ShowProgressWithProgressBar; // 0x28
	private static DelegateBridge __Hotfix0__ShowProgressWithProgressSlider; // 0x30
	private static DelegateBridge __Hotfix0__BasicRender; // 0x38
	private static DelegateBridge __Hotfix0__FillProgress; // 0x40
	private static DelegateBridge __Hotfix0__InitTextFormatOrColor; // 0x48
	private static DelegateBridge __Hotfix0_OnClick; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public TemplateActivityMissionPlugin plugin { get; }
	public Adapter adatper { get; }
	protected TemplateMissionViewModel viewModel { get; }

	// RVA: 0x30a7ae4 VA: 0x75956bfae4
	public TemplateActivityMissionPlugin get_plugin() { }
	// RVA: 0x30a7b64 VA: 0x75956bfb64
	public Adapter get_adatper() { }
	// RVA: 0x30a7bcc VA: 0x75956bfbcc
	private Void _InitIfNot() { }
	// RVA: 0x30a7d14 VA: 0x75956bfd14
	protected TemplateMissionViewModel get_viewModel() { }
	// RVA: 0x30a7d7c VA: 0x75956bfd7c
	private Boolean _ShowProgressWithText() { }
	// RVA: 0x30a7dec VA: 0x75956bfdec
	private Boolean _ShowProgressWithProgressBar() { }
	// RVA: 0x30a7e70 VA: 0x75956bfe70
	private Boolean _ShowProgressWithProgressSlider() { }
	// RVA: 0x30a7ee0 VA: 0x75956bfee0
	private Void _BasicRender() { }
	// RVA: 0x30a8abc VA: 0x75956c0abc
	private Void _FillProgress() { }
	// RVA: 0x30a8be8 VA: 0x75956c0be8
	private Void _InitTextFormatOrColor(Dictionary`2 activityStringRes, String stringResKey, out String textToInit, String defaultValue) { }
	// RVA: 0x30a8d34 VA: 0x75956c0d34
	public Void OnClick() { }
	// RVA: 0x30a8ddc VA: 0x75956c0ddc
	public Void Render(TemplateMissionViewModel viewModel) { }
	// RVA: 0x30a8fc0 VA: 0x75956c0fc0
	public Void .ctor() { }
}
```