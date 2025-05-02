# Act13sideMissionPlugin

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Text _missionName`

- `Text _missionFinishDesc`

- `Image _charBack`

- `Text _missionFrom`

- `Text _orgDesc`

- `AnimationWrapper _wrapper`

- `Image _leftImg`

- `GameObject _receiveAllBtn`

- `GameObject _showAllBtn`

- `GameObject _emptyPart`

- `GameObject _normalPart`

- `GameObject _allFinishPart`

- `GameObject _goToButton`

- `Boolean cacheAvail`

- `Boolean m_lockFlag`

- `TemplateMissionViewModel m_cacheViewModel`

- `Single animDelta`

- `Boolean showAllInfoFlag`

- `Boolean m_needToPlayAnim`

- `Boolean m_lastTimeData`


## Methods

- `Void ApplyDataBundle(TemplateMissionViewModel)`

- `Void RenderViewAct13Side()`

- `Void _PlayAnim(Action)`

- `IEnumerator RenderCor(Action)`

- `Void Render(Action)`

- `Void RenderCoro(Action)`

- `Boolean IsAvailClick()`

- `Void OnAllClick()`

- `Void OnReceiveAllClick()`

- `Void OnGoToStageClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionPlugin : MonoBehaviour, TemplateActivityMissionPlugin, IHotfixable
{
	private Text _missionName; // 0x18
	private Text _missionFinishDesc; // 0x20
	private Image _charBack; // 0x28
	private Text _missionFrom; // 0x30
	private Text _orgDesc; // 0x38
	private AnimationWrapper _wrapper; // 0x40
	private Image _leftImg; // 0x48
	private GameObject _receiveAllBtn; // 0x50
	private GameObject _showAllBtn; // 0x58
	private GameObject _emptyPart; // 0x60
	private GameObject _normalPart; // 0x68
	private GameObject _allFinishPart; // 0x70
	private GameObject _goToButton; // 0x78
	private Boolean cacheAvail; // 0x80
	private const String FADE_IN_PARAM; // 0x0
	private const String FADE_OUT_PARAM; // 0x0
	private Boolean m_lockFlag; // 0x81
	private TemplateMissionViewModel m_cacheViewModel; // 0x88
	public Single animDelta; // 0x90
	public Action`1 missionGroupClick; // 0x98
	public Action`1 receiveAllMissionGroupClick; // 0xa0
	public Boolean showAllInfoFlag; // 0xa8
	private Boolean m_needToPlayAnim; // 0xa9
	private Boolean m_lastTimeData; // 0xaa
	private static DelegateBridge __Hotfix0__CheckSame; // 0x0
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_RenderViewAct13Side; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x18
	private static DelegateBridge __Hotfix0_RenderCor; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_RenderCoro; // 0x30
	private static DelegateBridge __Hotfix0_IsAvailClick; // 0x38
	private static DelegateBridge __Hotfix0_OnAllClick; // 0x40
	private static DelegateBridge __Hotfix0_OnReceiveAllClick; // 0x48
	private static DelegateBridge __Hotfix0_OnGoToStageClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x34419c8 VA: 0x7595a599c8
	private static Boolean _CheckSame(TemplateMissionViewModel missionData1, TemplateMissionViewModel missionData2) { }
	// RVA: 0x3441ad4 VA: 0x7595a59ad4
	public Void ApplyDataBundle(TemplateMissionViewModel missionData) { }
	// RVA: 0x3441b90 VA: 0x7595a59b90
	public Void RenderViewAct13Side() { }
	// RVA: 0x34420a4 VA: 0x7595a5a0a4
	private Void _PlayAnim(Action commonRender) { }
	// RVA: 0x34423bc VA: 0x7595a5a3bc
	private IEnumerator RenderCor(Action commonRender) { }
	// RVA: 0x3442168 VA: 0x7595a5a168
	public Void Render(Action commonRender) { }
	// RVA: 0x34424b4 VA: 0x7595a5a4b4
	public Void RenderCoro(Action commonRender) { }
	// RVA: 0x3442610 VA: 0x7595a5a610
	public Boolean IsAvailClick() { }
	// RVA: 0x3442680 VA: 0x7595a5a680
	public Void OnAllClick() { }
	// RVA: 0x3442744 VA: 0x7595a5a744
	public Void OnReceiveAllClick() { }
	// RVA: 0x3442808 VA: 0x7595a5a808
	public Void OnGoToStageClick() { }
	// RVA: 0x34428a8 VA: 0x7595a5a8a8
	public Void .ctor() { }
}
```