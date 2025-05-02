# Act13sideDailyMissionItemView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _normalPartGo`

- `GameObject _completeMaskGo`

- `GameObject _emptyPartGo`

- `GameObject _navPartGo`

- `GameObject _battleEndGo`

- `Text _textPrincipalName`

- `Text _textMissionName`

- `Text _textMissionDesc`

- `Text _textPrestigeDesc`

- `Text _textAgenda`

- `Image _imgOrgLogo`

- `Image _imgPrincipalBg`

- `GameObject _btnNavGo`

- `GameObject _btnCommitGo`

- `SimpleLayoutContent _rewardList`

- `Single _itemCardScale`

- `UIAnimationLocation _completeAnim`

- `Button _btnNavToPool`

- `Action <onNavToPool>k__BackingField`

- `Int32 m_boardIdx`

- `Act13sideDailyMissionItemViewModel m_itemModel`

- `Adapter m_adapter`


## Properties

- `Button btnNavToPool`

- `Action onNavToPool`


## Methods

- `Button get_btnNavToPool()`

- `Void set_onMissionCancel(Action`1)`

- `Void set_onMissionCommit(Action`1)`

- `Action get_onNavToPool()`

- `Void set_onNavToPool(Action)`

- `Void set_onNavToStage(Action`1)`

- `Void Render(String, Int32, Int32, Act13sideDailyMissionItemViewModel)`

- `Void PlayCompleAnim(Action)`

- `Void OnBtnCommit()`

- `Void OnBtnCancel()`

- `Void OnNavToPool()`

- `Void OnNavToStage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionItemView : MonoBehaviour, IHotfixable
{
	private GameObject _normalPartGo; // 0x18
	private GameObject _completeMaskGo; // 0x20
	private GameObject _emptyPartGo; // 0x28
	private GameObject _navPartGo; // 0x30
	private GameObject _battleEndGo; // 0x38
	private Text _textPrincipalName; // 0x40
	private Text _textMissionName; // 0x48
	private Text _textMissionDesc; // 0x50
	private Text _textPrestigeDesc; // 0x58
	private Text _textAgenda; // 0x60
	private Image _imgOrgLogo; // 0x68
	private Image _imgPrincipalBg; // 0x70
	private GameObject _btnNavGo; // 0x78
	private GameObject _btnCommitGo; // 0x80
	private SimpleLayoutContent _rewardList; // 0x88
	private Single _itemCardScale; // 0x90
	private UIAnimationLocation _completeAnim; // 0x98
	private Button _btnNavToPool; // 0xa8
	private Action`1 <onMissionCancel>k__BackingField; // 0xb0
	private Action`1 <onMissionCommit>k__BackingField; // 0xb8
	private Action <onNavToPool>k__BackingField; // 0xc0
	private Action`1 <onNavToStage>k__BackingField; // 0xc8
	private Int32 m_boardIdx; // 0xd0
	private Act13sideDailyMissionItemViewModel m_itemModel; // 0xd8
	private Adapter m_adapter; // 0xe0
	private static DelegateBridge __Hotfix0_get_btnNavToPool; // 0x0
	private static DelegateBridge __Hotfix0_get_onMissionCancel; // 0x8
	private static DelegateBridge __Hotfix0_set_onMissionCancel; // 0x10
	private static DelegateBridge __Hotfix0_get_onMissionCommit; // 0x18
	private static DelegateBridge __Hotfix0_set_onMissionCommit; // 0x20
	private static DelegateBridge __Hotfix0_get_onNavToPool; // 0x28
	private static DelegateBridge __Hotfix0_set_onNavToPool; // 0x30
	private static DelegateBridge __Hotfix0_get_onNavToStage; // 0x38
	private static DelegateBridge __Hotfix0_set_onNavToStage; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x48
	private static DelegateBridge __Hotfix0_PlayCompleAnim; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnCommit; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnCancel; // 0x60
	private static DelegateBridge __Hotfix0_OnNavToPool; // 0x68
	private static DelegateBridge __Hotfix0_OnNavToStage; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Button btnNavToPool { get; }
	private Action`1 onMissionCancel { get; set; }
	private Action`1 onMissionCommit { get; set; }
	private Action onNavToPool { get; set; }
	private Action`1 onNavToStage { get; set; }

	// RVA: 0x343a0d4 VA: 0x7595a520d4
	public Button get_btnNavToPool() { }
	// RVA: 0x343a13c VA: 0x7595a5213c
	private Action`1 get_onMissionCancel() { }
	// RVA: 0x343a1a4 VA: 0x7595a521a4
	public Void set_onMissionCancel(Action`1 value) { }
	// RVA: 0x343a228 VA: 0x7595a52228
	private Action`1 get_onMissionCommit() { }
	// RVA: 0x343a290 VA: 0x7595a52290
	public Void set_onMissionCommit(Action`1 value) { }
	// RVA: 0x343a314 VA: 0x7595a52314
	private Action get_onNavToPool() { }
	// RVA: 0x343a37c VA: 0x7595a5237c
	public Void set_onNavToPool(Action value) { }
	// RVA: 0x343a400 VA: 0x7595a52400
	private Action`1 get_onNavToStage() { }
	// RVA: 0x343a468 VA: 0x7595a52468
	public Void set_onNavToStage(Action`1 value) { }
	// RVA: 0x343a4ec VA: 0x7595a524ec
	public Void Render(String actId, Int32 position, Int32 boardMax, Act13sideDailyMissionItemViewModel itemModel) { }
	// RVA: 0x343aa80 VA: 0x7595a52a80
	public Void PlayCompleAnim(Action onComplete) { }
	// RVA: 0x343ac14 VA: 0x7595a52c14
	public Void OnBtnCommit() { }
	// RVA: 0x343acb4 VA: 0x7595a52cb4
	public Void OnBtnCancel() { }
	// RVA: 0x343ad54 VA: 0x7595a52d54
	public Void OnNavToPool() { }
	// RVA: 0x343adf0 VA: 0x7595a52df0
	public Void OnNavToStage() { }
	// RVA: 0x343aea4 VA: 0x7595a52ea4
	public Void .ctor() { }
}
```