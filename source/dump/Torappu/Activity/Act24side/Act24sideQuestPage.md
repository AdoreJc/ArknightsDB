# Act24sideQuestPage

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String m_actId`

- `String m_selectStageId`


## Properties

- `String actId`

- `String selectStageId`


## Methods

- `String get_actId()`

- `String get_selectStageId()`

- `DataBundle CreateRecoverDataBundleForBattle(String)`

- `Void <>xLuaBaseProxy_OnStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestPage : StateEnginePage
{
	public const String KEY_PARAM_BUNDLE; // 0x0
	private String m_actId; // 0xe8
	private String m_selectStageId; // 0xf0
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_selectStageId; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_CreateRecoverDataBundleForBattle; // 0x18
	private static DelegateBridge __Hotfix0_GenPageStackToJumpBack; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String actId { get; }
	public String selectStageId { get; }

	// RVA: 0x32c0a20 VA: 0x75958d8a20
	public String get_actId() { }
	// RVA: 0x32c0a88 VA: 0x75958d8a88
	public String get_selectStageId() { }
	// RVA: 0x32c0af0 VA: 0x75958d8af0
	protected override Void OnStart() { }
	// RVA: 0x32c0bb4 VA: 0x75958d8bb4
	public DataBundle CreateRecoverDataBundleForBattle(String selectStageId) { }
	// RVA: 0x32c0ddc VA: 0x75958d8ddc
	public static List`1 GenPageStackToJumpBack(DataBundle stageBundle, Param questPageParam) { }
	// RVA: 0x32c1128 VA: 0x75958d9128
	public Void .ctor() { }
	// RVA: 0x32c1198 VA: 0x75958d9198
	private Void <>xLuaBaseProxy_OnStart() { }
}
```