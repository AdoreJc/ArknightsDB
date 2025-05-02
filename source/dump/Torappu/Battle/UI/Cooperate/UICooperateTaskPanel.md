# UICooperateTaskPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Text _stageInfo`

- `String _stageInfoFromMap`

- `String _stageNameFromMap`

- `CooperateGameMode m_gameMode`

- `CooperateUIPlugin m_plugin`

- `Boolean m_isResting`

- `Boolean <isBasicStage>k__BackingField`

- `UICooperateTaskView <taskView>k__BackingField`


## Properties

- `Text stageInfo`

- `Boolean isBasicStage`

- `UICooperateTaskView taskView`


## Methods

- `Text get_stageInfo()`

- `Boolean get_isBasicStage()`

- `Void set_isBasicStage(Boolean)`

- `UICooperateTaskView get_taskView()`

- `Void set_taskView(UICooperateTaskView)`

- `Void set_registBuff(ObjectPtr`1)`

- `Void set_progressBuff(ObjectPtr`1)`

- `Void InitTask(ObjectPtr`1, CooperateGameMode, CooperateUIPlugin)`

- `Void UpdateProgeressBuff(ObjectPtr`1)`

- `Void SetFontSize(FP)`

- `Void AddProgress(Boolean, String, String)`

- `Void SetProgressSlider(FP)`

- `Void SetProgressSlider(FP, FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateTaskPanel : MonoBehaviour, IHotfixable
{
	private Text _stageInfo; // 0x18
	private String _stageInfoFromMap; // 0x20
	private String _stageNameFromMap; // 0x28
	protected const String STAGE_INFO_FORMAT; // 0x0
	protected const String SCORE_FORMAT; // 0x0
	protected const String INFO_FORMAT; // 0x0
	private const Int32 BASIC_FONT_TOLERANCE; // 0x0
	private const Single PROGRESS_COMPARE_OFFSET; // 0x0
	protected CooperateGameMode m_gameMode; // 0x30
	protected CooperateUIPlugin m_plugin; // 0x38
	protected Boolean m_isResting; // 0x40
	private Boolean <isBasicStage>k__BackingField; // 0x41
	private UICooperateTaskView <taskView>k__BackingField; // 0x48
	private ObjectPtr`1 <registBuff>k__BackingField; // 0x50
	private ObjectPtr`1 <progressBuff>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_stageInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_isBasicStage; // 0x8
	private static DelegateBridge __Hotfix0_set_isBasicStage; // 0x10
	private static DelegateBridge __Hotfix0_get_taskView; // 0x18
	private static DelegateBridge __Hotfix0_set_taskView; // 0x20
	private static DelegateBridge __Hotfix0_get_registBuff; // 0x28
	private static DelegateBridge __Hotfix0_set_registBuff; // 0x30
	private static DelegateBridge __Hotfix0_get_progressBuff; // 0x38
	private static DelegateBridge __Hotfix0_set_progressBuff; // 0x40
	private static DelegateBridge __Hotfix0_get_type; // 0x48
	private static DelegateBridge __Hotfix0_InitTask; // 0x50
	private static DelegateBridge __Hotfix0_LoadDataFromBuff; // 0x58
	private static DelegateBridge __Hotfix0_UpdateProgeressBuff; // 0x60
	private static DelegateBridge __Hotfix0_GetProgerss; // 0x68
	private static DelegateBridge __Hotfix0_SetFontSize; // 0x70
	private static DelegateBridge __Hotfix0_UpdatePanelFixed; // 0x78
	private static DelegateBridge __Hotfix0_UpdatePanel; // 0x80
	private static DelegateBridge __Hotfix0_StopTimerAnim; // 0x88
	private static DelegateBridge __Hotfix0_StageEndAnim; // 0x90
	private static DelegateBridge __Hotfix0_AddProgress; // 0x98
	private static DelegateBridge __Hotfix0_SetProgressSlider; // 0xa0
	private static DelegateBridge __Hotfix1_SetProgressSlider; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	protected Text stageInfo { get; }
	public Boolean isBasicStage { get; set; }
	public UICooperateTaskView taskView { get; set; }
	protected ObjectPtr`1 registBuff { get; set; }
	protected ObjectPtr`1 progressBuff { get; set; }
	public virtual CoopStageType type { get; }

	// RVA: 0x20d6bb4 VA: 0x75946eebb4
	protected Text get_stageInfo() { }
	// RVA: 0x20d3810 VA: 0x75946eb810
	public Boolean get_isBasicStage() { }
	// RVA: 0x20d6c1c VA: 0x75946eec1c
	private Void set_isBasicStage(Boolean value) { }
	// RVA: 0x20d36d0 VA: 0x75946eb6d0
	public UICooperateTaskView get_taskView() { }
	// RVA: 0x20d6c9c VA: 0x75946eec9c
	public Void set_taskView(UICooperateTaskView value) { }
	// RVA: 0x20d366c VA: 0x75946eb66c
	protected ObjectPtr`1 get_registBuff() { }
	// RVA: 0x20d6d20 VA: 0x75946eed20
	private Void set_registBuff(ObjectPtr`1 value) { }
	// RVA: 0x20d42ac VA: 0x75946ec2ac
	protected ObjectPtr`1 get_progressBuff() { }
	// RVA: 0x20d6db0 VA: 0x75946eedb0
	private Void set_progressBuff(ObjectPtr`1 value) { }
	// RVA: 0x20d4e4c VA: 0x75946ece4c
	public virtual CoopStageType get_type() { }
	// RVA: 0x20d6e40 VA: 0x75946eee40
	public Void InitTask(ObjectPtr`1 buff, CooperateGameMode gameMode, CooperateUIPlugin uiPlugin) { }
	// RVA: 0x20d34d4 VA: 0x75946eb4d4
	public virtual Void LoadDataFromBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20d70b8 VA: 0x75946ef0b8
	public Void UpdateProgeressBuff(ObjectPtr`1 buff) { }
	// RVA: 0x20d4eb8 VA: 0x75946eceb8
	public virtual Void GetProgerss(Int32 curScore) { }
	// RVA: 0x20d3964 VA: 0x75946eb964
	protected Void SetFontSize(FP cnt) { }
	// RVA: 0x20d4200 VA: 0x75946ec200
	public virtual Void UpdatePanelFixed() { }
	// RVA: 0x20d4f38 VA: 0x75946ecf38
	public virtual Void UpdatePanel() { }
	// RVA: 0x20d72d8 VA: 0x75946ef2d8
	public virtual Void StopTimerAnim() { }
	// RVA: 0x20d7474 VA: 0x75946ef474
	public virtual Void StageEndAnim() { }
	// RVA: 0x20d3d04 VA: 0x75946ebd04
	protected Void AddProgress(Boolean complete, String progress, String max) { }
	// RVA: 0x20d47a0 VA: 0x75946ec7a0
	protected Void SetProgressSlider(FP progress) { }
	// RVA: 0x20d48e0 VA: 0x75946ec8e0
	protected Void SetProgressSlider(FP progress, FP basicProgress) { }
	// RVA: 0x20d4dd8 VA: 0x75946ecdd8
	public Void .ctor() { }
}
```