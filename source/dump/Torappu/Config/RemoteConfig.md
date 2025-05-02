# RemoteConfig

**Namespace:** `Torappu.Config`


## Fields

- `InternalConfig m_config`


## Properties

- `Boolean isAuditMode`

- `Boolean enableDBCheck`

- `Boolean enableLuaPlayerData`

- `Boolean enableGameBI`

- `Boolean enableHGSDKPollingConfirm`

- `String inlandAgeTips`

- `Boolean enableFastPlayerDelta`

- `Boolean haltIfHotUpdateUnzipError`

- `Boolean enableHotUpdateLargePack`

- `Boolean enableIAPProdCheck`

- `Boolean disableGuest`

- `Boolean enableNetCheck`

- `Boolean announceUseWeb`

- `Boolean disableBuffTemplateDB`

- `Int32 HGSDKV2`

- `Int32 HGDownload`

- `Boolean enableAsyncResCheck`

- `Int32 effectPreloadStripBound`

- `Boolean enableBattleAnimationLazyLoad`

- `Boolean enableNativeLicense`

- `Boolean enableHGString`

- `Boolean enableFastBattleFinish`

- `Int32 fastAddPages`

- `Int32 fastBattleFinish`

- `Boolean enableCrossAppShare`

- `Int32 margueeType`

- `Boolean renderInvisibleSpine`

- `Boolean renderMultiPlayerInvisibleSpine`

- `Boolean spineTickInAdditionalFrame`

- `Int32 visibilityColliderBallRadius`

- `Boolean showRecordNumber`

- `String recordNumber`

- `String beianUrl`

- `Boolean enableBattlePostprocessAA`

- `Boolean enableACEService`

- `Boolean enableACEData4`

- `Boolean enableRoguelikeSeedMode`


## Methods

- `Boolean get_isAuditMode()`

- `Boolean get_enableDBCheck()`

- `Boolean get_enableLuaPlayerData()`

- `Boolean get_enableGameBI()`

- `Boolean get_enableHGSDKPollingConfirm()`

- `String get_inlandAgeTips()`

- `Boolean get_enableFastPlayerDelta()`

- `Boolean get_haltIfHotUpdateUnzipError()`

- `Boolean get_enableHotUpdateLargePack()`

- `Boolean get_enableIAPProdCheck()`

- `Boolean get_disableGuest()`

- `Boolean get_enableNetCheck()`

- `Boolean get_announceUseWeb()`

- `Boolean get_disableBuffTemplateDB()`

- `Int32 get_HGSDKV2()`

- `Int32 get_HGDownload()`

- `Boolean get_enableAsyncResCheck()`

- `Int32 get_effectPreloadStripBound()`

- `Boolean get_enableBattleAnimationLazyLoad()`

- `Boolean get_enableNativeLicense()`

- `Boolean get_enableHGString()`

- `Boolean get_enableFastBattleFinish()`

- `Int32 get_fastAddPages()`

- `Int32 get_fastBattleFinish()`

- `Boolean get_enableCrossAppShare()`

- `Int32 get_margueeType()`

- `Boolean get_renderInvisibleSpine()`

- `Boolean get_renderMultiPlayerInvisibleSpine()`

- `Boolean get_spineTickInAdditionalFrame()`

- `Int32 get_visibilityColliderBallRadius()`

- `Boolean get_showRecordNumber()`

- `String get_recordNumber()`

- `String get_beianUrl()`

- `Boolean get_enableBattlePostprocessAA()`

- `Boolean get_enableACEService()`

- `Boolean get_enableACEData4()`

- `Boolean get_enableRoguelikeSeedMode()`

- `Boolean SetData(String)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Config
public class RemoteConfig : Singleton`1
{
	private InternalConfig m_config; // 0x10
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate8 __Hotfix0_get_isAuditMode; // 0x8
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableDBCheck; // 0x10
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableLuaPlayerData; // 0x18
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableGameBI; // 0x20
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableHGSDKPollingConfirm; // 0x28
	private static __XLua_Gen_Delegate89 __Hotfix0_get_inlandAgeTips; // 0x30
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableFastPlayerDelta; // 0x38
	private static __XLua_Gen_Delegate8 __Hotfix0_get_haltIfHotUpdateUnzipError; // 0x40
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableHotUpdateLargePack; // 0x48
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableIAPProdCheck; // 0x50
	private static __XLua_Gen_Delegate8 __Hotfix0_get_disableGuest; // 0x58
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableNetCheck; // 0x60
	private static __XLua_Gen_Delegate8 __Hotfix0_get_announceUseWeb; // 0x68
	private static __XLua_Gen_Delegate8 __Hotfix0_get_disableBuffTemplateDB; // 0x70
	private static __XLua_Gen_Delegate10 __Hotfix0_get_HGSDKV2; // 0x78
	private static __XLua_Gen_Delegate10 __Hotfix0_get_HGDownload; // 0x80
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableAsyncResCheck; // 0x88
	private static __XLua_Gen_Delegate10 __Hotfix0_get_effectPreloadStripBound; // 0x90
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableBattleAnimationLazyLoad; // 0x98
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableNativeLicense; // 0xa0
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableHGString; // 0xa8
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableFastBattleFinish; // 0xb0
	private static __XLua_Gen_Delegate10 __Hotfix0_get_fastAddPages; // 0xb8
	private static __XLua_Gen_Delegate10 __Hotfix0_get_fastBattleFinish; // 0xc0
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableCrossAppShare; // 0xc8
	private static __XLua_Gen_Delegate10 __Hotfix0_get_margueeType; // 0xd0
	private static __XLua_Gen_Delegate8 __Hotfix0_get_renderInvisibleSpine; // 0xd8
	private static __XLua_Gen_Delegate8 __Hotfix0_get_renderMultiPlayerInvisibleSpine; // 0xe0
	private static __XLua_Gen_Delegate8 __Hotfix0_get_spineTickInAdditionalFrame; // 0xe8
	private static __XLua_Gen_Delegate10 __Hotfix0_get_visibilityColliderBallRadius; // 0xf0
	private static __XLua_Gen_Delegate8 __Hotfix0_get_showRecordNumber; // 0xf8
	private static __XLua_Gen_Delegate89 __Hotfix0_get_recordNumber; // 0x100
	private static __XLua_Gen_Delegate89 __Hotfix0_get_beianUrl; // 0x108
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableBattlePostprocessAA; // 0x110
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableACEService; // 0x118
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableACEData4; // 0x120
	private static __XLua_Gen_Delegate8 __Hotfix0_get_enableRoguelikeSeedMode; // 0x128
	private static __XLua_Gen_Delegate170 __Hotfix0_SetData; // 0x130

	public Boolean isAuditMode { get; }
	public Boolean enableDBCheck { get; }
	public Boolean enableLuaPlayerData { get; }
	public Boolean enableGameBI { get; }
	public Boolean enableHGSDKPollingConfirm { get; }
	public String inlandAgeTips { get; }
	public Boolean enableFastPlayerDelta { get; }
	public Boolean haltIfHotUpdateUnzipError { get; }
	public Boolean enableHotUpdateLargePack { get; }
	public Boolean enableIAPProdCheck { get; }
	public Boolean disableGuest { get; }
	public Boolean enableNetCheck { get; }
	public Boolean announceUseWeb { get; }
	public Boolean disableBuffTemplateDB { get; }
	public Int32 HGSDKV2 { get; }
	public Int32 HGDownload { get; }
	public Boolean enableAsyncResCheck { get; }
	public Int32 effectPreloadStripBound { get; }
	public Boolean enableBattleAnimationLazyLoad { get; }
	public Boolean enableNativeLicense { get; }
	public Boolean enableHGString { get; }
	public Boolean enableFastBattleFinish { get; }
	public Int32 fastAddPages { get; }
	public Int32 fastBattleFinish { get; }
	public Boolean enableCrossAppShare { get; }
	public Int32 margueeType { get; }
	public Boolean renderInvisibleSpine { get; }
	public Boolean renderMultiPlayerInvisibleSpine { get; }
	public Boolean spineTickInAdditionalFrame { get; }
	public Int32 visibilityColliderBallRadius { get; }
	public Boolean showRecordNumber { get; }
	public String recordNumber { get; }
	public String beianUrl { get; }
	public Boolean enableBattlePostprocessAA { get; }
	public Boolean enableACEService { get; }
	public Boolean enableACEData4 { get; }
	public Boolean enableRoguelikeSeedMode { get; }

	// RVA: 0x67b6e0c VA: 0x7598dcee0c
	private Void .ctor() { }
	// RVA: 0x67b6fc8 VA: 0x7598dcefc8
	public Boolean get_isAuditMode() { }
	// RVA: 0x67b7044 VA: 0x7598dcf044
	public Boolean get_enableDBCheck() { }
	// RVA: 0x67b70c0 VA: 0x7598dcf0c0
	public Boolean get_enableLuaPlayerData() { }
	// RVA: 0x67b713c VA: 0x7598dcf13c
	public Boolean get_enableGameBI() { }
	// RVA: 0x67b71b8 VA: 0x7598dcf1b8
	public Boolean get_enableHGSDKPollingConfirm() { }
	// RVA: 0x67b7234 VA: 0x7598dcf234
	public String get_inlandAgeTips() { }
	// RVA: 0x67b72b0 VA: 0x7598dcf2b0
	public Boolean get_enableFastPlayerDelta() { }
	// RVA: 0x67b732c VA: 0x7598dcf32c
	public Boolean get_haltIfHotUpdateUnzipError() { }
	// RVA: 0x67b73a8 VA: 0x7598dcf3a8
	public Boolean get_enableHotUpdateLargePack() { }
	// RVA: 0x67b7424 VA: 0x7598dcf424
	public Boolean get_enableIAPProdCheck() { }
	// RVA: 0x67b74a0 VA: 0x7598dcf4a0
	public Boolean get_disableGuest() { }
	// RVA: 0x67b751c VA: 0x7598dcf51c
	public Boolean get_enableNetCheck() { }
	// RVA: 0x67b7598 VA: 0x7598dcf598
	public Boolean get_announceUseWeb() { }
	// RVA: 0x67b7614 VA: 0x7598dcf614
	public Boolean get_disableBuffTemplateDB() { }
	// RVA: 0x67b7690 VA: 0x7598dcf690
	public Int32 get_HGSDKV2() { }
	// RVA: 0x67b770c VA: 0x7598dcf70c
	public Int32 get_HGDownload() { }
	// RVA: 0x67b7788 VA: 0x7598dcf788
	public Boolean get_enableAsyncResCheck() { }
	// RVA: 0x67b7804 VA: 0x7598dcf804
	public Int32 get_effectPreloadStripBound() { }
	// RVA: 0x67b7880 VA: 0x7598dcf880
	public Boolean get_enableBattleAnimationLazyLoad() { }
	// RVA: 0x67b78fc VA: 0x7598dcf8fc
	public Boolean get_enableNativeLicense() { }
	// RVA: 0x67b7978 VA: 0x7598dcf978
	public Boolean get_enableHGString() { }
	// RVA: 0x67b79f4 VA: 0x7598dcf9f4
	public Boolean get_enableFastBattleFinish() { }
	// RVA: 0x67b7a70 VA: 0x7598dcfa70
	public Int32 get_fastAddPages() { }
	// RVA: 0x67b7aec VA: 0x7598dcfaec
	public Int32 get_fastBattleFinish() { }
	// RVA: 0x67b7b68 VA: 0x7598dcfb68
	public Boolean get_enableCrossAppShare() { }
	// RVA: 0x67b7be4 VA: 0x7598dcfbe4
	public Int32 get_margueeType() { }
	// RVA: 0x67b7c60 VA: 0x7598dcfc60
	public Boolean get_renderInvisibleSpine() { }
	// RVA: 0x67b7cdc VA: 0x7598dcfcdc
	public Boolean get_renderMultiPlayerInvisibleSpine() { }
	// RVA: 0x67b7d58 VA: 0x7598dcfd58
	public Boolean get_spineTickInAdditionalFrame() { }
	// RVA: 0x67b7dd4 VA: 0x7598dcfdd4
	public Int32 get_visibilityColliderBallRadius() { }
	// RVA: 0x67b7e50 VA: 0x7598dcfe50
	public Boolean get_showRecordNumber() { }
	// RVA: 0x67b7ecc VA: 0x7598dcfecc
	public String get_recordNumber() { }
	// RVA: 0x67b7f48 VA: 0x7598dcff48
	public String get_beianUrl() { }
	// RVA: 0x67b7fc4 VA: 0x7598dcffc4
	public Boolean get_enableBattlePostprocessAA() { }
	// RVA: 0x67b8040 VA: 0x7598dd0040
	public Boolean get_enableACEService() { }
	// RVA: 0x67b80bc VA: 0x7598dd00bc
	public Boolean get_enableACEData4() { }
	// RVA: 0x67b8138 VA: 0x7598dd0138
	public Boolean get_enableRoguelikeSeedMode() { }
	// RVA: 0x67b81b4 VA: 0x7598dd01b4
	public Boolean SetData(String json) { }
}
```