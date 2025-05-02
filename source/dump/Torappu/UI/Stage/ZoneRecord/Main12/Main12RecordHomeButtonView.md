# Main12RecordHomeButtonView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `CanvasGroup _canvasGroup`

- `UICommonTrackPoint _trackPointReward`

- `Text _titleName`

- `UIAtlasImage _back`

- `GameObject _lockIcon`

- `Single _lockAlpha`

- `Boolean m_isInited`

- `String m_cachedRecordId`

- `TrackPointViewProperty m_rewardTrackProperty`


## Methods

- `Void set_onClickBtn(Action`1)`

- `Void Render(ZoneRecordViewModel)`

- `Void OnClickBtn()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12RecordHomeButtonView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasGroup; // 0x18
	private StageDiffImage[] _panelDiffGroup; // 0x20
	private UICommonTrackPoint _trackPointReward; // 0x28
	private Text _titleName; // 0x30
	private UIAtlasImage _back; // 0x38
	private GameObject _lockIcon; // 0x40
	private Single _lockAlpha; // 0x48
	private Boolean m_isInited; // 0x4c
	private String m_cachedRecordId; // 0x50
	private TrackPointViewProperty m_rewardTrackProperty; // 0x58
	private Dictionary`2 m_diffImgDict; // 0x60
	private Action`1 <onClickBtn>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClickBtn; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickBtn; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClickBtn; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onClickBtn { get; set; }

	// RVA: 0x2fcda24 VA: 0x75955e5a24
	private Action`1 get_onClickBtn() { }
	// RVA: 0x2fcda8c VA: 0x75955e5a8c
	public Void set_onClickBtn(Action`1 value) { }
	// RVA: 0x2fcdb10 VA: 0x75955e5b10
	public Void Render(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fce024 VA: 0x75955e6024
	public Void OnClickBtn() { }
	// RVA: 0x2fcde3c VA: 0x75955e5e3c
	private Void _InitIfNot() { }
	// RVA: 0x2fce0d4 VA: 0x75955e60d4
	public Void .ctor() { }
}
```