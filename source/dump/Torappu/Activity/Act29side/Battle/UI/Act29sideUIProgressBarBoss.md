# Act29sideUIProgressBarBoss

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

- `UIAtlasImage _progressMark`

- `UIAtlasImage _progressMarkDepressed`

- `UIAtlasImage _progressMarkEnthu`

- `UIAtlasImage _progressMarkEmpty`

- `UIAtlasImage _blurMask`

- `RectTransform _anchor`

- `Act29SideManager m_manager`

- `AudioType m_audiotypeLastTick`

- `AudioType m_audiotypeNextTrigger`

- `Single m_tweenTime`

- `Boolean m_lockProgressMark`

- `Boolean m_endAudioStage`

- `Boolean m_isBossDead`

- `Boolean m_firstFadeIn`

- `Tween m_markEnthuTweenFI`

- `Tween m_markDepressedTweenFI`

- `Tween m_markEmptyTweenFO`

- `Tween m_markPredictTweenFO`

- `Sequence seq_1`

- `Sequence seq_2`


## Methods

- `Void Init(ProgressBarInfo)`

- `Void UpdateProgressBar()`

- `Void _DoFade(Boolean, ref, ref)`

- `Void _DoFadeIn(AudioType)`

- `Void _DoFadeOut(AudioType)`

- `Void _CloseAllTweens()`

- `Void _SwitchToBossDeadStage()`

- `AudioType _GetOppositeAudioType(AudioType)`

- `Void <_DoFadeOut>b__33_0()`

- `Void <_DoFadeOut>b__33_1()`

- `Void <_DoFadeOut>b__33_2()`

- `Void <_DoFadeOut>b__33_3()`

- `Void <_DoFadeOut>b__33_4()`

- `Void <_SwitchToBossDeadStage>b__35_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29side.Battle.UI
public class Act29sideUIProgressBarBoss : MonoBehaviour
{
	private Color _enthuBarColor; // 0x18
	private Color _depressedBarColor; // 0x28
	private Color _emptyBarColor; // 0x38
	private Color _enthuPredictColor; // 0x48
	private Color _depressedPredictColor; // 0x58
	private UIAtlasImage _predictMark; // 0x68
	private UIAtlasImage _progressBarBackground; // 0x70
	private UIAtlasImage _progressBarProcessing; // 0x78
	private UIAtlasImage _progressMark; // 0x80
	private UIAtlasImage _progressMarkDepressed; // 0x88
	private UIAtlasImage _progressMarkEnthu; // 0x90
	private UIAtlasImage _progressMarkEmpty; // 0x98
	private UIAtlasImage _blurMask; // 0xa0
	private RectTransform _anchor; // 0xa8
	private Act29SideManager m_manager; // 0xb0
	private AudioType m_audiotypeLastTick; // 0xb8
	private AudioType m_audiotypeNextTrigger; // 0xbc
	private Single m_tweenTime; // 0xc0
	private Boolean m_lockProgressMark; // 0xc4
	private Boolean m_endAudioStage; // 0xc5
	private Boolean m_isBossDead; // 0xc6
	private Boolean m_firstFadeIn; // 0xc7
	private Tween m_markEnthuTweenFI; // 0xc8
	private Tween m_markDepressedTweenFI; // 0xd0
	private Tween m_markEmptyTweenFO; // 0xd8
	private Tween m_markPredictTweenFO; // 0xe0
	private Sequence seq_1; // 0xe8
	private Sequence seq_2; // 0xf0
	private const Single BLUR_MASK_MARGIN; // 0x0


	// RVA: 0x3265ca4 VA: 0x759587dca4
	public Void Init(ProgressBarInfo info) { }
	// RVA: 0x3265e44 VA: 0x759587de44
	public Void UpdateProgressBar() { }
	// RVA: 0x32680f4 VA: 0x75958800f4
	private Void _DoFade(Boolean isFadeIn, ref UIAtlasImage atlas, ref Tween tween) { }
	// RVA: 0x3267b20 VA: 0x759587fb20
	private Void _DoFadeIn(AudioType audioType) { }
	// RVA: 0x3267c98 VA: 0x759587fc98
	private Void _DoFadeOut(AudioType audioType) { }
	// RVA: 0x3267878 VA: 0x759587f878
	private Void _CloseAllTweens() { }
	// RVA: 0x3267948 VA: 0x759587f948
	private Void _SwitchToBossDeadStage() { }
	// RVA: 0x326785c VA: 0x759587f85c
	private AudioType _GetOppositeAudioType(AudioType audioType) { }
	// RVA: 0x3268280 VA: 0x7595880280
	public Void .ctor() { }
	// RVA: 0x3268288 VA: 0x7595880288
	private Void <_DoFadeOut>b__33_0() { }
	// RVA: 0x3268320 VA: 0x7595880320
	private Void <_DoFadeOut>b__33_1() { }
	// RVA: 0x32683b8 VA: 0x75958803b8
	private Void <_DoFadeOut>b__33_2() { }
	// RVA: 0x3268408 VA: 0x7595880408
	private Void <_DoFadeOut>b__33_3() { }
	// RVA: 0x32684a8 VA: 0x75958804a8
	private Void <_DoFadeOut>b__33_4() { }
	// RVA: 0x32684b0 VA: 0x75958804b0
	private Void <_SwitchToBossDeadStage>b__35_0() { }
}
```