# BossRushPage

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushCacheData m_cachedData`

- `String m_actId`


## Properties

- `String activityId`


## Methods

- `String get_activityId()`

- `BossRushCacheData ConsumeCacheParam()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushPage : StateEnginePage, IHotfixable
{
	private const String KEY_PARAM_BUNDLE; // 0x0
	private BossRushCacheData m_cachedData; // 0xe8
	private String m_actId; // 0x100
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x18
	private static DelegateBridge __Hotfix0_GenPageStackToJumpBack; // 0x20
	private static DelegateBridge __Hotfix0_SaveParamToBundle; // 0x28
	private static DelegateBridge __Hotfix0_LoadParamFromBundle; // 0x30
	private static DelegateBridge __Hotfix0_ConsumeCacheParam; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String activityId { get; }

	// RVA: 0x2e589b8 VA: 0x75954709b8
	public String get_activityId() { }
	// RVA: 0x2e58a20 VA: 0x7595470a20
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2e58bd0 VA: 0x7595470bd0
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2e58ca4 VA: 0x7595470ca4
	public static CommonTopMenu CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x2e58e1c VA: 0x7595470e1c
	public static List`1 GenPageStackToJumpBack(DataBundle stagePageBundle, Params param) { }
	// RVA: 0x2e59168 VA: 0x7595471168
	public static Void SaveParamToBundle(String actId, String stageGroupId, String stageId, String teamId, DataBundle targetBundle) { }
	// RVA: 0x2e5931c VA: 0x759547131c
	public static Params LoadParamFromBundle(DataBundle bundleToJumpBack) { }
	// RVA: 0x2e59530 VA: 0x7595471530
	public BossRushCacheData ConsumeCacheParam() { }
	// RVA: 0x2e595d0 VA: 0x75954715d0
	public Void .ctor() { }
	// RVA: 0x2e59640 VA: 0x7595471640
	private IEnumerator <>n__0() { }
	// RVA: 0x2e59648 VA: 0x7595471648
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2e59650 VA: 0x7595471650
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```