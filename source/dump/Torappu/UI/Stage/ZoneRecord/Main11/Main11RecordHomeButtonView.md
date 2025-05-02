# Main11RecordHomeButtonView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelComplete`

- `CanvasGroup _canvasBtnPrevGlow`

- `UICommonTrackPoint _trackPointReward`

- `Text _textRecordName`

- `String m_cachedRecordId`

- `Boolean m_hasInited`

- `Main11RecordHomeButtonGlowTweenWrapper m_glowTween`

- `TrackPointViewProperty m_rewardTrackProperty`


## Methods

- `Void set_onBtnClicked(Action`1)`

- `Void Render(ZoneRecordViewModel)`

- `Void OnButtonClicked()`

- `Void _InitIfNot()`

- `Void _UpdateButtonGlow(Main11RecordHomeButtonGlowTweenWrapper, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11RecordHomeButtonView : MonoBehaviour, IHotfixable
{
	private GameObject _panelLocked; // 0x18
	private GameObject _panelComplete; // 0x20
	private StageDiffImage[] _panelDiffGroup; // 0x28
	private CanvasGroup _canvasBtnPrevGlow; // 0x30
	private UICommonTrackPoint _trackPointReward; // 0x38
	private Text _textRecordName; // 0x40
	private String m_cachedRecordId; // 0x48
	private Dictionary`2 m_diffImgDict; // 0x50
	private Boolean m_hasInited; // 0x58
	private Main11RecordHomeButtonGlowTweenWrapper m_glowTween; // 0x60
	private TrackPointViewProperty m_rewardTrackProperty; // 0x68
	private Action`1 <onBtnClicked>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnButtonClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__UpdateButtonGlow; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onBtnClicked { get; set; }

	// RVA: 0x2fd5178 VA: 0x75955ed178
	private Action`1 get_onBtnClicked() { }
	// RVA: 0x2fd51e0 VA: 0x75955ed1e0
	public Void set_onBtnClicked(Action`1 value) { }
	// RVA: 0x2fd5264 VA: 0x75955ed264
	public Void Render(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd5854 VA: 0x75955ed854
	public Void OnButtonClicked() { }
	// RVA: 0x2fd5570 VA: 0x75955ed570
	private Void _InitIfNot() { }
	// RVA: 0x2fd57ac VA: 0x75955ed7ac
	private Void _UpdateButtonGlow(Main11RecordHomeButtonGlowTweenWrapper tween, Boolean glow) { }
	// RVA: 0x2fd5d18 VA: 0x75955edd18
	public Void .ctor() { }
}
```