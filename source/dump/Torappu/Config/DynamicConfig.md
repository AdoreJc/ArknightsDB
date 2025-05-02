# DynamicConfig

**Namespace:** `Torappu.Config`


## Fields

- `InternalConfig m_config`


## Properties

- `Boolean disableLuaTick`

- `Boolean disableMinorAlert`

- `Boolean disableAutoReplayCleanup`

- `Boolean defaultServiceLicenseSelect`

- `Boolean defaultRegisterPolicySelect`

- `Boolean enableDelayUpdateTileForEnemy`

- `Boolean alertIfLuaValidationFailed`

- `Boolean exitGameIfLuaValidationFailed`

- `Boolean enableLicenseUpdate`

- `Boolean enableListPool`

- `Boolean preloadAudioFromBuff`

- `Boolean preloadAudioFromEnvManager`

- `Boolean preloadAudioFromEffect`

- `Boolean enableBattleLua`

- `Int32 preloadBuffEffectExtraDepth`

- `Boolean exitGameIfTableValidationFailed`

- `Boolean enableSkipIdentityVerify`

- `Boolean enableLoginIdentityVerify`

- `Boolean keepGuestWhenClearCache`

- `Boolean enableTwoStepIdentityVerify`

- `Boolean enableHgsdkPing`

- `Boolean enableHgsdkPingInBattle`

- `Int32 defaultPingIntervalIfFailed`

- `Boolean enablePreloadSpineAudioEvent`

- `Boolean enableBackPress`

- `Boolean useRecycleToFinishScheduler`

- `Boolean enableAppetizer`

- `Boolean webViewUseInstCenter`

- `Boolean enableMultiCurrency`

- `Boolean enableUndeterDirtyFix`

- `Boolean enableGachaAudioPreload`

- `Boolean enableBuildingReflection`

- `Boolean enableLoginoutRequest`

- `Boolean enableUIDelayUnload`

- `Boolean enableManyUIUUA`

- `Int32 minSyncStatusInterval`

- `Boolean alwaysMoveNextWhenPause`

- `Boolean dynIllustStartClearBGM`

- `Boolean enableLargeIllustRT`

- `Boolean disableIllustStencil`

- `Boolean disableFlatDB`


## Methods

- `Boolean get_disableLuaTick()`

- `Boolean get_disableMinorAlert()`

- `Boolean get_disableAutoReplayCleanup()`

- `Boolean get_defaultServiceLicenseSelect()`

- `Boolean get_defaultRegisterPolicySelect()`

- `Boolean get_enableDelayUpdateTileForEnemy()`

- `Boolean get_alertIfLuaValidationFailed()`

- `Boolean get_exitGameIfLuaValidationFailed()`

- `Boolean get_enableLicenseUpdate()`

- `Boolean get_enableListPool()`

- `Boolean get_preloadAudioFromBuff()`

- `Boolean get_preloadAudioFromEnvManager()`

- `Boolean get_preloadAudioFromEffect()`

- `Boolean get_enableBattleLua()`

- `Int32 get_preloadBuffEffectExtraDepth()`

- `Boolean get_exitGameIfTableValidationFailed()`

- `Boolean get_enableSkipIdentityVerify()`

- `Boolean get_enableLoginIdentityVerify()`

- `Boolean get_keepGuestWhenClearCache()`

- `Boolean get_enableTwoStepIdentityVerify()`

- `Boolean get_enableHgsdkPing()`

- `Boolean get_enableHgsdkPingInBattle()`

- `Int32 get_defaultPingIntervalIfFailed()`

- `Boolean get_enablePreloadSpineAudioEvent()`

- `Boolean get_enableBackPress()`

- `Boolean get_useRecycleToFinishScheduler()`

- `Boolean get_enableAppetizer()`

- `Boolean get_webViewUseInstCenter()`

- `Boolean get_enableMultiCurrency()`

- `Boolean get_enableUndeterDirtyFix()`

- `Boolean get_enableGachaAudioPreload()`

- `Boolean get_enableBuildingReflection()`

- `Boolean get_enableLoginoutRequest()`

- `Boolean get_enableUIDelayUnload()`

- `Boolean get_enableManyUIUUA()`

- `Int32 get_minSyncStatusInterval()`

- `Boolean get_alwaysMoveNextWhenPause()`

- `Boolean get_dynIllustStartClearBGM()`

- `Boolean get_enableLargeIllustRT()`

- `Boolean get_disableIllustStencil()`

- `Boolean get_disableFlatDB()`

- `Boolean Load()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Config
public class DynamicConfig : Singleton`1
{
	private InternalConfig m_config; // 0x10
	private static DelegateBridge __Hotfix0_get_disableLuaTick; // 0x0
	private static DelegateBridge __Hotfix0_get_disableMinorAlert; // 0x8
	private static DelegateBridge __Hotfix0_get_disableAutoReplayCleanup; // 0x10
	private static DelegateBridge __Hotfix0_get_defaultServiceLicenseSelect; // 0x18
	private static DelegateBridge __Hotfix0_get_defaultRegisterPolicySelect; // 0x20
	private static DelegateBridge __Hotfix0_get_enableDelayUpdateTileForEnemy; // 0x28
	private static DelegateBridge __Hotfix0_get_alertIfLuaValidationFailed; // 0x30
	private static DelegateBridge __Hotfix0_get_exitGameIfLuaValidationFailed; // 0x38
	private static DelegateBridge __Hotfix0_get_enableLicenseUpdate; // 0x40
	private static DelegateBridge __Hotfix0_get_enableListPool; // 0x48
	private static DelegateBridge __Hotfix0_get_preloadAudioFromBuff; // 0x50
	private static DelegateBridge __Hotfix0_get_preloadAudioFromEnvManager; // 0x58
	private static DelegateBridge __Hotfix0_get_preloadAudioFromEffect; // 0x60
	private static DelegateBridge __Hotfix0_get_enableBattleLua; // 0x68
	private static DelegateBridge __Hotfix0_get_preloadBuffEffectExtraDepth; // 0x70
	private static DelegateBridge __Hotfix0_get_exitGameIfTableValidationFailed; // 0x78
	private static DelegateBridge __Hotfix0_get_enableSkipIdentityVerify; // 0x80
	private static DelegateBridge __Hotfix0_get_enableLoginIdentityVerify; // 0x88
	private static DelegateBridge __Hotfix0_get_keepGuestWhenClearCache; // 0x90
	private static DelegateBridge __Hotfix0_get_enableTwoStepIdentityVerify; // 0x98
	private static DelegateBridge __Hotfix0_get_enableHgsdkPing; // 0xa0
	private static DelegateBridge __Hotfix0_get_enableHgsdkPingInBattle; // 0xa8
	private static DelegateBridge __Hotfix0_get_defaultPingIntervalIfFailed; // 0xb0
	private static DelegateBridge __Hotfix0_get_enablePreloadSpineAudioEvent; // 0xb8
	private static DelegateBridge __Hotfix0_get_enableBackPress; // 0xc0
	private static DelegateBridge __Hotfix0_get_useRecycleToFinishScheduler; // 0xc8
	private static DelegateBridge __Hotfix0_get_enableAppetizer; // 0xd0
	private static DelegateBridge __Hotfix0_get_webViewUseInstCenter; // 0xd8
	private static DelegateBridge __Hotfix0_get_enableMultiCurrency; // 0xe0
	private static DelegateBridge __Hotfix0_get_enableUndeterDirtyFix; // 0xe8
	private static DelegateBridge __Hotfix0_get_enableGachaAudioPreload; // 0xf0
	private static DelegateBridge __Hotfix0_get_enableBuildingReflection; // 0xf8
	private static DelegateBridge __Hotfix0_get_enableLoginoutRequest; // 0x100
	private static DelegateBridge __Hotfix0_get_enableUIDelayUnload; // 0x108
	private static DelegateBridge __Hotfix0_get_enableManyUIUUA; // 0x110
	private static DelegateBridge __Hotfix0_get_minSyncStatusInterval; // 0x118
	private static DelegateBridge __Hotfix0_get_alwaysMoveNextWhenPause; // 0x120
	private static DelegateBridge __Hotfix0_get_dynIllustStartClearBGM; // 0x128
	private static DelegateBridge __Hotfix0_get_enableLargeIllustRT; // 0x130
	private static DelegateBridge __Hotfix0_get_disableIllustStencil; // 0x138
	private static DelegateBridge __Hotfix0_get_disableFlatDB; // 0x140
	private static DelegateBridge __Hotfix0_Load; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public Boolean disableLuaTick { get; }
	public Boolean disableMinorAlert { get; }
	public Boolean disableAutoReplayCleanup { get; }
	public Boolean defaultServiceLicenseSelect { get; }
	public Boolean defaultRegisterPolicySelect { get; }
	public Boolean enableDelayUpdateTileForEnemy { get; }
	public Boolean alertIfLuaValidationFailed { get; }
	public Boolean exitGameIfLuaValidationFailed { get; }
	public Boolean enableLicenseUpdate { get; }
	public Boolean enableListPool { get; }
	public Boolean preloadAudioFromBuff { get; }
	public Boolean preloadAudioFromEnvManager { get; }
	public Boolean preloadAudioFromEffect { get; }
	public Boolean enableBattleLua { get; }
	public Int32 preloadBuffEffectExtraDepth { get; }
	public Boolean exitGameIfTableValidationFailed { get; }
	public Boolean enableSkipIdentityVerify { get; }
	public Boolean enableLoginIdentityVerify { get; }
	public Boolean keepGuestWhenClearCache { get; }
	public Boolean enableTwoStepIdentityVerify { get; }
	public Boolean enableHgsdkPing { get; }
	public Boolean enableHgsdkPingInBattle { get; }
	public Int32 defaultPingIntervalIfFailed { get; }
	public Boolean enablePreloadSpineAudioEvent { get; }
	public Boolean enableBackPress { get; }
	public Boolean useRecycleToFinishScheduler { get; }
	public Boolean enableAppetizer { get; }
	public Boolean webViewUseInstCenter { get; }
	public Boolean enableMultiCurrency { get; }
	public Boolean enableUndeterDirtyFix { get; }
	public Boolean enableGachaAudioPreload { get; }
	public Boolean enableBuildingReflection { get; }
	public Boolean enableLoginoutRequest { get; }
	public Boolean enableUIDelayUnload { get; }
	public Boolean enableManyUIUUA { get; }
	public Int32 minSyncStatusInterval { get; }
	public Boolean alwaysMoveNextWhenPause { get; }
	public Boolean dynIllustStartClearBGM { get; }
	public Boolean enableLargeIllustRT { get; }
	public Boolean disableIllustStencil { get; }
	public Boolean disableFlatDB { get; }

	// RVA: 0x3725208 VA: 0x7595d3d208
	public Boolean get_disableLuaTick() { }
	// RVA: 0x372527c VA: 0x7595d3d27c
	public Boolean get_disableMinorAlert() { }
	// RVA: 0x37252f0 VA: 0x7595d3d2f0
	public Boolean get_disableAutoReplayCleanup() { }
	// RVA: 0x3725364 VA: 0x7595d3d364
	public Boolean get_defaultServiceLicenseSelect() { }
	// RVA: 0x37253d8 VA: 0x7595d3d3d8
	public Boolean get_defaultRegisterPolicySelect() { }
	// RVA: 0x372544c VA: 0x7595d3d44c
	public Boolean get_enableDelayUpdateTileForEnemy() { }
	// RVA: 0x37254c0 VA: 0x7595d3d4c0
	public Boolean get_alertIfLuaValidationFailed() { }
	// RVA: 0x3725534 VA: 0x7595d3d534
	public Boolean get_exitGameIfLuaValidationFailed() { }
	// RVA: 0x37255a8 VA: 0x7595d3d5a8
	public Boolean get_enableLicenseUpdate() { }
	// RVA: 0x372561c VA: 0x7595d3d61c
	public Boolean get_enableListPool() { }
	// RVA: 0x3725690 VA: 0x7595d3d690
	public Boolean get_preloadAudioFromBuff() { }
	// RVA: 0x3725704 VA: 0x7595d3d704
	public Boolean get_preloadAudioFromEnvManager() { }
	// RVA: 0x3725778 VA: 0x7595d3d778
	public Boolean get_preloadAudioFromEffect() { }
	// RVA: 0x37257ec VA: 0x7595d3d7ec
	public Boolean get_enableBattleLua() { }
	// RVA: 0x3725860 VA: 0x7595d3d860
	public Int32 get_preloadBuffEffectExtraDepth() { }
	// RVA: 0x37258d4 VA: 0x7595d3d8d4
	public Boolean get_exitGameIfTableValidationFailed() { }
	// RVA: 0x3725948 VA: 0x7595d3d948
	public Boolean get_enableSkipIdentityVerify() { }
	// RVA: 0x37259bc VA: 0x7595d3d9bc
	public Boolean get_enableLoginIdentityVerify() { }
	// RVA: 0x3725a30 VA: 0x7595d3da30
	public Boolean get_keepGuestWhenClearCache() { }
	// RVA: 0x3725aa4 VA: 0x7595d3daa4
	public Boolean get_enableTwoStepIdentityVerify() { }
	// RVA: 0x3725b18 VA: 0x7595d3db18
	public Boolean get_enableHgsdkPing() { }
	// RVA: 0x3725b8c VA: 0x7595d3db8c
	public Boolean get_enableHgsdkPingInBattle() { }
	// RVA: 0x3725c00 VA: 0x7595d3dc00
	public Int32 get_defaultPingIntervalIfFailed() { }
	// RVA: 0x3725c74 VA: 0x7595d3dc74
	public Boolean get_enablePreloadSpineAudioEvent() { }
	// RVA: 0x3725ce8 VA: 0x7595d3dce8
	public Boolean get_enableBackPress() { }
	// RVA: 0x3725d5c VA: 0x7595d3dd5c
	public Boolean get_useRecycleToFinishScheduler() { }
	// RVA: 0x3725dd0 VA: 0x7595d3ddd0
	public Boolean get_enableAppetizer() { }
	// RVA: 0x3725e44 VA: 0x7595d3de44
	public Boolean get_webViewUseInstCenter() { }
	// RVA: 0x3725eb8 VA: 0x7595d3deb8
	public Boolean get_enableMultiCurrency() { }
	// RVA: 0x3725f2c VA: 0x7595d3df2c
	public Boolean get_enableUndeterDirtyFix() { }
	// RVA: 0x3725fa0 VA: 0x7595d3dfa0
	public Boolean get_enableGachaAudioPreload() { }
	// RVA: 0x3726014 VA: 0x7595d3e014
	public Boolean get_enableBuildingReflection() { }
	// RVA: 0x3726088 VA: 0x7595d3e088
	public Boolean get_enableLoginoutRequest() { }
	// RVA: 0x37260fc VA: 0x7595d3e0fc
	public Boolean get_enableUIDelayUnload() { }
	// RVA: 0x3726170 VA: 0x7595d3e170
	public Boolean get_enableManyUIUUA() { }
	// RVA: 0x37261e4 VA: 0x7595d3e1e4
	public Int32 get_minSyncStatusInterval() { }
	// RVA: 0x3726258 VA: 0x7595d3e258
	public Boolean get_alwaysMoveNextWhenPause() { }
	// RVA: 0x37262cc VA: 0x7595d3e2cc
	public Boolean get_dynIllustStartClearBGM() { }
	// RVA: 0x3726340 VA: 0x7595d3e340
	public Boolean get_enableLargeIllustRT() { }
	// RVA: 0x37263b4 VA: 0x7595d3e3b4
	public Boolean get_disableIllustStencil() { }
	// RVA: 0x3726428 VA: 0x7595d3e428
	public Boolean get_disableFlatDB() { }
	// RVA: 0x372649c VA: 0x7595d3e49c
	public Boolean Load() { }
	// RVA: 0x37269cc VA: 0x7595d3e9cc
	private Void .ctor() { }
}
```