# Act1LockStageBtn

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `InterlockStageType _stageType`

- `Text _stageCode`

- `StageRankViewViaSwitch _stageRank`

- `GameObject _selected`

- `UIColorGraphic _uIColorGraphic`

- `Color _selectedColor`

- `GameObject _interlockPanel`

- `GameObject _finalPanel`

- `AnimationWrapper _animation`

- `Image _stageEnemyIcon`

- `Image _stageEnemyBg`

- `Image _interLockAssistIcon`

- `GameObject _interLockAssistPanel`

- `Text _interLockAssistCount`

- `GameObject _interLockHasSquad`

- `GameObject _interLockNonSquad`

- `Image _interLockAsssitBg`

- `GameObject _interLockUseSpAssist`

- `Color _interLockedColor`

- `Color _interNormalColor`

- `Act1LockStageViewModel m_cachedViewModel`

- `Boolean m_inited`


## Properties

- `InterlockStageType stageType`

- `AnimationWrapper animWrapper`


## Methods

- `Boolean RenderStageBtn(Act1LockStageViewModel, String)`

- `Void _InitIfNot()`

- `Void _RenderBtn(Act1LockStageViewModel)`

- `Boolean _TryLockStage()`

- `Boolean _CheckStageLocked(Act1LockStageViewModel)`

- `Void _RenderInterLockInfo()`

- `Void _RenderFinalInfo()`

- `Void OnEventClick()`

- `InterlockStageType get_stageType()`

- `AnimationWrapper get_animWrapper()`

- `Boolean _ApplySelect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockStageBtn : MonoBehaviour, IHotfixable
{
	private InterlockStageType _stageType; // 0x18
	private Text _stageCode; // 0x20
	private StageRankViewViaSwitch _stageRank; // 0x28
	private GameObject _selected; // 0x30
	private UIColorGraphic _uIColorGraphic; // 0x38
	private Color _selectedColor; // 0x40
	private GameObject _interlockPanel; // 0x50
	private GameObject _finalPanel; // 0x58
	private Act1LockInterlockStageStatusView[] _interLockStageStatus; // 0x60
	private AnimationWrapper _animation; // 0x68
	private Image _stageEnemyIcon; // 0x70
	private Image _stageEnemyBg; // 0x78
	private Image _interLockAssistIcon; // 0x80
	private GameObject _interLockAssistPanel; // 0x88
	private Text _interLockAssistCount; // 0x90
	private GameObject _interLockHasSquad; // 0x98
	private GameObject _interLockNonSquad; // 0xa0
	private Image _interLockAsssitBg; // 0xa8
	private GameObject _interLockUseSpAssist; // 0xb0
	private Color _interLockedColor; // 0xb8
	private Color _interNormalColor; // 0xc8
	public Action`1 onStageClick; // 0xd8
	private Act1LockStageViewModel m_cachedViewModel; // 0xe0
	private Boolean m_inited; // 0xe8
	private static DelegateBridge __Hotfix0_RenderStageBtn; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderBtn; // 0x10
	private static DelegateBridge __Hotfix0__TryLockStage; // 0x18
	private static DelegateBridge __Hotfix0__CheckStageLocked; // 0x20
	private static DelegateBridge __Hotfix0__RenderInterLockInfo; // 0x28
	private static DelegateBridge __Hotfix0__RenderFinalInfo; // 0x30
	private static DelegateBridge __Hotfix0_OnEventClick; // 0x38
	private static DelegateBridge __Hotfix0_get_stageType; // 0x40
	private static DelegateBridge __Hotfix0_get_animWrapper; // 0x48
	private static DelegateBridge __Hotfix0__ApplySelect; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public InterlockStageType stageType { get; }
	public AnimationWrapper animWrapper { get; }

	// RVA: 0x33cf3d0 VA: 0x75959e73d0
	public Boolean RenderStageBtn(Act1LockStageViewModel stageViewModel, String selectedStageId) { }
	// RVA: 0x33d36f4 VA: 0x75959eb6f4
	private Void _InitIfNot() { }
	// RVA: 0x33d3768 VA: 0x75959eb768
	private Void _RenderBtn(Act1LockStageViewModel stageViewModel) { }
	// RVA: 0x33d3ae0 VA: 0x75959ebae0
	private Boolean _TryLockStage() { }
	// RVA: 0x33d3a44 VA: 0x75959eba44
	private Boolean _CheckStageLocked(Act1LockStageViewModel viewModel) { }
	// RVA: 0x33d3b60 VA: 0x75959ebb60
	private Void _RenderInterLockInfo() { }
	// RVA: 0x33d3ee0 VA: 0x75959ebee0
	private Void _RenderFinalInfo() { }
	// RVA: 0x33d41c0 VA: 0x75959ec1c0
	public Void OnEventClick() { }
	// RVA: 0x33d4250 VA: 0x75959ec250
	public InterlockStageType get_stageType() { }
	// RVA: 0x33d42b8 VA: 0x75959ec2b8
	public AnimationWrapper get_animWrapper() { }
	// RVA: 0x33d3908 VA: 0x75959eb908
	private Boolean _ApplySelect(String stageId) { }
	// RVA: 0x33d4320 VA: 0x75959ec320
	public Void .ctor() { }
}
```