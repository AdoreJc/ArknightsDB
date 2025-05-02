# ZoneRecordPage

**Namespace:** `Torappu.UI.Stage.ZoneRecord`


## Fields

- `RectTransform _recordHolderContainer`


## Properties

- `RectTransform controllerContainer`


## Methods

- `RectTransform get_controllerContainer()`

- `Void OnBackClicked()`

- `Boolean IsTransitting()`

- `Boolean LoadAsset(String, out)`

- `Boolean LoadSpriteFromAutoPackHub(String, String, out)`

- `String TryLoadTextAssets(String)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStateEngineReady(Boolean)`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord
public class ZoneRecordPage : StateEnginePage, IHotfixable
{
	private RectTransform _recordHolderContainer; // 0xe8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnStateEngineReady; // 0x8
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x10
	private static DelegateBridge __Hotfix0_get_controllerContainer; // 0x18
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x20
	private static DelegateBridge __Hotfix0_IsTransitting; // 0x28
	private static DelegateBridge __Hotfix0_SendGetZoneRecordReward; // 0x30
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x38
	private static DelegateBridge __Hotfix0_LoadSpriteFromAutoPackHub; // 0x40
	private static DelegateBridge __Hotfix0_TryLoadTextAssets; // 0x48
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public RectTransform controllerContainer { get; }

	// RVA: 0x2fcc8d4 VA: 0x75955e48d4
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2fcc958 VA: 0x75955e4958
	protected override Void OnStateEngineReady(Boolean isFromStack) { }
	// RVA: 0x2fcc9dc VA: 0x75955e49dc
	protected override Void OnPageRouted() { }
	// RVA: 0x2fcc334 VA: 0x75955e4334
	public RectTransform get_controllerContainer() { }
	// RVA: 0x2fcc78c VA: 0x75955e478c
	public Void OnBackClicked() { }
	// RVA: 0x2fcca48 VA: 0x75955e4a48
	public Boolean IsTransitting() { }
	// RVA: 0x2fccadc VA: 0x75955e4adc
	public static Void SendGetZoneRecordReward(String[] stageIds, Action`1 handler) { }
	// RVA: 0x VA: 0x0
	public Boolean LoadAsset(String assetPath, out T asset) { }
	// RVA: 0x2fccd10 VA: 0x75955e4d10
	public Boolean LoadSpriteFromAutoPackHub(String spriteId, String hubPath, out Sprite sprite) { }
	// RVA: 0x2fccec8 VA: 0x75955e4ec8
	public String TryLoadTextAssets(String path) { }
	// RVA: 0x2fcd09c VA: 0x75955e509c
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x2fcd194 VA: 0x75955e5194
	public Void .ctor() { }
	// RVA: 0x2fcd204 VA: 0x75955e5204
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2fcd20c VA: 0x75955e520c
	private Void <>xLuaBaseProxy_OnStateEngineReady(Boolean P0) { }
	// RVA: 0x2fcd218 VA: 0x75955e5218
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```