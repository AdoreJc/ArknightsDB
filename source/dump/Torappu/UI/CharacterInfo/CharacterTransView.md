# CharacterTransView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _confirmingPanel`

- `GameObject _contentPanel`

- `Single _fadeDuration`

- `Image _confirmingPanelBG`

- `GameObject _skillTrainingPanel`

- `Text _skillTrainingCDText`

- `Image _skillTrainingProgressCircle`

- `MotionController _motionController`

- `Transform _effectLayerHierarchyRoot`

- `Shader _shaderUIRTPS`

- `GameObject _redEffect`

- `GameObject _blackEffect`

- `GameObject _whiteEffect`

- `Int32 _itemCount`

- `Action m_clickCurrentCallback`

- `Boolean m_readyToConfirm`

- `Int32 m_confirmSelectionIndex`

- `Boolean m_transValid`

- `Int64 m_trainingStartTS`

- `Int64 m_trainingEndTS`

- `Int64 m_lastRestTS`

- `Int32 m_currentTransIndex`

- `Coroutine m_confirmCoroutine`

- `Coroutine m_introCoroutine`

- `CanvasGroup m_confirmingPanelCanvasGroup`

- `Sprite m_shotSprite`

- `Shader m_shotBlurShader`


## Methods

- `Void Awake()`

- `Void OnDestroy()`

- `Void Update()`

- `String _FormatBuildingRestTime(TimeSpan)`

- `Void _ShotBackground()`

- `Void _UpdateSkillTrainingRestTimeLabel(Int64)`

- `Void _UpdateSkillTrainingProcess(Int64, Int64)`

- `Void _UpdateSkillTraining()`

- `Void _SetupSkillTrainingPart(Int32, Int64, Int64)`

- `Color _GetItemColor(Int32, List`1)`

- `Void Setup(Option, List`1, Shader, Action`1, Action, Func`2)`

- `Void StartIntroMotion()`

- `IEnumerator _StartIntroCoroutine()`

- `IEnumerator _StartConfirmCoroutine(Int32)`

- `Void _OnTransButtonPressed(Int32)`

- `Void OnMedicMarkPressed()`

- `Void OnMagicMarkPressed()`

- `Void OnMeleeMarkPressed()`

- `Void OnPanelCancel()`

- `Void OnPanelConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterTransView : MonoBehaviour, IHotfixable
{
	private GameObject _confirmingPanel; // 0x18
	private GameObject _contentPanel; // 0x20
	private Single _fadeDuration; // 0x28
	private Image _confirmingPanelBG; // 0x30
	private GameObject _skillTrainingPanel; // 0x38
	private Text _skillTrainingCDText; // 0x40
	private Image[] _skillTrainingLevelMarks; // 0x48
	private Image _skillTrainingProgressCircle; // 0x50
	private Transform[] _skillPanelPosition; // 0x58
	private Transform[] _bgEffectPosition; // 0x60
	private GameObject[] _foreEffectRawImage; // 0x68
	private Image[] _transButtonImages; // 0x70
	private EffectLayer[] _effectLayers; // 0x78
	private GameObject[] _effectTransIconPanels; // 0x80
	private MotionController _motionController; // 0x88
	private Transform _effectLayerHierarchyRoot; // 0x90
	private Shader _shaderUIRTPS; // 0x98
	private GameObject _redEffect; // 0xa0
	private GameObject _blackEffect; // 0xa8
	private GameObject _whiteEffect; // 0xb0
	private Int32 _itemCount; // 0xb8
	private List`1 m_effectList; // 0xc0
	private Action`1 m_selectCallback; // 0xc8
	private Action m_clickCurrentCallback; // 0xd0
	private Func`2 m_focusCurrentCallback; // 0xd8
	private Boolean m_readyToConfirm; // 0xe0
	private Int32 m_confirmSelectionIndex; // 0xe4
	private Boolean m_transValid; // 0xe8
	private Int64 m_trainingStartTS; // 0xf0
	private Int64 m_trainingEndTS; // 0xf8
	private Int64 m_lastRestTS; // 0x100
	private Int32 m_currentTransIndex; // 0x108
	private Coroutine m_confirmCoroutine; // 0x110
	private Coroutine m_introCoroutine; // 0x118
	private CanvasGroup m_confirmingPanelCanvasGroup; // 0x120
	private Sprite m_shotSprite; // 0x128
	private List`1 m_shotCameraList; // 0x130
	private Shader m_shotBlurShader; // 0x138
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__FormatBuildingRestTime; // 0x18
	private static DelegateBridge __Hotfix0__ShotBackground; // 0x20
	private static DelegateBridge __Hotfix0__UpdateSkillTrainingRestTimeLabel; // 0x28
	private static DelegateBridge __Hotfix0__UpdateSkillTrainingProcess; // 0x30
	private static DelegateBridge __Hotfix0__UpdateSkillTraining; // 0x38
	private static DelegateBridge __Hotfix0__SetupSkillTrainingPart; // 0x40
	private static DelegateBridge __Hotfix0__GetItemColor; // 0x48
	private static DelegateBridge __Hotfix0_Setup; // 0x50
	private static DelegateBridge __Hotfix0_StartIntroMotion; // 0x58
	private static DelegateBridge __Hotfix0__StartIntroCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__StartConfirmCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__OnTransButtonPressed; // 0x70
	private static DelegateBridge __Hotfix0_OnMedicMarkPressed; // 0x78
	private static DelegateBridge __Hotfix0_OnMagicMarkPressed; // 0x80
	private static DelegateBridge __Hotfix0_OnMeleeMarkPressed; // 0x88
	private static DelegateBridge __Hotfix0_OnPanelCancel; // 0x90
	private static DelegateBridge __Hotfix0_OnPanelConfirm; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2d6c2e4 VA: 0x75953842e4
	private Void Awake() { }
	// RVA: 0x2d6c7d8 VA: 0x75953847d8
	private Void OnDestroy() { }
	// RVA: 0x2d6ca74 VA: 0x7595384a74
	private Void Update() { }
	// RVA: 0x2d6cbb4 VA: 0x7595384bb4
	private String _FormatBuildingRestTime(TimeSpan restTime) { }
	// RVA: 0x2d6cde4 VA: 0x7595384de4
	private Void _ShotBackground() { }
	// RVA: 0x2d6cef0 VA: 0x7595384ef0
	private Void _UpdateSkillTrainingRestTimeLabel(Int64 restTime) { }
	// RVA: 0x2d6d05c VA: 0x759538505c
	private Void _UpdateSkillTrainingProcess(Int64 restTime, Int64 totalTime) { }
	// RVA: 0x2d6cadc VA: 0x7595384adc
	private Void _UpdateSkillTraining() { }
	// RVA: 0x2d6d154 VA: 0x7595385154
	private Void _SetupSkillTrainingPart(Int32 trainingLevel, Int64 trainingStartTS, Int64 trainingEndTS) { }
	// RVA: 0x2d6d2b0 VA: 0x75953852b0
	private Color _GetItemColor(Int32 idx, List`1 unlockList) { }
	// RVA: 0x2d6d39c VA: 0x759538539c
	public Void Setup(Option option, List`1 shotCamList, Shader shotShader, Action`1 onSelect, Action onClickCurrentTmpl, Func`2 getClickFlag) { }
	// RVA: 0x2d6d888 VA: 0x7595385888
	public Void StartIntroMotion() { }
	// RVA: 0x2d6d928 VA: 0x7595385928
	private IEnumerator _StartIntroCoroutine() { }
	// RVA: 0x2d6d9fc VA: 0x75953859fc
	private IEnumerator _StartConfirmCoroutine(Int32 selectIndex) { }
	// RVA: 0x2d6dac0 VA: 0x7595385ac0
	private Void _OnTransButtonPressed(Int32 index) { }
	// RVA: 0x2d6dc50 VA: 0x7595385c50
	public Void OnMedicMarkPressed() { }
	// RVA: 0x2d6dcbc VA: 0x7595385cbc
	public Void OnMagicMarkPressed() { }
	// RVA: 0x2d6dd28 VA: 0x7595385d28
	public Void OnMeleeMarkPressed() { }
	// RVA: 0x2d6dd94 VA: 0x7595385d94
	public Void OnPanelCancel() { }
	// RVA: 0x2d6de04 VA: 0x7595385e04
	public Void OnPanelConfirm() { }
	// RVA: 0x2d6de78 VA: 0x7595385e78
	public Void .ctor() { }
}
```