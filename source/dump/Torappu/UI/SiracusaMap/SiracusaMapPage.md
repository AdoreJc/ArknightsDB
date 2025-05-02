# SiracusaMapPage

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Boolean m_isTopMenuSortingOrderSet`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `SiracusaMapNotify _siracusaMapNotify`

- `String m_groupId`

- `Boolean m_isRetro`

- `Param m_enterParam`


## Properties

- `String groupId`

- `Boolean isRetro`

- `Param enterParam`


## Methods

- `String get_groupId()`

- `Boolean get_isRetro()`

- `Param get_enterParam()`

- `Void _OnBackClicked()`

- `Void _CommonQuit()`

- `Boolean IsTransitting()`

- `Void AddTaskRingRewardStateTop()`

- `Void AddAVGChatStateTop()`

- `Void AddCharCardBattlePreviewState()`

- `Void AddCharCardBagStateTop()`

- `Void AddCharSelectGotoStateTop()`

- `Void AddCharSelectStateTop()`

- `Void _SetSortingOrderIfNot()`

- `Void AddRewardState()`

- `Void ShowToast(String, Boolean)`

- `Void <OnCreate>b__15_0(GameObject)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapPage : StateEnginePage
{
	public const String KEY_PARAM_BUNDLE; // 0x0
	private const Int32 KEY_PREVIEW_TOPMENU_SORTING_ORDER; // 0x0
	private Boolean m_isTopMenuSortingOrderSet; // 0xe8
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xf0
	private SiracusaMapNotify _siracusaMapNotify; // 0xf8
	private String m_groupId; // 0x100
	private Boolean m_isRetro; // 0x108
	private Param m_enterParam; // 0x110
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x8
	private static DelegateBridge __Hotfix0_get_enterParam; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x20
	private static DelegateBridge __Hotfix0__CommonQuit; // 0x28
	private static DelegateBridge __Hotfix0_IsTransitting; // 0x30
	private static DelegateBridge __Hotfix0_AddTaskRingRewardStateTop; // 0x38
	private static DelegateBridge __Hotfix0_AddAVGChatStateTop; // 0x40
	private static DelegateBridge __Hotfix0_AddCharCardBattlePreviewState; // 0x48
	private static DelegateBridge __Hotfix0_AddCharCardBagStateTop; // 0x50
	private static DelegateBridge __Hotfix0_AddCharSelectGotoStateTop; // 0x58
	private static DelegateBridge __Hotfix0_AddCharSelectStateTop; // 0x60
	private static DelegateBridge __Hotfix0__SetSortingOrderIfNot; // 0x68
	private static DelegateBridge __Hotfix0_AddRewardState; // 0x70
	private static DelegateBridge __Hotfix0_ShowToast; // 0x78
	private static DelegateBridge __Hotfix0_GenPageStackToJumpBack; // 0x80
	private static DelegateBridge __Hotfix0_SaveParamToBundle; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public String groupId { get; }
	public Boolean isRetro { get; }
	public Param enterParam { get; }

	// RVA: 0x2400444 VA: 0x7594a18444
	public String get_groupId() { }
	// RVA: 0x24004ac VA: 0x7594a184ac
	public Boolean get_isRetro() { }
	// RVA: 0x2401174 VA: 0x7594a19174
	public Param get_enterParam() { }
	// RVA: 0x24049c0 VA: 0x7594a1c9c0
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2404b08 VA: 0x7594a1cb08
	private Void _OnBackClicked() { }
	// RVA: 0x2404c58 VA: 0x7594a1cc58
	private Void _CommonQuit() { }
	// RVA: 0x2404d08 VA: 0x7594a1cd08
	public Boolean IsTransitting() { }
	// RVA: 0x24025d8 VA: 0x7594a1a5d8
	public Void AddTaskRingRewardStateTop() { }
	// RVA: 0x2402668 VA: 0x7594a1a668
	public Void AddAVGChatStateTop() { }
	// RVA: 0x24026f8 VA: 0x7594a1a6f8
	public Void AddCharCardBattlePreviewState() { }
	// RVA: 0x24029f4 VA: 0x7594a1a9f4
	public Void AddCharCardBagStateTop() { }
	// RVA: 0x2404d9c VA: 0x7594a1cd9c
	public Void AddCharSelectGotoStateTop() { }
	// RVA: 0x2402b90 VA: 0x7594a1ab90
	public Void AddCharSelectStateTop() { }
	// RVA: 0x2404e2c VA: 0x7594a1ce2c
	private Void _SetSortingOrderIfNot() { }
	// RVA: 0x2403eb0 VA: 0x7594a1beb0
	public Void AddRewardState() { }
	// RVA: 0x2401e28 VA: 0x7594a19e28
	public Void ShowToast(String tips, Boolean isStrongAlert) { }
	// RVA: 0x240387c VA: 0x7594a1b87c
	public static List`1 GenPageStackToJumpBack(DataBundle stageBundle, Param param) { }
	// RVA: 0x2404f2c VA: 0x7594a1cf2c
	public static Void SaveParamToBundle(Param param, DataBundle targetBundle) { }
	// RVA: 0x2405080 VA: 0x7594a1d080
	public Void .ctor() { }
	// RVA: 0x24050f0 VA: 0x7594a1d0f0
	private Void <OnCreate>b__15_0(GameObject inst) { }
	// RVA: 0x24051a8 VA: 0x7594a1d1a8
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```