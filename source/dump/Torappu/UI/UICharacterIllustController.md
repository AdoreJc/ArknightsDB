# UICharacterIllustController

**Namespace:** `Torappu.UI`


## Fields

- `Config m_config`

- `String m_activeIllustId`

- `Boolean m_pausedByDynEntrance`

- `Coroutine m_activateIllustCoroutine`


## Methods

- `Void Update()`

- `Void _OnSettingChanged(SettingType)`

- `Config GetConfig()`

- `UICharacterIllust _GachaOnlyLoadChrIllust(AbstractAssetLoader, CharacterConfig, RectTransform)`

- `UICharacterIllust _GachaOnlyLoadChrStaticIllust(AbstractAssetLoader, CharUISkinStruct, RectTransform)`

- `UICharacterIllust _BattleFinishOnlyLoadChrStaticIllust(CharUISkinStruct, RectTransform)`

- `UICharacterIllust _HomeOnlyLoadChrIllust(UICharacterIllustLoader, CharUISkinStruct, RectTransform)`

- `UICharacterIllust _SkinShopOnlyLoadChrIllust(UICharacterIllustLoader, CharUISkinStruct, RectTransform)`

- `UICharacterIllust _LoadChrIllust(IUICharacterIllustLoader, CharUISkinStruct, RectTransform)`

- `UICharacterIllust _LoadChrDynamicIllust(CharUISkinStruct, RectTransform)`

- `UICharacterIllust _LoadChrStaticIllust(IUICharacterIllustLoader, CharUISkinStruct, RectTransform)`

- `UICharacterIllust _LoadNpcStaticIllust(NPCConfig)`

- `Void _RefreshConfig()`

- `Void _ActivateIllust(String, Boolean)`

- `Boolean _IsActiveIllust(UICharacterIllust)`

- `Void _AddIllustRef(UICharacterIllust)`

- `Void _RemoveIllustRef(UICharacterIllust)`

- `Void _RemoveInvalidIllustRef()`

- `Void _PostProcessOnRemove()`

- `Void _ResumeDynInstanceIfNecessary()`

- `Void _PauseDynInstanceIfNecessary()`

- `Boolean _ContainsTarget(String)`

- `Boolean _IsStaticTarget(String)`

- `Void _ActivateIllustImmediately()`

- `IEnumerator _ActivateIllustCoroutine()`

- `Void _PauseDynIllustByDynEntrance(Boolean)`

- `Void _PlayStartByDynEntrance(CharUISkinStruct)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterIllustController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private List`1 m_illusts; // 0x18
	private Config m_config; // 0x20
	private String m_activeIllustId; // 0x30
	private Boolean m_pausedByDynEntrance; // 0x38
	private Coroutine m_activateIllustCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0__OnSettingChanged; // 0x18
	private static DelegateBridge __Hotfix0_GetConfig; // 0x20
	private static DelegateBridge __Hotfix0__GachaOnlyLoadChrIllust; // 0x28
	private static DelegateBridge __Hotfix0__GachaOnlyLoadChrStaticIllust; // 0x30
	private static DelegateBridge __Hotfix0__BattleFinishOnlyLoadChrStaticIllust; // 0x38
	private static DelegateBridge __Hotfix0__HomeOnlyLoadChrIllust; // 0x40
	private static DelegateBridge __Hotfix0__SkinShopOnlyLoadChrIllust; // 0x48
	private static DelegateBridge __Hotfix0__LoadChrIllust; // 0x50
	private static DelegateBridge __Hotfix0__LoadChrDynamicIllust; // 0x58
	private static DelegateBridge __Hotfix0__LoadChrStaticIllust; // 0x60
	private static DelegateBridge __Hotfix0__LoadNpcStaticIllust; // 0x68
	private static DelegateBridge __Hotfix0__RefreshConfig; // 0x70
	private static DelegateBridge __Hotfix0__ActivateIllust; // 0x78
	private static DelegateBridge __Hotfix0__IsActiveIllust; // 0x80
	private static DelegateBridge __Hotfix0__AddIllustRef; // 0x88
	private static DelegateBridge __Hotfix0__RemoveIllustRef; // 0x90
	private static DelegateBridge __Hotfix0__RemoveInvalidIllustRef; // 0x98
	private static DelegateBridge __Hotfix0__PostProcessOnRemove; // 0xa0
	private static DelegateBridge __Hotfix0__ResumeDynInstanceIfNecessary; // 0xa8
	private static DelegateBridge __Hotfix0__PauseDynInstanceIfNecessary; // 0xb0
	private static DelegateBridge __Hotfix0__ContainsTarget; // 0xb8
	private static DelegateBridge __Hotfix0__IsStaticTarget; // 0xc0
	private static DelegateBridge __Hotfix0__ActivateIllustImmediately; // 0xc8
	private static DelegateBridge __Hotfix0__ActivateIllustCoroutine; // 0xd0
	private static DelegateBridge __Hotfix0__PauseDynIllustByDynEntrance; // 0xd8
	private static DelegateBridge __Hotfix0__PlayStartByDynEntrance; // 0xe0
	private static DelegateBridge __Hotfix0_GachaOnlyLoadChrIllust; // 0xe8
	private static DelegateBridge __Hotfix0_BattleFinishOnlyLoadChrStaticIllust; // 0xf0
	private static DelegateBridge __Hotfix0_HomeOnlyLoadChrIllust; // 0xf8
	private static DelegateBridge __Hotfix0_SkinShopOnlyLoadChrIllust; // 0x100
	private static DelegateBridge __Hotfix0_LoadChrIllust; // 0x108
	private static DelegateBridge __Hotfix0_LoadChrStaticIllust; // 0x110
	private static DelegateBridge __Hotfix0_LoadNpcStaticIllust; // 0x118
	private static DelegateBridge __Hotfix0_GetIllustConfig; // 0x120
	private static DelegateBridge __Hotfix0_PauseDynIllustByDynEntrance; // 0x128
	private static DelegateBridge __Hotfix0_PlayStartByDynEntrance; // 0x130
	private static DelegateBridge __Hotfix0_HomeOnlyUseDynIllust; // 0x138
	private static DelegateBridge _c__Hotfix0_ctor; // 0x140


	// RVA: 0x2117f9c VA: 0x759472ff9c
	protected override Void Awake() { }
	// RVA: 0x21182f4 VA: 0x75947302f4
	private Void Update() { }
	// RVA: 0x21185ec VA: 0x75947305ec
	protected override Void OnDestroy() { }
	// RVA: 0x2118784 VA: 0x7594730784
	private Void _OnSettingChanged(SettingType settingType) { }
	// RVA: 0x2115320 VA: 0x759472d320
	public Config GetConfig() { }
	// RVA: 0x2118818 VA: 0x7594730818
	private UICharacterIllust _GachaOnlyLoadChrIllust(AbstractAssetLoader assetLoader, CharacterConfig config, RectTransform parent) { }
	// RVA: 0x2118cd0 VA: 0x7594730cd0
	private UICharacterIllust _GachaOnlyLoadChrStaticIllust(AbstractAssetLoader assetLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x2119180 VA: 0x7594731180
	private UICharacterIllust _BattleFinishOnlyLoadChrStaticIllust(CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x2119474 VA: 0x7594731474
	private UICharacterIllust _HomeOnlyLoadChrIllust(UICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x2119880 VA: 0x7594731880
	private UICharacterIllust _SkinShopOnlyLoadChrIllust(UICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x21199c8 VA: 0x75947319c8
	private UICharacterIllust _LoadChrIllust(IUICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x2118a68 VA: 0x7594730a68
	private UICharacterIllust _LoadChrDynamicIllust(CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x21195cc VA: 0x75947315cc
	private UICharacterIllust _LoadChrStaticIllust(IUICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x2119c5c VA: 0x7594731c5c
	private UICharacterIllust _LoadNpcStaticIllust(NPCConfig npcConfig) { }
	// RVA: 0x2118104 VA: 0x7594730104
	private Void _RefreshConfig() { }
	// RVA: 0x2119e3c VA: 0x7594731e3c
	private Void _ActivateIllust(String targetIllustId, Boolean fastMode) { }
	// RVA: 0x211847c VA: 0x759473047c
	private Boolean _IsActiveIllust(UICharacterIllust illsut) { }
	// RVA: 0x2118fe8 VA: 0x7594730fe8
	private Void _AddIllustRef(UICharacterIllust illust) { }
	// RVA: 0x211a5ec VA: 0x75947325ec
	private Void _RemoveIllustRef(UICharacterIllust illust) { }
	// RVA: 0x211a234 VA: 0x7594732234
	private Void _RemoveInvalidIllustRef() { }
	// RVA: 0x211a6dc VA: 0x75947326dc
	private Void _PostProcessOnRemove() { }
	// RVA: 0x211aa40 VA: 0x7594732a40
	private Void _ResumeDynInstanceIfNecessary() { }
	// RVA: 0x211a878 VA: 0x7594732878
	private Void _PauseDynInstanceIfNecessary() { }
	// RVA: 0x2119f80 VA: 0x7594731f80
	private Boolean _ContainsTarget(String targetIllustId) { }
	// RVA: 0x211a0d0 VA: 0x75947320d0
	private Boolean _IsStaticTarget(String targetIllustId) { }
	// RVA: 0x211a390 VA: 0x7594732390
	private Void _ActivateIllustImmediately() { }
	// RVA: 0x211a540 VA: 0x7594732540
	private IEnumerator _ActivateIllustCoroutine() { }
	// RVA: 0x211ac40 VA: 0x7594732c40
	private Void _PauseDynIllustByDynEntrance(Boolean pause) { }
	// RVA: 0x211acf8 VA: 0x7594732cf8
	private Void _PlayStartByDynEntrance(CharUISkinStruct skin) { }
	// RVA: 0x211aed0 VA: 0x7594732ed0
	public static UICharacterIllust GachaOnlyLoadChrIllust(AbstractAssetLoader assetLoader, CharacterConfig config, RectTransform parent) { }
	// RVA: 0x211b05c VA: 0x759473305c
	public static UICharacterIllust BattleFinishOnlyLoadChrStaticIllust(CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x211b1ac VA: 0x75947331ac
	public static UICharacterIllust HomeOnlyLoadChrIllust(UICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x211b318 VA: 0x7594733318
	public static UICharacterIllust SkinShopOnlyLoadChrIllust(UICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x211b484 VA: 0x7594733484
	public static UICharacterIllust LoadChrIllust(IUICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x211b5f0 VA: 0x75947335f0
	public static UICharacterIllust LoadChrStaticIllust(IUICharacterIllustLoader staticIllustLoader, CharUISkinStruct skin, RectTransform parent) { }
	// RVA: 0x211b75c VA: 0x759473375c
	public static UICharacterIllust LoadNpcStaticIllust(NPCConfig config) { }
	// RVA: 0x211b8b4 VA: 0x75947338b4
	public static Config GetIllustConfig() { }
	// RVA: 0x2116f80 VA: 0x759472ef80
	public static Void PauseDynIllustByDynEntrance(Boolean pause) { }
	// RVA: 0x2114ed0 VA: 0x759472ced0
	public static Void PlayStartByDynEntrance(CharUISkinStruct skin) { }
	// RVA: 0x211b9fc VA: 0x75947339fc
	public static Boolean HomeOnlyUseDynIllust(LoadStrategy strategy) { }
	// RVA: 0x211ba68 VA: 0x7594733a68
	public Void .ctor() { }
}
```