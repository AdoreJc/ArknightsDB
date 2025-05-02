# GradingController

**Namespace:** `Torappu.Grading`


## Fields

- `SimulatorStatus <simulatorStatus>k__BackingField`


## Properties

- `SimulatorStatus simulatorStatus`

- `Boolean isSimulator`


## Methods

- `SimulatorStatus get_simulatorStatus()`

- `Void set_simulatorStatus(SimulatorStatus)`

- `Boolean get_isSimulator()`

- `Void _Init()`

- `Void _OnSettingChange(SettingType)`

- `Void InitGradingSetting()`

- `Void _DoGradingStep()`

- `Void _InitSettingsAfterAutoGrading()`

- `Void _DoGradingStepFinish()`

- `Void UpdatePPGradingSetting()`

- `Boolean GetGradingSetting(GradingSetting)`

- `Boolean GetGradingSetting(GradingSetting, GradingLevel)`

- `Boolean _Get_PP_COLORGRADING_ViaLevel(GradingLevel)`

- `Boolean _Get_PP_BLOOM_ViaLevel(GradingLevel)`

- `Boolean _Get_PP_VIGNETTE_ViaLevel(GradingLevel)`

- `Boolean _Get_BUILDING_BLOOM_ViaLevel(GradingLevel)`

- `Boolean _Get_SP_WATEREFFECT_ViaLevel(GradingLevel)`

- `Boolean _Get_SP_SHADOWCAMERA_ViaLevel(GradingLevel)`

- `Boolean _Get_SP_ADDITIONAL_LIGHT_ViaLevel(GradingLevel)`

- `Boolean _Get_EnableHighLevelEffect_ViaLevel(GradingLevel)`

- `Boolean _Get_EnableLargeDynIllust_ViaLevel(GradingLevel)`

- `FpsStrategyType _Get_FPS_STRATEGY_ViaLevel(GradingLevel)`

- `Boolean _Get_AntialiasingFlag_ViaLevel(GradingLevel)`

- `Int32 GetValidIndexOfLevel(GradingLevel)`

- `GradingLevel GetLevelViaIndex(Int32)`

- `Void <_DoGradingStep>b__13_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Grading
public class GradingController : Singleton`1, ILuaCallCSharp, IHotfixable
{
	public static DeviceLevel s_oldTestLevel; // 0x0
	private SimulatorStatus <simulatorStatus>k__BackingField; // 0x10
	private static DelegateBridge __Hotfix0_get_simulatorStatus; // 0x8
	private static DelegateBridge __Hotfix0_set_simulatorStatus; // 0x10
	private static DelegateBridge __Hotfix0_get_isSimulator; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0__Init; // 0x28
	private static DelegateBridge __Hotfix0__OnSettingChange; // 0x30
	private static DelegateBridge __Hotfix0_InitGradingSetting; // 0x38
	private static DelegateBridge __Hotfix0__DoGradingStep; // 0x40
	private static DelegateBridge __Hotfix0__InitSettingsAfterAutoGrading; // 0x48
	private static DelegateBridge __Hotfix0__DoGradingStepFinish; // 0x50
	private static DelegateBridge __Hotfix0_UpdatePPGradingSetting; // 0x58
	private static DelegateBridge __Hotfix0_GetGradingSetting; // 0x60
	private static DelegateBridge __Hotfix1_GetGradingSetting; // 0x68
	private static DelegateBridge __Hotfix0__Get_PP_COLORGRADING_ViaLevel; // 0x70
	private static DelegateBridge __Hotfix0__Get_PP_BLOOM_ViaLevel; // 0x78
	private static DelegateBridge __Hotfix0__Get_PP_VIGNETTE_ViaLevel; // 0x80
	private static DelegateBridge __Hotfix0__Get_BUILDING_BLOOM_ViaLevel; // 0x88
	private static DelegateBridge __Hotfix0__Get_SP_WATEREFFECT_ViaLevel; // 0x90
	private static DelegateBridge __Hotfix0__Get_SP_SHADOWCAMERA_ViaLevel; // 0x98
	private static DelegateBridge __Hotfix0__Get_SP_ADDITIONAL_LIGHT_ViaLevel; // 0xa0
	private static DelegateBridge __Hotfix0__Get_EnableHighLevelEffect_ViaLevel; // 0xa8
	private static DelegateBridge __Hotfix0__Get_EnableLargeDynIllust_ViaLevel; // 0xb0
	private static DelegateBridge __Hotfix0__Get_FPS_STRATEGY_ViaLevel; // 0xb8
	private static DelegateBridge __Hotfix0__Get_AntialiasingFlag_ViaLevel; // 0xc0
	private static DelegateBridge __Hotfix0_GetValidIndexOfLevel; // 0xc8
	private static DelegateBridge __Hotfix0_GetLevelViaIndex; // 0xd0

	public SimulatorStatus simulatorStatus { get; set; }
	public Boolean isSimulator { get; }

	// RVA: 0x35c28c8 VA: 0x7595bda8c8
	public SimulatorStatus get_simulatorStatus() { }
	// RVA: 0x35c2940 VA: 0x7595bda940
	private Void set_simulatorStatus(SimulatorStatus value) { }
	// RVA: 0x35c29cc VA: 0x7595bda9cc
	public Boolean get_isSimulator() { }
	// RVA: 0x35c2a50 VA: 0x7595bdaa50
	protected Void .ctor() { }
	// RVA: 0x35c2af8 VA: 0x7595bdaaf8
	private Void _Init() { }
	// RVA: 0x35c2c48 VA: 0x7595bdac48
	private Void _OnSettingChange(SettingType type) { }
	// RVA: 0x35c3038 VA: 0x7595bdb038
	public Void InitGradingSetting() { }
	// RVA: 0x35c30b0 VA: 0x7595bdb0b0
	private Void _DoGradingStep() { }
	// RVA: 0x35c32d8 VA: 0x7595bdb2d8
	private Void _InitSettingsAfterAutoGrading() { }
	// RVA: 0x35c3684 VA: 0x7595bdb684
	private Void _DoGradingStepFinish() { }
	// RVA: 0x35c2cf4 VA: 0x7595bdacf4
	public Void UpdatePPGradingSetting() { }
	// RVA: 0x35c3b00 VA: 0x7595bdbb00
	public Boolean GetGradingSetting(GradingSetting setting) { }
	// RVA: 0x35c394c VA: 0x7595bdb94c
	public Boolean GetGradingSetting(GradingSetting setting, GradingLevel level) { }
	// RVA: 0x35c3c88 VA: 0x7595bdbc88
	private Boolean _Get_PP_COLORGRADING_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3d18 VA: 0x7595bdbd18
	private Boolean _Get_PP_BLOOM_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3dac VA: 0x7595bdbdac
	private Boolean _Get_PP_VIGNETTE_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3e3c VA: 0x7595bdbe3c
	private Boolean _Get_BUILDING_BLOOM_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3ecc VA: 0x7595bdbecc
	private Boolean _Get_SP_WATEREFFECT_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3f60 VA: 0x7595bdbf60
	private Boolean _Get_SP_SHADOWCAMERA_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3ff0 VA: 0x7595bdbff0
	private Boolean _Get_SP_ADDITIONAL_LIGHT_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c4080 VA: 0x7595bdc080
	private Boolean _Get_EnableHighLevelEffect_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c4110 VA: 0x7595bdc110
	private Boolean _Get_EnableLargeDynIllust_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c35f4 VA: 0x7595bdb5f4
	private FpsStrategyType _Get_FPS_STRATEGY_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c38b8 VA: 0x7595bdb8b8
	private Boolean _Get_AntialiasingFlag_ViaLevel(GradingLevel level) { }
	// RVA: 0x35c3560 VA: 0x7595bdb560
	public Int32 GetValidIndexOfLevel(GradingLevel level) { }
	// RVA: 0x35c381c VA: 0x7595bdb81c
	public GradingLevel GetLevelViaIndex(Int32 index) { }
	// RVA: 0x35c41a0 VA: 0x7595bdc1a0
	private static Void .cctor() { }
	// RVA: 0x35c41ec VA: 0x7595bdc1ec
	private Void <_DoGradingStep>b__13_0() { }
}
```