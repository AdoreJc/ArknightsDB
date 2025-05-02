# Act29sideUIProgressBar

**Namespace:** `Torappu.Activity.Act29side.Battle.UI`


## Fields

- `Color _enthuBarColor`

- `Color _depressedBarColor`

- `Color _emptyBarColor`

- `Color _enthuPredictColor`

- `Color _depressedPredictColor`

- `UIAtlasImage _predictMark`

- `UIAtlasImage _progressBarBackground`

- `UIAtlasImage _progressBarProcessing`

- `UIAtlasImage _blurMask`

- `UIAtlasImage _markInactiveLeft`

- `UIAtlasImage _markInactiveRight`

- `UIAtlasImage _markActiveRightEnthu`

- `UIAtlasImage _markActiveRightDepressed`

- `GameObject _decoEnthu`

- `GameObject _decoDepressed`

- `Act29SideManager m_manager`

- `AudioType m_type`

- `Single m_progress`

- `Single m_width`

- `Single m_audioBuffLength`

- `Single m_tweenTime`

- `Boolean m_isActive`

- `Boolean m_needFadingOut`

- `Boolean m_fadingOutOver`

- `Boolean m_isFadingIn`

- `Boolean m_fadingInOver`

- `Boolean m_hideRightMark`

- `RectTransform m_rect`


## Properties

- `Boolean isActive`


## Methods

- `Boolean get_isActive()`

- `Void Init(ProgressBarInfo)`

- `Void Active()`

- `Void Inactive()`

- `Void UpdateProgressBar()`

- `Void <UpdateProgressBar>b__35_0()`

- `Void <UpdateProgressBar>b__35_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29side.Battle.UI
public class Act29sideUIProgressBar : MonoBehaviour
{
	private Color _enthuBarColor; // 0x18
	private Color _depressedBarColor; // 0x28
	private Color _emptyBarColor; // 0x38
	private Color _enthuPredictColor; // 0x48
	private Color _depressedPredictColor; // 0x58
	private UIAtlasImage _predictMark; // 0x68
	private UIAtlasImage _progressBarBackground; // 0x70
	private UIAtlasImage _progressBarProcessing; // 0x78
	private UIAtlasImage _blurMask; // 0x80
	private UIAtlasImage _markInactiveLeft; // 0x88
	private UIAtlasImage _markInactiveRight; // 0x90
	private UIAtlasImage _markActiveRightEnthu; // 0x98
	private UIAtlasImage _markActiveRightDepressed; // 0xa0
	private GameObject _decoEnthu; // 0xa8
	private GameObject _decoDepressed; // 0xb0
	private Act29SideManager m_manager; // 0xb8
	private AudioType m_type; // 0xc0
	private Single m_progress; // 0xc4
	private Single m_width; // 0xc8
	private Single m_audioBuffLength; // 0xcc
	private Single m_tweenTime; // 0xd0
	private Boolean m_isActive; // 0xd4
	private Boolean m_needFadingOut; // 0xd5
	private Boolean m_fadingOutOver; // 0xd6
	private Boolean m_isFadingIn; // 0xd7
	private Boolean m_fadingInOver; // 0xd8
	private Boolean m_hideRightMark; // 0xd9
	private RectTransform m_rect; // 0xe0
	private const Single PREDICT_MARK_SCALER; // 0x0
	private const Single BLUR_MASK_MARGIN; // 0x0

	public Boolean isActive { get; }

	// RVA: 0x3267834 VA: 0x759587f834
	public Boolean get_isActive() { }
	// RVA: 0x3267128 VA: 0x759587f128
	public Void Init(ProgressBarInfo info) { }
	// RVA: 0x3267570 VA: 0x759587f570
	public Void Active() { }
	// RVA: 0x3267508 VA: 0x759587f508
	public Void Inactive() { }
	// RVA: 0x32669a4 VA: 0x759587e9a4
	public Void UpdateProgressBar() { }
	// RVA: 0x326783c VA: 0x759587f83c
	public Void .ctor() { }
	// RVA: 0x3267844 VA: 0x759587f844
	private Void <UpdateProgressBar>b__35_0() { }
	// RVA: 0x3267850 VA: 0x759587f850
	private Void <UpdateProgressBar>b__35_1() { }
}
```